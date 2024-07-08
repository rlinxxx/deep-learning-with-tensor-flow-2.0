# Feedforward Neural Network

The Feedforward Neural Network (or simply Artificial Neural Network) is characterized by direction of the flow of information between its layers. The intuition is that the input only goes from left to right, that is why it is called “feedforward”. 

Here, we apply this type of network for classification and for regression.

For classification, we use images as data, which are represented as a matrix of 3 dimensions (height x width x channels). We also apply the concept of different activation functions. For the hidden layers, we use the Rectified Linear Unit (ReLU). For the output layer, since we are dealing with multiclass classification, we use the Softmax function.