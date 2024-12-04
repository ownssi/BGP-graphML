## Potential models we can use:
1. LSTM to predict and detect anomalies
2. Random Forest to classify data points

## Docker command
docker run -d -p (Port number you want to use):8888 khoarau/bml 

ex: docker run -d -p 8989:8888 khoarau/bml will allow you to access to jupyter notebook through http://localhost:8989/. If the jupyter prompts you to enter password, "bml" is password



## Data path

Each dataset's folder/anomaly OR no_anomaly/Each dataset's name/transform/Features
The one ends with 1 is one min interval and 3 is three min interval
