# ✈️ JFK Airport Web Scraping & Analysis

Python project for scraping publicly available data related to JFK Airport and analyzing flight activity and customer reviews using `pandas`, `numpy`, and `matplotlib`.

The goal is to build a small end-to-end data pipeline:

1. **Collect** data from the web (e.g., airport review pages).
2. **Load & clean** CSV-based flight datasets.
3. **Merge & transform** the data into an analysis-ready format.
4. **Visualize** patterns in reviews and flight delays/traffic.

This repository is designed as a portfolio project to demonstrate skills in web scraping, data wrangling, and exploratory data analysis in Python.

---

## 📦 Tech Stack

- **Language:** Python 3.x  
- **Libraries:**
  - `requests` – HTTP requests for web pages  
  - `beautifulsoup4` – HTML parsing and scraping  
  - `pandas` – data frames, cleaning, aggregation  
  - `numpy` – numerical operations  
  - `matplotlib` – data visualization  

All dependencies are listed in `requirements.txt`.

---

## 📁 Project Structure (planned)

```bash
jfk-airport-web-scraping/
│
├── README.md                  # Project overview (this file)
├── requirements.txt           # Python dependencies
│
├── src/                       # Python source code
│   ├── scrape_reviews.py      # Web scraping logic for airport reviews
│   ├── load_flights_data.py   # Utilities to load and clean flight data
│   └── merge_and_analyze.py   # Data merging and basic analysis helpers
│
├── data/                      # Raw and processed data (CSV files)
│   ├── jfk_reviews_raw.csv    # Scraped review data (output from scrape_reviews.py)
│   ├── jfk_flights_raw.csv    # Original flight dataset(s)
│   └── jfk_flights_merged.csv # Combined / cleaned dataset
│
└── notebooks/
    └── jfk_analysis.ipynb     # Exploratory analysis & visualizations
