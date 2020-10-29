# Timeseries_anomaly_detection_using_an_Autoencoder
# 

```
python Tad.py 
```

Description: Detect anomalies in a timeseries using an Autoencoder.

###  Introduction

This script demonstrates how you can use a reconstruction convolutional autoencoder model to detect anomalies in timeseries data. You can view the results of the program run in results.pdf,and the Tad.ipynb can run on jupyter notebook.

### Datasets

We will use the [Numenta Anomaly Benchmark(NAB)] dataset. It provides artifical timeseries data containing labeled anomalous periods of behavior. Data are ordered, timestamped, single-valued metrics.

Procedures needed for the data set has been put into Datasets/ folder, need more data, please refer to https://www.kaggle.com/boltzmannbrain/nab).

### Python requirements 

Currently, the code supports python >=3.6

* tensorflow-cpu(==2.3.0,necessary,if support GPU,for tensorflow-gpu ==2.3)
* numpy (==1.19.2,necessary,which mathces the TensorFlow version) 
* matplotlib
* pandas
* missingno

### Results 

see results.pdf

### Reference 

https://keras.io/examples/timeseries/timeseries_anomaly_detection/#introduction

