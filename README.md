# Web Scraping: Indian Military Aircraft Data

## 📌 Objective
The objective of this project is to scrape data from the Wikipedia page **[List of active Indian military aircraft](https://en.wikipedia.org/wiki/List_of_active_Indian_military_aircraft)** using Python and the **BeautifulSoup** library. The extracted data is saved into a CSV file for further analysis.

## 📊 Data Extraction
- The script extracts tabular data from the Wikipedia page.
- Aircraft names are retrieved from the `<a>` tags inside the table.
- Other details (e.g., origin, type, quantity) are extracted from the `<td>` tags.
- Since the table is not uniformly structured, adjustments are made to maintain consistency.

## 🚀 Technologies Used
- **Python**
- **BeautifulSoup** (for web scraping)
- **pandas** (for data processing)
- **requests** (for fetching web pages)

## 📂 Files Included
- **`indian_military_aircraft_scraper.ipynb`** → Jupyter Notebook with the full scraping code.
- **`indian_military_aircraft.csv`** → CSV file containing the scraped data.
- **`README.md`** → This file explaining the project.

## 🔧 How to Run the Script
1. Install required libraries:
   ```bash
   pip install requests beautifulsoup4 pandas
