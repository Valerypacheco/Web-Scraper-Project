#Overview
This repository contains a Python script designed to scrape book prices from the website Books to Scrape. The script extracts book titles and prices, logs this information into a CSV file, and sends an email alert if any book's price drops below a specified threshold.

#Key Features
Web Scraping: Extracts book titles and prices from the Books to Scrape website.
Data Logging: Saves the scraped data into BookData.csv with a timestamp.
Email Notification: Sends an email alert if any book's price falls below £30 (or your specified threshold).

#Running the Script
The script uses a loop to continuously check book prices every hour. Ensure you have sufficient permissions to execute long-running scripts on your system.
