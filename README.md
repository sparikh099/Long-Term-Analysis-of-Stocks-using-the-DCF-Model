# Intrinisic Value Calculator
## Purpose of Project
The goal of this project was to develop a fair value to buy a stock at. To model the stock price, I discounted cash flows and forecasted the cash flows based on regression techniques. I used an R-squared value to determine what regression value would be best used to predict the future cash flows. The intrinsic value of a stock can tell whether or not a stock is overvalued or undervalued. If a stock is overvalued, it is not a buy, if it is undervalued, it is a buy.
## Main Steps in Project
The first major step in this project was collecting the data. I collected the data from yahoo finance and retained all of the cash flow statements. 

After I gained access to the cash flow statements, I used the free cash flow for my predictions. To forecast future cash flows, I took the numbers from the previous cash flows and developed various regression models such as linear regression, polynomial regression, decision tree regression, random forest regression, and support vector regression. To analyze which regression model to use to forecast the cash flows, I analyzed the R-squared value as an indicator. Based on the model with the highest R-squared value, I adjusted the intrinsic value based on the future cash flows on that specific regression model.

Finally, based on the DCF model, I would finally compute my own intrinsic value of various stocks. 


