# LSTM for time series forecasting

In this repository I will implement a LSTM architecture for time series forecasting. We used heartbeat records as dataset.
<br/>


## Requirements

Pandas 0.24.2
<br/>
Matplotlib 3.0.3
<br/>
Numpy 1.16.5
<br/>
Keras 2.2.5
<br/>

## Data
The dataset can be found [here](http://www.timeseriesclassification.com/description.php?Dataset=ECG5000).
<br/>
All data used are under /dataset folder in the main repo.
<br/> 
Here is a visualisation of small sample from the used data.
<br/>
<br/>
<p align="center">
  <img src="res/data.png" title="Data visualisation" >
</p>

## Results
With only 2 layers of LSTMs (10 units each) we got a quite good results.
<br/>
<p align="center">
  <img src="res/predictions.png" title="Results" >
</p>
<br/>
The code and the dataset file are availables. 
<br/>
Feel free to contact me for any question.
