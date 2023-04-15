# Stock Data Analysis with Technical Indicators

This is a simple Python web application built with Streamlit that allows users to download and analyze stock data for a selected ticker from the S&P 500 index. The app also applies technical analysis indicators such as Simple Moving Average, Exponential Moving Average, and Relative Strength Index to the data and displays the results in a chart and table format.

## Instruction to Run the App:
### Install the required Python libraries by running the following command in your terminal or command prompt:
```pip install streamlit pandas yfinance talib```

### Note: You may need to install additional dependencies for TA-Lib depending on your system.

### Run the following command:
```streamlit run stock_data_analysis.py```

### Wait for the app to start running and then use the select boxes on the left sidebar to choose a stock ticker, select a start and end date, and choose a technical analysis indicator to apply to the data.

### The app will download the data from Yahoo Finance, apply the selected indicator, and display the results in a chart and table format on the right side of the app.

### Note: This app requires an active internet connection to download the stock data from Yahoo Finance and Wikipedia. TA-Lib library must also be installed properly for the technical indicators to work. You can find instructions on how to install TA-Lib [here](https://mrjbq7.github.io/ta-lib/install.html" target="_new)




