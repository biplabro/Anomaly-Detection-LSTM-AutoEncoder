# Anomaly Detection using LSTM AutoEncoder
<br><br>
* ```LSTM-Demonstration``` folder contains our first iteration just to make sure that the code works & able to find anomalies in an ideal case, i.e. sudden spike in parameter value.
* ```Error-Patterns``` folder contains code for generating three types of error; sine, ramp and square wave. 
* ```Anomaly-Detection``` folder contains LSTM algorithm & datasets required to investigate three types of error trends. Datasets cntain around 8600 data points and at 7300 & 8100 row number, 200 datapoints long error is injected. 
* This algorithm is univariate & considers the "stator_winding" temperature value of the dataset for anomaly detection, since it is one of the most important variable of an electric vehicle system.
* ```LSTM-lightweight``` folder contains lightweight code for the same autoencoder function, with status identification (Normal, Anomaly & Fault) and Finite State Machine for precise reporting of the states of the system. 
