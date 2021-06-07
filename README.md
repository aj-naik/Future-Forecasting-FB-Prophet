# Future-Forecasting-FB-Prophet
 Predicting Future Product Prices Using Facebook Prophet.  

 FB Prophet is a library developed by Facebook for use on time series data. Compared to normal methods of handling Time Series data, FB Prophet is very easy and efficient method of time series forecasting.

 # Project Description
(I followed Ryan Ahmed's brilliant tutorial for this project. Check out his tutorials and guided projects on various platforms)
The problem statement is forecasting the prices of avocado in general and in a specific region given historic data.

# Flow of Project:
- Loaded data and checked for any null values
- Performed EDA by plotting various features to get more sense of data. Generated following plots:
1. Date and Average Price to see fluctuations in prices
2. Distplot of Average Price to check variations in prices.
3. Violin plot of the average price vs. avocado type to see which types of avocado command a higher market value.
4. Bar Chart to indicate the number of regions where avocado is sold.
5. Another Bar Chart to indicate the count of sales in every year.
6. Catplots of avocado prices vs. regions for conventional and organic avocados to get a sense of which regions consume which type of avocados more.
- After EDA, modelled a sample of data using FB Prophet to predict the price of avocados over a period of 1 year in general over all regions as well as over specific regions and generated plots of the predictions.
- Also generated plot of yearly trend of prices which is made easy because of Prophet.
