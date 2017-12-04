# SparkDev AI Hurricane Trajectory Prediction

In our model, the inputs to the Recurrent Neural Network (RNN) are wind speed, pressure, and aggregated features of direction, distance, and grid identification. The distance and direction values were calculated from the latitude and longitude points given by the Unisys dataset. Our RNN is learning from all these features and it is predicting which grid location the hurricane will be moving to next. 

## Resources 
- [Unisys Weather Data](http://weather.unisys.com/hurricane/atlantic/)
- [A Sparse Recurrent Neural Network for Trajectory Prediction of Atlantic Hurricanes](https://www.researchgate.net/publication/305685761_A_Sparse_Recurrent_Neural_Network_for_Trajectory_Prediction_of_Atlantic_Hurricanes)

## Tools
- [Python 3.6](python.org/downloads)
- [Keras](https://keras.io/models/model/)
- [TensorFlow](tensorflow.org)
- [NumPy](numpy.org) 
