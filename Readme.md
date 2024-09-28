# Stock Valuation and Sensitivity Analysis for Woolworths Group
## Table of Contents
- [Project Overview](#project-overview)
- [Key Features](#key-features)
- [Data Overview](#data-overview)
- [Key Variables](#key-variables)
- [Methodology](#methodology)
- [Results and Discussion](#results-and-discussion)
- [Insights](#insights)
- [Conclusion](#conlcusion)

### Project Overview
This project evaluates the stock of Woolworths Group Limited using the Dividend Discount Model (DDM) and performs a sensitivity analysis using Monte Carlo simulations. The project aims to explore how different assumptions about the dividend growth rate and discount rate impact the estimated fair value of the stock.

### Key Features:
- Dividend Discount Model (DDM): A widely-used method for estimating the intrinsic value of a stock based on the present value of expected future dividends.
- Monte Carlo Simulations: Used to perform sensitivity analysis by introducing randomness to the growth rate and discount rate to observe different scenarios.
- Historical Data: Includes Woolworths' weekly stock prices and annual dividend data over a 10-year period.

### Data Overview
- Stock Price Data: Weekly stock price data from 1st July 2013 to 30th June 2023 sourced from Bloomberg.
- Dividend Data: Annual dividend data for Woolworths Group from 2013 to 2022.

#### Key Variables:
- LIMIT_BAL: Credit limit or stock value
- Historical Returns: Calculated using the log-return formula:
![image](https://github.com/user-attachments/assets/6115ce8b-38b6-43dd-b6cf-1d1faea507f6)
- Dividend Growth Rate (g):
  ![image](https://github.com/user-attachments/assets/8cd9077b-058f-47dc-a861-dd86299df33e) 
- Discount Rate (r): Calculated based on historical returns.
  
### Methodology
- Data Collection: Historical stock prices and dividends were collected from Bloomberg for a 10-year period.
- Dividend Discount Model (DDM): The DDM estimates the stock price based on projected future dividends discounted back to the present value.
- Monte Carlo Simulations: Performed 500 simulations, varying the dividend growth rate and discount rate randomly to assess the variability in the estimated stock price.
- Growth rates were assumed to follow a normal distribution, and scenarios were generated to explore how these inputs influence the predicted share price.

### Results and Discussion
- Stock Price Prediction: Using DDM and constant discount rates, most projected prices were below the actual stock price of $39.13 per share.
- Monte Carlo Simulations:
  - Introducing randomness in growth and discount rates led to more varied outcomes.
  - Many forecasted prices were below the actual stock price, indicating model limitations, particularly under uncertain conditions.
  - The average historical rate of return estimated was 3.4%, lower than the country's risk-free rate of 4.021%, leading to questions about the accuracy of the discount rate.

### Insights:
- The Dividend Discount Model (DDM) works effectively when the assumptions hold, but when multiple variables are random, results become unpredictable.
- The results showed that the stock price is highly sensitive to changes in the growth rate, with small variations resulting in significant price fluctuations.

### Conclusion
The project highlights the strengths and limitations of using DDM for stock valuation. The sensitivity analysis using Monte Carlo simulations emphasized the model's vulnerability to assumptions, especially the discount rate and dividend growth rate. Given the volatility in real-world markets, these results underline the importance of using caution when applying DDM for long-term stock valuation.
