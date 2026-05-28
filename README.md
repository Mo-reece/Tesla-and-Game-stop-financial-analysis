# Tesla and GameStop Financial Analysis

Exploratory financial analysis project comparing Tesla (TSLA) and GameStop (GME) stock prices and revenue trends.

## Problem Statement

The goal is to collect stock-price and revenue data, clean it into analysis-ready tables, and create visual comparisons that make financial trends easier to understand.

## Why This Project Matters

This project demonstrates early data analyst skills: acquiring data from APIs and web pages, cleaning tabular data, and using visualizations to communicate trend differences between two public companies.

## Key Features

- Pulls historical stock data with `yfinance`.
- Scrapes quarterly revenue data from Macrotrends pages.
- Cleans date and revenue columns for analysis.
- Creates Plotly visualizations for stock and revenue comparison.

## Tech Stack

- Python
- pandas
- yfinance
- requests and BeautifulSoup
- Plotly
- Jupyter Notebook

## Project Structure

```text
.
├── stock.ipynb
├── requirements.txt
├── LICENSE
└── README.md
```

## Setup

```bash
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook
```

## Usage

Open `stock.ipynb` and run all cells. Because the notebook fetches live financial data and scrapes public web pages, results can change over time and web scraping cells may need selector updates if the source page changes.

## Portfolio Status

This is a learning/practice project and should not be pinned ahead of stronger projects. To make it recruiter-ready, add:

- A final insight section with 3-5 business observations.
- Saved chart screenshots or exported HTML charts.
- Clear data-source limitations.
- A reproducible run date and package versions.

## Future Improvements

- Replace fragile scraping with a more stable data source where possible.
- Add automated checks for empty revenue tables.
- Export visualizations to a `figures/` or `outputs/` folder.
- Compare against broader market benchmarks.

## Author

Maurice Leonard Okurut
