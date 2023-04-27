# Curve-Fitting-and-Model-Representation
Implement the model  𝑓𝑤,𝑏 for linear regression with one variable.
We will use the motivating example of housing price prediction.
We will use a simple data set with only two data points - a house with 1000 square feet(sqft) sold for $300,000 and a house with 2000 square feet sold for $500,000. These two points will constitute our data or training set. The units of size are 1000 sqft and the units of price are $1000's of dollars.
You would like to fit a linear regression model through these two points, so you can then predict price for other houses - say, a house with 1200 sqft.
Linear regression builds a model which establishes a relationship between features and targets
In the example above, the feature was house size and the target was house price
for simple linear regression, the model has two parameters  𝑤 and  𝑏 whose values are 'fit' using training data.
once a model's parameters have been determined, the model can be used to make predictions on novel data.

Notations:
x               Training Example feature values (in this code - Size (1000 sqft))	                              x_train
y               Training Example targets (in this code - Price (1000s of dollars)).)	                          y_train
𝑥(𝑖) ,  𝑦(𝑖)                               𝑖𝑡ℎ  Training Example	                                                x_i, y_i
m                                     Number of training examples                                                 m
𝑤                                              parameter: weight                                                  w
𝑏                                              parameter: bias                                                     b
𝑓𝑤,𝑏(𝑥(𝑖))      	The result of the model evaluation at  𝑥(𝑖) parameterized by  𝑤,𝑏:  𝑓𝑤,𝑏(𝑥(𝑖))=𝑤𝑥(𝑖)+𝑏          	f_wb
 

