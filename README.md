# API-request-in-python
Here's what's happening in the code:
We make a GET request to the API endpoint using requests.get().
We check if the response was successful  using response.status_code.
If the response was successful, we parse the JSON response using response.json().
We write the extracted data to a CSV file named user_data.csv using a with statement.
We write the header row using f.write().
We write each row of data using f.write() with an f-string to format the data.
Finally, we print a message indicating that the data has been written to the file.
