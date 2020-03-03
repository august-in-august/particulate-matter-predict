# particulate-matter-predict

To compare several deep learning methods by comparing the predicted resutls in several areas in Seoul

There are five models are compared

* CNN(Convolutional neural network) model
* LSTM(Long short term neural network) model
* GRU(Gated recurrent neural network) model
* ConvNet+GRU model
* ConvNet+LSTM model

## source code:

* data_visualization.ipynb  Preview the columns of collected data
* LSTM.ipynb  Example of one predicting model 
* Model Comparison.ipynb  of all trained models

For more descriptiion, please check the [paper](https://github.com/timfree/particulate-matter-predict/blob/master/%E1%84%86%E1%85%B5%E1%84%89%E1%85%A6%E1%84%86%E1%85%A5%E1%86%AB%E1%84%8C%E1%85%B5%20%E1%84%8B%E1%85%A8%E1%84%8E%E1%85%B3%E1%86%A8%E1%84%86%E1%85%A9%E1%84%83%E1%85%A6%E1%86%AF%20%E1%84%87%E1%85%B5%E1%84%80%E1%85%AD.pdf)

models are running on jupyter notebook 2.0 and written in python language

## necessary libraries 

h5py == 2.10.0    
jupyterlab == 1.2.4     
Keras == 2.3.1     
matplotlib == 3.1.3     
numpy == 1.17.4    
pandas == 0.25.3    
scikit-learn == 0.22.1    
scipy == 1.4.1     
tensorflow == 2.1.0     
