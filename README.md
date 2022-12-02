Please refer: [My Project Collection](https://github.com/AswinBalamurugan/Machine_Learning_Projects/blob/main/README.md)

# Objective
Prepare the given time series data to apply appropriate time-series models. 

# Dataset
The dataset is available on kaggle - "Store Item Demand Forcasting Challenge".
Link to the website - https://www.kaggle.com/competitions/demand-forecasting-kernels-only/data

## Description of the dataset
The dataset contains the following columns:
* date - Date of the sale data.
* store - Store ID
* item - Item ID
* sales - Number of items sold at a particular store on a particular date. 

# Approach
* To prepare the data for a time-series analysis.
* To use the processed data to train MLP and CNN-LSTM models. 

# Description of models used
* Multi-Layer Perceptron (MLP) <br>
It is a feedforward artificial neural network that generates a set of outputs from a set of inputs. An MLP is characterized by several layers of input nodes connected as a directed graph between the input and output layers. MLP uses backpropogation for training the network. MLP is a deep learning method.

* Convolutional Neural Network (CNN) <br>
It can be thought of as a sequence of layers, in which every layer transforms the input volume of activations to another layer through a differentiable function. Therefore, three main types of layer to build a CNNs architecture can be identified, namely: Convolutional layer, Pooling Layer and Fully-Connected Layer.

* Long Short-Term Memory (LSTM) <br>
It is an artificial neural network used in the fields of artificial intelligence and deep learning. Unlike standard feedforward neural networks, LSTM has feedback connections. The connection weights and biases in the network change once per episode of training, analogous to how physiological changes in synaptic strengths store long-term memories; the activation patterns in the network change once per time-step, analogous to how the moment-to-moment change in electric firing patterns in the brain store short-term memories.

# Links to the three plotly plots (exploratory data analysis) 
* [Sales by Date](https://aswinbalamurugan.github.io/DL_sales_forcast/plots/sales_by_date.html)
* [Store Sales by Date](https://aswinbalamurugan.github.io/DL_sales_forcast/plots/store_sales_by_date.html)
* [Item Sales by Date](https://aswinbalamurugan.github.io/DL_sales_forcast/plots/item_sales_by_date.html)

# Accuracy score of the Models
* MLP
* Train data RMSE : 15.93
* Validation data RMSE : 16.05
* CNN-LSTM
* Train data RMSE : 16.26
* Validation data RMSE : 16.33

# Conclusion
The trained CNN-LSTM model fitted better on the processed dataset. This model can be used to predict the sales of a product in a particular store after some particular days in the future. 
