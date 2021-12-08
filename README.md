# Global_Mart_Sales_Forecast

-GM, an online supergiant store has worldwide operations. Store takes orders and delivers across the globe and deals with all the major product categories — consumer, corporate and home office.
-I am going to forecast the sales of the products for the next 6 months, so that we have a proper estimate and can plan inventory and business processes accordingly.


# Some Findings after Reading the dataset

-The store dataset has the 5 attributes - Order-Date, Segment, Market, Sales, Profit
-The store caters to 7 different geographical market segments - Africa, APAC (Asia Pacific), Canada, EMEA(Middle East), EU (European Union), LATAM (Latin America), US (United States) and 3 major customer segments, i.e. consumer, corporate and home
-Based on these, there are 21 unique "Market-Segments" for which the sales forecasts can be made. 
-So, I am going to Calculate the CoV on the profit for each of the 21 market segments on the train data that will help in finding the most profitable market segment by comparing the 21 CoV values.
-The next part is to forecast using different models - train-test split that takes the 42 months data as the train data and the 6 months data as the test data.
-Following models will be used to do forecasting
Simple exponential smoothing
Holt’s exponential smoothing
Holt-Winters’ exponential smoothing - Additive
Holt-Winters’ exponential smoothing - Multiplicative
AR model
MA model
ARMA model
ARIMA model
SARIMA model
-Model will be choosen according to the MAPE values of each model.
