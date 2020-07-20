# Predicting a defaulter on a credit loan

Knowing if someone would default on a credit loan is very important for banks, credit institutions to know before they lend credit to an individual. The accompanied notebook in
this repository shows one way of predicting if someone would default on a loan. I will be performing a binary classification by predicting a credit defaulter using age, sex, marital status, education, history of past payment, amount of bill statement, 
and past payment. This kind of model is useful for banks and credit card companies to determine if a person is likely to default on a bill/loan. 
We will be using feed-forward neural networks here.

Here are some of the steps followed:
# Exploring the data: 
some initial analysis to get familiar with the data
# Feature Engineering: 
Here we try to prepare the data by transforming it into tensors so that neural network model can understand it
# Model Building: 
Split data into training and validation dataset. Use 3 hidden layers in our feedforward neural network model. We will use some regularization in the form of batch 
normalization and dropout to reduce overfitting.
# Model Performance Evaluation: 
Use loss and accuracy to see how the model has performed on the validation dataset.
# Prediction: 
Using the model to predict on the validation dataset. This can be used for new data.

Some more data was needed for a better accuracy which currently stands at 78%.

For more information check this blog: https://medium.com/swlh/how-to-predict-if-someone-would-default-on-their-credit-payment-using-deep-learning-49ee032a8a31


