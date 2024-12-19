# 2024-Comparative-Stock-Market-Tool

A Streamlit-based application that allows users to compare the stock performance of two companies. The tool fetches stock market data using Yahoo Finance, visualizes it with various chart types, and leverages OpenAI's GPT-3.5 to provide a detailed comparative performance analysis of the selected stocks.

## Features
- Stock Comparison: Compare two stocks by entering their ticker symbols (e.g., AAL for American Airlines and UAL for United Airlines).
- Chart Visualization: Select from three types of charts (Line, Bar, and Scatter) to visualize stock price movements.
- OpenAI Integration: Generate a comprehensive analysis of the two stock performances, including highlights and a conclusion.

## Example
After selecting two stock tickers, such as AAL (American Airlines) and UAL (United Airlines), and choosing a chart type, you'll see the historical price data visualized. When you click "Comparative Performance", the app will fetch data from OpenAI and provide an insightful comparison of the stock performances, highlighting key trends and differences.

![Screenshot (383)](https://github.com/user-attachments/assets/4e97300f-9c27-4be3-adfa-e632d6fff377)

![Screenshot (384)](https://github.com/user-attachments/assets/efdf286c-4d9d-4f11-a052-2c7b86015cf4)


![Screenshot (385)](https://github.com/user-attachments/assets/7bad505a-9d47-4b06-846a-ac58657df44a)

## Technologies Used
- Streamlit: For creating the interactive web application.
- Yahoo Finance (yfinance): To fetch historical stock market data.
- OpenAI GPT-3.5: For generating the comparative stock analysis.
- Python: The programming language used for the app development.
