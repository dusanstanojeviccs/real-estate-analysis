# Real Estate Analysis

A simple repository showing the use of a neural network for a regression task. 

The dataset being analysed is located at https://archive.ics.uci.edu/ml/machine-learning-databases/housing/housing.data.

The framework being used for the machine learning is Keras. 

The model has the following structure:
```
_________________________________________________________________
Layer (type)                 Output Shape              Param #   
=================================================================
dense_1 (Dense)              (None, 20)                280       
_________________________________________________________________
dense_2 (Dense)              (None, 10)                210       
_________________________________________________________________
dense_3 (Dense)              (None, 1)                 11        
=================================================================
Total params: 501
Trainable params: 501
Non-trainable params: 0
```
