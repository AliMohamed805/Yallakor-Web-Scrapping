# ⚽ Yallakora Match Data Scraper

A Python web scraping project that extracts football match data from [Yallakora](https://www.yallakora.com), a leading Arabic sports news website.

This project collects structured match information for a specific date and exports it into a CSV file, making it suitable for data analysis and reporting.

## 📌 Project Description

The scraper automatically extracts:

- 🏆 Championship / Tournament name
- ⚽ Home team
- ⚽ Away team
- 🔢 Match score
- 🕒 Match time

The output is saved in CSV format using UTF-8 encoding to properly handle Arabic characters.

## 🚀 Features

- Scrape match data for any specific date
- Extract multiple championships from the same page
- Clean and structured CSV export
- Proper Arabic text encoding support
- Simple and lightweight implementation

## 🛠️ Technologies Used

- Python 3.x
- requests
- BeautifulSoup4
- lxml
