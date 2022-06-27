# Data-Science-Practicum-
The purpose of this project is to see if there is an easier way for organizations to calculate budgets for food and beverage, instead of splitting them out seperately from their current budgeting processed. 

Problem Statement:
 Due to the high level of volatility in the market, especially for food, it is imperative that organizations have more agility and accuracy in their inflation forecasting. Food items are one of the commodities that are broken out when analyzing the consumer price index (CPI) and are extremely volatile. Based off of this information, organizations have to forecast their food pricing separately from the rest of their goods or services which increases the amount of time an organization needs to forecast pricing for their business. To try and reduce this lift, the US CPI averages will be compared to food CPIs to see if there is an easier and faster way to forecast food price based off of the national CPI.

Process:
  Three machine learning models were used to try and predict inflation rates for food and beverage spend using national CPI datasets. This data was then used to forecast spend and compared to actual food and beverage spend.
  
  Conclusion: 
  In conclusion, all three models over estimated the price for food and beverage spend for both datasets. The Prices were about 33-66% higher than the actuals. However, the data did show that market basket CPI data can be used to predict food and beverage data. This can be seen when analyzing the forecasted spend data to the F11 spend dataset. Two of the three models were trained using the market basket CPI data and both of those models came close to what the F11 spend data forecast was. Therefore, for organization to accurately and more robustly forecast their budgets, they should use all of their own historical spend data, no matter the commodity, to train any of the three machine learning models used during this project (KNN, Linear Regression or ARIMA) and they will most likely create a robust enough model to forecast their future budgets. 
  
  For more detailed information - please play the powerpoint slideshow. 
