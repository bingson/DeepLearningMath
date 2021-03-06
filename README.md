# Deep Learning Mechanics
<img src='images/final_outline.png' alt='Drawing' style='width: 400pt;'/>

## 1_L-layer Neural Network

In this assignment you will implement all the building blocks necessary for a
neural network of any architecture. By completing this assignment you will
- develop an intuition of the over all structure of a neural network;
- write functions (e.g. forward propagation, backward propagation, logistic loss, etc...) that would help you decompose your code and ease the process of building a neural network;
- initialize/update parameters according to your desired structure;
- experiment with different model architectures and see how each one behaves.


## 2_Initialization_Methods

Different initializations lead to different results. 
By completing this assignment you will learn how to use different initializations to
* speed up the convergence of gradient descent;
* increase the odds of gradient descent converging to a lower training (and generalization) error;
* break symmetry and make sure different hidden units can learn different things.

## 2_Optimization_Methods	

There are many different optimization algorithms you could be using to get you to the minimal cost. 
By completing this assignment you will
* understand the intuition between Adam and RMS prop;
* recognize the importance of mini-batch gradient descent;
* learn the effects of momentum on the overall performance of your model.

## 2_Regularization_Methods

It is very important that you regularize your model properly because it could dramatically improve your results.
By completing this assignment you will
* understand that different regularization methods that could help your model;
* implement dropout and see it work on data;
* recognize that a model without regularization gives you a better accuracy on the training set but nor necessarily on the test set;
* understand that you could use both dropout and regularization on your model.

## 3_Gradient_Checking

You will be implementing gradient checking to make sure that your backpropagation implementation is correct. By completing this assignment you will
* implement gradient checking from scratch;
* understand how to use the difference formula to check your backpropagation implementation;
* recognize that your backpropagation algorithm should give you similar results as the ones you got by computing the difference formula;
* learn how to identify which parameter's gradient was computed incorrectly.


