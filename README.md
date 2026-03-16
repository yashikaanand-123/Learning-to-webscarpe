# Web Scraping: Largest Companies in Canada (2023 Forbes List)

This project demonstrates web scraping techniques by extracting the 2023 Forbes list of largest companies in Canada from Wikipedia. The scraped data is cleaned, structured into a pandas DataFrame, and saved as a CSV file.

## 📋 Project Overview

This script scrapes the [Wikipedia page](https://en.wikipedia.org/wiki/List_of_largest_companies_in_Canada) containing the 2023 Fortune 500 list of Canadian companies. It extracts key company information including:
- Company rank
- Fortune 500 global rank
- Company name
- Industry sector
- Revenue (in USD millions)
- Profits (in USD millions)
- Number of employees
- Headquarters location

## 🛠️ Technologies Used

- **Python 3.x**
- **BeautifulSoup4** - For HTML parsing and data extraction
- **Requests** - For making HTTP requests to the webpage
- **Pandas** - For data structuring and CSV export

## 🚀 How to Run

1. Clone this repository
2. Install required packages:
   ```bash
   pip install requests beautifulsoup4 pandas
