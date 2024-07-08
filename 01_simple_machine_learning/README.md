# Simple Machine Learning

Here, we apply the concepts of Linear Regression and Logistic Regression using TensorFlow. 

A Logistic Regression funtion can be defined as:

\begin{equation}
    p(y = 1 | x) = \sigma (w^T x + b)  = \sigma (\sum_{d=1}^D w_{d} x_{d} + b)
\end{equation}

Where the activation function is simply a sigmoid function.
We also need to optimize a loss function (also called cost function, or objective function). To do so, we use the Binary Cross Entropy (for classification), and the Mean Squared Error (for regression).