## 1_Initialization_Methods.ipynb

Different initializations lead to different results. A well chosen initialization can: 
* Speed up the convergence of gradient descent
* Increase the odds of gradient descent converging to a lower training (and generalization) error
* be used to break symmetry and make sure different hidden units can learn different things

Here are the initialization methods you will experiment with:
* Zeros initialization -- setting initialization = "zeros" in the input argument.
* Random initialization -- setting initialization = "random" in the input argument. This initializes the weights to large random values.
* He initialization -- setting initialization = "he" in the input argument. This initializes the weights to random values scaled according to a paper by He et al., 2015.
	
