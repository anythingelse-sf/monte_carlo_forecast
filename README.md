## monte_carlo_forecast

# Financial Planning with APIs and Simulations

Two part financial analysis tools by using a single Jupyter notebook:

Part 1: A financial planner to visualize current savings as a percentage of the portfolio. The user can then determine if they have enough reserves for an emergency fund or another investment.

Part 2: A Monte Varlow financial planner for retirement funds. This tool will forecast the performance of their retirement portfolio in 30 years. To do this, the tool will make an Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulations.

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
2. Each portfolio consists of select cryptocurrency, Stocks repesented by 'SPY', and Bonds represented by 'AGG'
