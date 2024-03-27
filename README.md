# stock-change-prediction
Use an LSTM-based model to determine whether the S&P 500 stock price movement will be positive the next day. 
Training data: 1989-2018
Testing data: 2018-2021

## Documentation:
4 feature engineering techniques were explored before the implementation of the deep learning model: transformation, extraction, interaction, and mapping. 
```
DL_featurengineering.ipynb
```
Some of these features were used to implement an LSTM model.
```
stock_movement_prediction_DL.ipynb
```
The model has an accuracy of 0.547 and an ROC(AUC) score of 0.469.
Additional notes regarding the EDA, model implementation, and model performance can be found embedded in the notebook. 
