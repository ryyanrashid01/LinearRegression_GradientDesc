# Linear Regression Gradient Descent

### Description
We are given a dataset. We need to implement the gradient descent algorithm to estimate (train) the weights of the linear regression model. We have used Python programming language with Jupyter Notebook.

### Requirements
<ol>
<li>Define at least three (3) functions as follows</li>

```
def train_model(X, y, alpha, max_epoch):
       """ Pass four arguments
       Arguments:
             X: input features
             y: responses
             alpha: learning rate
             max_epoch: maximum epochs
       Returns:
             w: estimated weights
             hist_loss: training loss history
       """
```
```
def prediction(w, X):
       """ Pass two arguments
       Arguments:
             w: weights
             X: input features
       Returns:
             yhat: predicted values
       """
```
```
def loss_fn(y, yhat):
       """ Pass two arguments
       Arguments:
             y: responses
             yhat: predicted value
       Returns:
             loss: loss value
       """
```

<li>Display the training loss value for each epoch of the training loop.</li>
<li>Display the estimated weights (after model training).</li>
<li>Display the training loss against epoch graph (after model training).</li>
<li>Evaluate the linear regression model with the estimated weights on the test set and display at least R-squared and mean squared error measures.</li>
</ol>
