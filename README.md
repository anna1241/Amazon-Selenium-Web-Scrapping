# Amazon Selenium Web Scraping

## Overview
This project utilizes Selenium to scrape data from the Amazon website for a specified product. The scraped information includes essential details such as the product title, price, rating, total rating count, delivery time, and image URL.

## Features
1. **Scrapped Data:**
   - The scraped data is organized into the following columns: Title, Price, Rating, Total Rating Count, Delivery Time, and Image URL.
   - In case delivery time is not provided, it will be marked as N/A or left as an empty field in the CSV file.

2. **CSV Data Storage:**
   - The scraped data is saved into a CSV file for easy accessibility and analysis.

3. **Data Analysis with Pandas:**
   - The project includes functionality to read the CSV data into a Pandas dataframe.
   - The dataframe is then displayed, allowing users to explore and analyze the scraped data efficiently.
