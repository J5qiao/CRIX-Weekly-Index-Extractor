# CRIX-Weekly-Index-Extractor
This project provides a Python-based web scraping tool for extracting historical weekly CRIX (Crypto Index) values from the interactive chart on the Royalton CRIX website, which does not offer direct CSV data download.

# Features
Uses Selenium to automate tooltip reading on the CRIX chart.

Supports manual mouse hover: you control the cursor over the chart, and the script extracts the displayed tooltip values.

Collected data is saved in a raw .csv file for post-cleaning.

# Output
crix_hover_raw_full.csv: A raw file containing tooltip text data including date and index value.

# Getting Started
To run this script, make sure you:

Have Python 3.x installed

Install the required packages: selenium, pandas

Download the appropriate version of ChromeDriver for your Chrome browser and add it to your system PATH
