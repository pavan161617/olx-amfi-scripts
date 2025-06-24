# OLX & AMFI Data Scraper Scripts

## 🔍 Script 1: OLX Car Cover Scraper (`olx_scraper.py`)
- Scrapes "Car Cover" listings from OLX India (`https://www.olx.in/items/q-car-cover`)
- Extracts item title, price, and location
- Saves results in a text file: `olx_car_covers.txt`

## 📊 Script 2: AMFI NAV Extractor (`extract_amfi.sh`)
- Downloads mutual fund data from AMFI India (`https://www.amfiindia.com/spages/NAVAll.txt`)
- Extracts **Scheme Name** and **Asset Value**
- Saves output in a `.tsv` (Tab-Separated Values) file: `amfi_data.tsv`

## ⚙️ Technologies Used
- Python 3
- Bash (for shell script)
- BeautifulSoup & Requests (for web scraping)

## 📁 How to Run
```bash
# Python script
python olx_scraper.py

# Shell script (on Unix/Linux or Git Bash on Windows)
bash extract_amfi.sh
