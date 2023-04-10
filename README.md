# POC-LSTM-sigmoid-labelling
Proof of concept for signal labelling using a Pytorch LSTM with added multiattention and walkforward validation

(1) avoids the trap of overfitting models to noise 
(2) takes into account the sequential dimension of time series data
(3) allows us to get an accurate view about how various models would have performed in the past given the information we would have had at that time.
