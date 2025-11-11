# Bookstore Scraper and Analyzer

## Overview
This project is a **web scraping and data analysis tool** that extracts information about books from [Books to Scrape](https://toscrape.com/), processes the data, and visualizes it. It also retrieves detailed information for the top 3 most expensive and bottom 3 cheapest books.

## Purpose
The purpose of this project is to demonstrate how to:

- Automate web data extraction using Selenium.
- Process and analyze scraped data with Python and Pandas.
- Visualize data insights using Matplotlib.
- Extract detailed information for specific items based on criteria (e.g., top and bottom priced books).

## Stack Used
- **Python 3.x**
- **Selenium** – for web scraping and browser automation
- **Pandas** – for data processing and storage
- **Matplotlib** – for data visualization
- **Chrome WebDriver** – to control the Chrome browser

## How to Run
1. Clone the repository:
```bash
git clone <repository_url>
```
2. Install the required Python packages:
```bash
pip install selenium pandas matplotlib
```
3. Download Chrome WebDriver matching your Chrome version and add it to your system PATH.
4. Run the script:
```bash
python bookstore_scraper.py
```
