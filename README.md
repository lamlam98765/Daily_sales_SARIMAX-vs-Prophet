# Forecasting daily sales/ SARIMAX vs Prophet


Data is from Kaggle competition <a href="https://www.kaggle.com/competitions/store-sales-time-series-forecasting/data">Store Sales - Time Series Forecasting</a>. You can also visit my workbook <a href="https://www.kaggle.com/code/thilananhnguyn/sarimax-beats-prophet-y-all">workbook</a> there.


I try to predict daily sales for the thousands of product families sold at Favorita stores located in Ecuador. The dataset in from Kaggle and contains six dataframes:

 - The training data, comprising time series of features store number, family, and onpromotion as well as the target sales.
- The test data, having the same features as the training data. You will predict the target sales for the dates in this file.
- Store metadata, including city, state, type, and cluster.
- Daily oil price. Includes values during both the train and test data timeframes. (Ecuador is an oil-dependent country and it's economical health is highly vulnerable to shocks in oil prices.)
- Holidays and Events, with metadata

## Result: 

<img width="1011" alt="image" src="https://github.com/lamlam98765/Daily_sales_SARIMAX-vs-Prophet/assets/92735387/b5f5caf5-aba2-4089-a3c1-4eaab3f4c672">

## Insights:

SARIMAX model performs better than Prophet model, proving that with time series done carefully it's worth it. 

In this case SARIMAX and Prophet perform well I don't have any issue, but we can also try LSTM too.
