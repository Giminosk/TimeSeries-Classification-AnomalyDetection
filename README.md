# TimeSeries-Classification-AnomalyDetection

## Data:
  - 50,000 samples
  - each sample is a time series with 3 lines:
    - each line represents data from one sensor
  - length of each sample is random (of some interval)
  - each sample is classified as array of 5 True/False, e.g [True, False, False, True, False]:
    - each True/False is responsible for occurance of one pattern
    - some patterns can affect many sencors
  - each sample can have zero, one or more defects

## Models used:
  - for classification Recurrent Neural Network (`RNN`) was used
  - for anomaly detection `Autoencoder` consisted of `RNNs` was used 

## Files structure:
  - `data` is folder with samples and labels
  - `models` is folder with saved models in .h5 format
  - `data_generation` is notebook with generating data
  - `analyzing` is main notebook
