## monte_carlo_forecast

# Financial Planning with APIs and Simulations

In this Challenge, you’ll create two financial analysis tools by using a single Jupyter notebook:

Part 1: A financial planner for emergencies. The members will be able to use this tool to visualize their current savings. The members can then determine if they have enough reserves for an emergency fund.

Part 2: A financial planner for retirement. This tool will forecast the performance of their retirement portfolio in 30 years. To do this, the tool will make an Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulations.

You’ll use the information from the Monte Carlo simulation to answer questions about the portfolio in your Jupyter notebook.

# Business Needs
Building a tool to help users evaluate their financial health

# User Requirements
1. Be able to access monthly budgets
    a. Visualize savings
    b. Determin if there are enough reserves for an emergency fund
2. Forecast a reasonably effective retirement plan based on current portfolio holdings and 'random walk' Monte Carlo Simulations
    a. Forecast 30 years forward
    b. Use historical price data and random walk probablities

# Assumptions
1. The average monthly household income = $12,000
2. Each portfolio consists of Cryptocurrency, Stocks, and Bonds
