# LSTM-Oil
Long Short Term Memory RNN used to predict Brent Oil Prices
This is probably the worst use case of an LSTM: 
  1) This is an absurdly small dataset for an LSTM
  2) Restricted to window forecasting, because I'm comparing its results against traditional window Time Series Methods
  3) Deep Learning implementation on data that has obvious deterministic components (Basically there's no need for a fully black box method)
However, despite these weaknesses, the LSTM decreased MAE and MSE to 8 and 9
