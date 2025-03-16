# Webscrapping with python - Extracting Product Data
Overview:
  This project demonstrates web scraping using Python with requests and BeautifulSoup. The script extracts product information from a sample webpage and stores it in a CSV file.
Technologies Used:
  1)Python
  2)Requests library for making HTTP requests
  3)BeautifulSoup from bs4 for parsing HTML
  4)Pandas for data manipulation
How It Works
>>The script fetches the HTML content of the webpage.
>>It parses the HTML using BeautifulSoup to extract product details.
>>The extracted data is cleaned and structured into lists.
>>A Pandas DataFrame is created to store the data.
>>The data is saved as a CSV file named products.csv.

Installation:
>>To run this script, ensure you have the required dependencies installed:

pip install requests beautifulsoup4 pandas
Usage
Run the script using Python:
python script.py
This will generate a products.csv file containing the extracted product data.

Sample Output:
The extracted data is stored in products.csv with the following columns:
>>Book Name
>>Price
>>Stock

Example:
Book Name,Price,Stock

Wings of fire,$5.00,50

Secret of success,$4.00,10

5 steps to success,3.0,34
