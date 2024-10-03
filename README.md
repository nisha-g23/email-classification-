# email-classification-
One major area in machine learning is supervised learning, where the goal is to predict an output given some inputs. The output value may be a numerical or categorical variable. In this article, we will discuss logistic regression: a supervised learning algorithm that can be used to classify data into categories, or classes, by predicting the probability that an observation falls into a particular class based on its features.

Though it can be extended to more than two categories, logistic regression is often used for binary classification, i.e. determining which of two groups a data point belongs to, or whether an event will occur or not. 

The typical setup for logistic regression is as follows: there is an outcome 
y
y that falls into one of two categories (say 0 or 1), and the following equation is used to estimate the probability that 
y
y belongs to a particular category given inputs 
X
=
(
x
1
,
x
2
,
.
.
.
,
x
k
)
X=(x 
1
​
 ,x 
2
​
 ,...,x 
k
​
 ):
P
(
y
=
1
∣
X
)
=
**sigmoid**

P(y=1∣X)=sigmoid(z)=1/1+e^-z 

​
 
​
 
