# RNN-LSTM
This is a working demo of RNN LSTM using individual numbers in sequence as input numbers and predicting the next number in the sequence

Input is array of size (100,5,1) - 100 sequences of 5 vectors size 1X1. eg. [1],[2],[3],[4],[5] output is expected to be [6].

For this we train keras model Sequential() to run the RNN. 
Add LSTM layer to the model. Train the model on train data and test it on test Data.
initially the epochs are kept at 50. Then to 100 then to 400.

Additional LSTM layer is added after the first LSTM layer to improve performance.

Mean Squared error of 0.008 % is achieved.
