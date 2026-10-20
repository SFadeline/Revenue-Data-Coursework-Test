Tesla and GameStop Stock & Revenue Analysis

A Python notebook that extracts, cleans, and visualizes historical stock prices and quarterly revenue for Tesla and GameStop.

This project was completed as a guided assignment in Python Project for Data Science, part of the IBM Data Analyst Professional Certificate on Coursera.

Project Objective

Practice collecting data from different sources and preparing it for visualization. The notebook brings together stock price history and revenue data to display each company’s performance over time.

Tools and Libraries

Python — programming language

yfinance — historical stock data

Requests — downloading HTML pages

BeautifulSoup — extracting revenue tables from HTML

pandas — organizing and cleaning data

Matplotlib — plotting stock prices and revenue

Jupyter Notebook — running code and presenting results

Project Workflow

Extract Tesla stock data using its ticker symbol, TSLA.

Scrape Tesla quarterly revenue from an IBM-provided webpage.

Extract GameStop stock data using its ticker symbol, GME.

Scrape GameStop quarterly revenue from an IBM-provided webpage.

Remove dollar signs, commas, and missing or empty revenue values.

Create separate stock price and revenue plots for each company.

Notebook

Open the .ipynb file in this repository to view the code, saved tables, and graphs.

How to Run

Install the required libraries:

pip install yfinance pandas requests beautifulsoup4 matplotlib jupyter

Start Jupyter Notebook:

jupyter notebook

Open the project notebook and run the cells from top to bottom. An internet connection is required to download the source data.

Data Sources and Limitations

Stock prices are retrieved through yfinance.

Revenue tables come from historical webpages supplied by IBM Skills Network.

The supplied plotting function limits stock data to June 14, 2021, and revenue data to April 30, 2021.

The revenue sources may end before those plotting cutoffs.

Downloaded stock values may differ between runs because of updates or historical price adjustments.

The plots are descriptive and do not establish what caused changes in stock prices.

What I Practiced

Retrieving data through a Python library.

Scraping HTML tables with BeautifulSoup.

Creating and cleaning pandas DataFrames.

Selecting and inspecting records.

Using a reusable function to visualize data.

Checking that each dataset uses the correct source.

Acknowledgements

The assignment structure, instructions, historical revenue pages, and supplied graphing function were provided by IBM Skills Network through Coursera. This repository documents my completed coursework and learning progress.

Author

Siti Fadilah

Aspiring Data Analyst with a background of Engineering Business.
