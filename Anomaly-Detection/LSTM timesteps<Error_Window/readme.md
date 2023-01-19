Workflow:

* generate error pattern with various Delta(width) & H(amplitude)
* create array of errors
* import base dataset
* create a new dataset by injecting error into base dataset
* feed the new dataset into LSTM algorithm & 
* see the anomay detection response

LSTM window = 60 datapoints,
Error window = 200 datapoints
