# Overfitting/Underfitting

## **What's overfitting?**

A: Overfitting refers to a model that models the training data too well. Overfitting happens when a model learns the detail and noise in the training data to the extent that it negatively impacts the performance of the model on new data.



**E: **Overfitting is more likely with nonparametric and nonlinear models that have more flexibility when learning a target function. As such, many nonparametric machine learning algorithms also include parameters or techniques to limit and constrain how much detail the model learns. For example, decision trees are a nonparametric machine learning algorithm that is very flexible and is subject to overfitting training data. This problem can be addressed by pruning a tree after it has learned in order to remove some of the detail it has picked up.

R:[ https://machinelearningmastery.com/overfitting-and-underfitting-with-machine-learning-algorithms](https://machinelearningmastery.com/overfitting-and-underfitting-with-machine-learning-algorithms/)

## Why overfitting happens?

Overfitting occurs when a model is excessively complex, such as having too many [parameters](https://en.wikipedia.org/wiki/Parameter) relative to the number of observations. Or the number of training data is not large enough!

R: [https://en.wikipedia.org/wiki/Overfitting\](https://en.wikipedia.org/wiki/Overfitting)

## How to avoid overfitting?

Early Stopping, Data argumentation\(numbers of parameter is much smaller than the data \), cross-validation,  Regularization\(L1, L2\), Dropout... 

R:  [https://www.quora.com/What-are-ways-to-prevent-over-fitting-your-training-set-data-Is-it-possible-to-test-if-you-have-done-so](https://www.quora.com/What-are-ways-to-prevent-over-fitting-your-training-set-data-Is-it-possible-to-test-if-you-have-done-so)


## What's early stopping?


Early stopping is a form of regularization used to avoid overfitting when training a learner with an iterative method, such as gradient descent.Divide the training data into new_train and validation data.

After each epoch, evaluate the accuracy(error) on the validation data, if the accuracy doesn't improve over N epochs, then we that the accuracy won't increase accuracy. N can be 10, 20,

Early stopping rules provid guidance as to how many iterations can be run before the learner begins to over-fit. 

R: [https://en.wikipedia.org/wiki/Early_stopping](https://en.wikipedia.org/wiki/Early_stopping)

## What's dropout?














