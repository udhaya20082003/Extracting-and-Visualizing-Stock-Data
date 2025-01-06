
# Extracting and Visualizing Stock Data

This project demonstrates how to extract and visualize historical stock and revenue data for Tesla and GameStop using Python. By using various data science libraries and web scraping techniques, we generate visualizations that highlight trends in share prices and revenues.
## Prerequisites

Before running the scripts, ensure you have the following Python libraries installed:
```http
  pip install yfinance bs4 pandas plotly
```

## Project overview

The project is divided into six main tasks:

1. Define Graphing Function: A reusable function to create visualizations for stock and revenue trends.

2. Extract Tesla Stock Data: Use the `yfinance` library to fetch Tesla's stock data.

3. Extract Tesla Revenue Data: Scrape Tesla's quarterly revenue data from the Macrotrends website.

4. Extract GameStop Stock Data: Use the `yfinance` library to fetch GameStop's stock data.

5. Extract GameStop Revenue Data: Scrape GameStop's quarterly revenue data from the Macrotrends website.

6. Visualize Data: Generate comparative graphs of stock prices and revenues for Tesla and GameStop.