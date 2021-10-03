# US Stock Price Performance Prediction

Group members: Susan (Fan) Wu (fw249), Shuoqi Zhang (sz646), Juyoung Cha (jc3537)

## Question & Project Purpose Summary

Our project goal is to predict the performance of US stocks. Specifically, we will construct prediction models for the minimum, average, and maximum annual stock prices using the financial indicators of the stocks through the years 2014 - 2018. We will further evaluate our models by comparing our model predictions with the actual stock prices.


## Dataset

https://www.kaggle.com/cnic92/200-financial-indicators-of-us-stocks-20142018?select=2018_Financial_Data.csv

The link provides five separate US stocks datasets for each year between 2014 and 2018. Each dataset contains 225 annual financial indicators (i.e. revenue, profit, R&D expenses) of around 4000 different companies. We plan to merge all the datasets into one composed of 225 columns and 22617 rows.
In addition, since our original dataset does not contain any information about the stock prices, we will obtain the stock prices of the corresponding companies between 2014 and 2019 from Python library. We will: 1) use the stock prices between 2014 and 2018 to calculate the minimum, maximum and average annual stock prices to build our prediction model, ii) use the stock prices of the year 2019 to compare with the predicted stock prices of 2019 and evaluate our model.

We can perform regression analysis on this dataset to identify the significant predictors and make predictions. Since our dataset is high-dimensional with 225 columns, we plan to use dimension reduction techniques such as Principal Component Analysis to reduce model complexity, whereby we can prevent overfitting and make more accurate predictions.

Since we have a very comprehensive range of indicators about the stocks, we believe that we can identify meaningful features and construct accurate prediction models of the stock prices.


## Project Value

The financial market is growing more and more complex with an increasing number of large companies and fluctuations. The US stock market is one of the most focused stock markets in the worldwide financial field, as it has substantial global influence on other financial markets including bonds and commodities. Furthermore, the changes of the stock prices of the larger companies significantly impact the stock prices of other medium and small companies. Therefore, investors and stockholders need to pay close attention to the performance of stocks in the US stock market. To maximize their returns in stock tradings, accurate data-driven prediction models are essential for optimum decision-making.

Our analysis is not based on the most recent data, as we are focusing our analysis on the stock market pre-COVID-19. The unprecedented and unpredictable pandemic has had such an overarching and critical impact on the stock market that outweighs the influence of all other variables. Thus, limiting our focus before the beginning of pandemic will allow us to better understand the relationship between the financial variables and the stock prices.

Predicting the stock prices is one of the most actively researched areas in data science. There is more data available than ever today, and our dataset contains a very comprehensive range of financial indicators. Based on the basic knowledge in the field of finance and economics, it is evident that the changes in the stock prices are reflected and can be at least partially explained by them. Our analysis will allow for a better understanding of the relationships between the financial indicators and stock prices, and strongly support our further actions in the financial market.

