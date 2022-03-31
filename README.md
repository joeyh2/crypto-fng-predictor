# LSTM Stock Predictor
Recurrent Neural Networks using Tensorflow

## LSTM Stock Predictor Using Fear and Greed Index vs. Closing Prices

## Which model has a lower loss?

With same window size of 10, the LSTM Stock Predictor Using Closing Prices had a lower loss (.0174) than 
LSTM Stock Predictor Using Fear and Greed Index (.0920)

Closing Prices
![close10_loss](Images/close10_loss.png)

Fear and Greed Index
![fng10_loss](Images/fng10_loss.png)

## Which model tracks the actual values better over time?

LSTM Stock Predictor Using Closing Prices tracks more closely to actual close prices over time. 

Closing Prices
![close10](Images/close10.png)

Fear and Greed Index
![fng10](Images/fng10.png)

## Which window size works best for the model?

Window size 10 works best for LSTM Stock Predictor Using Closing Prices model out of trials with values 1, 5, & 10. 

Window Size 1
![close_1](Images/close_1.png)
![close1_loss](Images/close1_loss.png)

Window Size 5
![close5](Images/close5.png)
![close5_loss](Images/close5_loss.png)

Window Size 10 (same as above)
![close10](Images/close10.png)
![close10_loss](Images/close10_loss.png)

## Takeaway

It appears our RNN model was better able to predict when trained using daily close prices as the only feature. When fed fear and greed index values as the lone feature, it had higher loss and less accurate predictions. 