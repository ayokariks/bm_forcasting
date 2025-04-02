# DEEP LEARNING APPROACH TO FORECASTING THE BALANCING MARKET
Forecasting in the balancing mechanism(BM) market is paramount in building a robust complex
electricity system in Great Britain (GB). With a growing number of players in this market including
distributed generators, aggregators, and battery energy storage systems(BESS), accurate
forecasting enables critical investment planning and optimisation of resources by all industry
participants. This thesis explores the utilisation of machine learning techniques to forecast two
major parts of the BM market, the imbalance volume, and the imbalance prices. The Long-short
term memory(LSTM) deep learning architecture was compared against a baseline linear model to
observe changes in prediction performance. The models used data provided by Elexon the GB
regulator of the BM market to forecast imbalance volumes(MAW) and imbalance
prices(GBP/MWH) per settlement period. The results showed the MAE of the Linear regression
imbalance volume(167.40) and imbalance price(134.93). Linear regression imbalance
volume(167.47) and imbalance price(135.63). XGBoost imbalance volume(284.65) and imbalance
price(141.11). Whilst the LSTM neural network provided an MAE of imbalance volume(156.55)
and imbalance price(58.93). Thus, the LSTM shows the best performance in forecasting(30 mins
ahead) the imbalance volume and the imbalance prices compared to the linear regression. Further
improvement on the scope of this work in the future would include the usage of other Recurrent
neural networks (RNN) techniques such as gated recurrent unit(GRU), benchmarking this with
the LSTM would ensure the best model is deployed.
