# Future-Forecasting-FB-Prophet
 Predicting Future Product Prices Using Facebook Prophet.  

 FB Prophet is a library developed by Facebook for use on time series data. Compared to normal methods of handling Time Series data, FB Prophet is very easy and efficient method of time series forecasting.

 # Project Description
(I followed Ryan Ahmed's brilliant tutorial for this project. Check out his tutorials and guided projects on various platforms)
The problem statement is forecasting the prices of avocado in general and in a specific region given historic data.

# Flow of Project:
1. Loaded data and checked for any null values
2. Performed EDA by plotting various features to get more sense of data. Generated following plots:
- Date and Average Price to see fluctuations in prices
- Distplot of Average Price to check variations in prices.
- Violin plot of the average price vs. avocado type to see which types of avocado command a higher market value.
- Bar Chart to indicate the number of regions where avocado is sold.
- Another Bar Chart to indicate the count of sales in every year.
- Catplots of avocado prices vs. regions for conventional and organic avocados to get a sense of which regions consume which type of avocados more.
3. After EDA, modelled a sample of data using FB Prophet to predict the price of avocados over a period of 1 year in general over all regions as well as over specific regions and generated plots of the predictions.
4. Also generated plot of yearly trend of prices which is made easy because of Prophet.
