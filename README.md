# Amazon Product Scraper
This repository contains a Python script to scrape product details from Amazon for PlayStation 4 products. The script extracts information such as product title, price, rating, reviews, and availability, and saves the data into a structured CSV file.

## Table of Contents
Project Overview
Features
Files Included
How to Run the Script
Sample Output
Disclaimer
Author

## Project Overview
The purpose of this project is to demonstrate web scraping techniques using Python. The script scrapes product listings from Amazon's search results page for "PlayStation 4" and extracts key details for further analysis or use.

## Features
Scrapes multiple pages of Amazon search results.
Extracts the following product details:
Title
Price
Rating
Number of Reviews
Availability Status
Saves the scraped data into a clean, tabular CSV file.
Handles missing or inconsistent data gracefully.


## Files Included
scraper.py : The Python script used to scrape data from Amazon.
amazon_data.csv : The CSV file containing the scraped data.
README.md : This file, which provides an overview of the project and instructions.

## How to Run the Script
### Install Required Libraries
Ensure you have the following Python libraries installed:
pip install requests beautifulsoup4 pandas

### Run the Script
Execute the script using the following command:
python scraper.py

### Output
The scraped data will be saved in a file named amazon_data.csv.
Sample Output
The output is a structured CSV file with the following columns:
### Title                               Price    Rating              Reviews         Availability 
***PlayStation 4 Slim 1TB Console***          $369.95  4.7 out of 5 stars  15,779 ratings  In Stock
***Sony Playstation PS4 1TB Black Console***  $200.00  4.6 out of 5 stars  1,600 ratings   Only 2 left in stock - order soon
***Playstation Sony 4 500GB Slim System***   $189.99  4.3 out of 5 stars  378 ratings     Only 2 left in stock - order soon

### Disclaimer
This script is intended for educational purposes only. Scraping data from websites like Amazon may violate their terms of service. Always ensure compliance with the website's policies before using this script.

### Author
This project was created by:
Younas Khan
Google Certified Professional Data Analyst
lyounaskhanl9@gmail.com

### For any questions or feedback, feel free to reach out!
