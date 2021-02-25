# PDF Data Scraping Bot
This bot scrapes invoice data from various PDF documents into an excel spreadsheet. It performs following:
- Gets PDF files from directory and assigns path to a variable.
- Loops through each file in the list and opens it.
- Scrapes data like Invoice ID, Customer ID, total amount etc.
- Creates an excel file and exports data to it.