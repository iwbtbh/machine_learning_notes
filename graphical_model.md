

### Graphs
src: http://people.cs.ubc.ca/~murphyk/Bayes/bnintro.html
we are interested in directed graph for this section. Directed graph is mostly important in AI and statistics. 
<br>
For Discrete variable - CPD - Directed Model:

<img src="https://github.com/iwbtbh/machine_learning_notes/blob/master/img/1.png" width="500"><br>
The thing to remember here is: ** a node is independent of its non-descendent given its parent(s) ** 
For example, W is independent of C (non-descendent) given S, R(W's parents). Similarly, S is independent of R given C. 

### Bayes Rules
posterior = likelihood * prior / marginal likelihood

### Two Styles 
Bottom up and top down. We can infer about the cause given effect; also, we can get a idea of how cause generate effects. 

### Causation and Correlation
src: http://bayes.cs.ucla.edu/BOOK-2K/causality2-epilogue.pdf

Bayes Net is generative model because it shows how we generate effects from causes. DBN are directed model of 
[stochastic process](https://en.wikipedia.org/wiki/Stochastic_process). Most common DBN(s) are Hidden Markov Model and Linear Dynamics Systems(LDS). Every node in LDS has gaussian distributions. 

### [Instance Based Learning] (https://en.wikipedia.org/wiki/Instance-based_learning)

### Model Hierachy 
Let mb(x) be the markov blanket of x 
Local Markov Property: x is independent with the rest of the world given mb(x) 
Pairwise Markov Property: x is independent with y given the rest of the world 
Global Markov Property: A and B are independent given C that cuts A and B

### Regularization 
src: https://www.quora.com/What-is-regularization-in-machine-learning <br>
When we add too many variables to our model, our model might overfit. When we overfit, our model becomes good and has better predicting power but it learns background noises. To regularize it, there are many options. L0 is the minimizing parameters in the model. 









                  

