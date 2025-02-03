# ETL-Project-1
This project was from a Hands-on lab activity from an online course. This is about extracting information from the List of Largest Banks in the world. 

The tasks/goals of this project are as follows:
1. Write a function log_progress() to log progress of the code at different stages in a file code_log.txt.
2. Extract the tabular information from the given URL under the heading 'By Market Capitalization'.
3. Convert the extracted tabular information to dataframe.
4. Transform the dataframe by adding new columns for 'Market Capitalization' (GBP, EUR, INR). Round the decimal places to 2 based on the exchange rate information shared from the CSV file.
5. Load the transformed dataframe to an output CSV file and SQL database.
6. Perform simple queries on the database. Write a function load_to_db() to execute a given set of queries to verify the output.

CSV file = exchange_rate.csv
URL = https://en.wikipedia.org/wiki/List_of_largest_banks
