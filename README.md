# Tesla and GameStop Stock & Revenue Analysis

A Python project that collects, cleans, and visualizes historical share prices and quarterly revenue for Tesla and GameStop.

Completed as a guided assignment for **Python Project for Data Science**, part of the **IBM Data Analyst Professional Certificate** on Coursera.

## Project Objective

Practice collecting financial data from different sources, preparing it for analysis, and presenting stock price and revenue trends through clear visualizations.

## Tools and Libraries

| Tool | Purpose |
|---|---|
| Python | Data collection and analysis |
| yfinance | Retrieve historical stock prices |
| Requests | Download revenue webpages |
| BeautifulSoup | Extract data from HTML tables |
| Pandas | Organize and clean datasets |
| Matplotlib | Create stock price and revenue charts |
| Jupyter Notebook | Present code, outputs, and explanations |

## Project Workflow

1. Retrieve Tesla (`TSLA`) historical stock data using yfinance.
2. Extract Tesla quarterly revenue from an IBM-provided webpage.
3. Retrieve GameStop (`GME`) historical stock data.
4. Extract GameStop quarterly revenue from a separate webpage.
5. Clean revenue values by removing currency symbols, commas, and missing or empty entries.
6. Create charts showing historical share prices and quarterly revenue for each company.

## Visualizations

The notebook uses a reusable `make_graph()` function to create two vertically arranged charts for each company:

- Historical closing share price in US dollars.
- Historical quarterly revenue in millions of US dollars.

The plotting function uses Matplotlib to produce static charts that can be viewed in the saved notebook.

## View the Notebook

[Open the completed notebook](<Revenue Data and Building a Dashboard (2).ipynb>)

## How to Run

Install the required libraries:

```bash
pip install yfinance pandas requests beautifulsoup4 matplotlib jupyter
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open the project notebook and run the cells from top to bottom.

An internet connection is required to retrieve stock data and download the revenue webpages.

## Data Sources and Limitations

- Historical stock prices are retrieved through yfinance.
- Revenue data comes from historical webpages provided by IBM Skills Network.
- The graphing function includes stock records through June 14, 2021, and revenue records through April 30, 2021.
- Available revenue records may end before the plotting cutoff.
- Downloaded stock prices may change between runs because of data updates or historical adjustments.
- The charts describe historical trends; they do not establish causation or predict future performance.

## Skills Demonstrated

- Retrieving data using a Python library.
- Scraping HTML tables with BeautifulSoup.
- Cleaning and organizing Pandas DataFrames.
- Inspecting extracted records.
- Creating reusable visualization functions.
- Combining code, tables, and charts in a notebook.

## Acknowledgements

The assignment template and revenue source pages were provided by IBM Skills Network through Coursera. This repository contains my completed coursework.

## Author

**Siti Fadilah**

Aspiring Data Analyst with a background in Engineering Business.
