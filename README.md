# Stock Ratio Tracker

This project enhances the existing real-time stock data visualization by providing traders with additional insights. The application allows traders to track the **ratio between two stocks** over time, along with their historical correlation. It also displays **upper and lower bounds** to help traders identify trading opportunities when these thresholds are crossed.

## Features

- **Track Stock Ratios**: Instead of showing individual stock prices, this application tracks the ratio between two stocks over time.
- **Historical Correlation**: Monitor the ratio of two stocks against their historical correlation with clearly marked upper and lower bounds.
- **Real-Time Updates**: Continuously updating line graph with automatic updates from the server.
- **Threshold Alerts**: Visual indicators show when the stock ratio crosses the upper or lower bounds, signaling potential trading opportunities.

## Installation

Step 1: Install Dependencies - npm install

Step 2: Run the Python server from the root of the project repository - python datafeed/server3.py

Step 3: Start the Client - npm start

## Objective

- Stock Ratio Tracking: The application calculates and plots the ratio between two stocks over time on a line graph.
- Historical Correlation Bounds: The graph plots upper and lower bounds based on the historical correlation of the two stocks, helping traders identify anomalies or potential trading opportunities.
- Real-Time Updates: The graph continuously updates as new data is received from the server.
- Threshold Alerts: If the stock ratio crosses the upper or lower bound, it is highlighted visually, signaling a possible trading event.

![Screenshot 2024-09-04 at 01 08 39](https://github.com/user-attachments/assets/0012b104-22f5-44c0-8e12-b42731a18fb2)


## Licenses
This project is licensed as task 3 of JPMC's Forage program.
