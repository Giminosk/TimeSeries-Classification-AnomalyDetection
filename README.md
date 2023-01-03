# TimeSeries-Classification-AnomalyDetection


## Preamble
You were asked for help by a company producing candies. Some of their products are plagued with different types of defects. The whole manufacture is equipped with sensors so there are several time series describing the process of producing candies.
They would like to achieve two goals:
  - Have a predictive model which will tell them if a given candy has a defect and which ones
  - Perform a root cause analysis - they would like to know what patterns in the data are related to defects


## Dataset:
  - 50,000 samples
  - each sample is a time series with 3 lines:
    - each line represents data from one sensor
  - length of each sample is random (of some interval)
  - each sample is classified as array of 5 True/False, e.g [True, False, False, True, False]:
    - each True/False is responsible for occurance of one pattern
    - some patterns can affect many sencors
  - each sample can have zero, one or more defects
