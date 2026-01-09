# Neural_Networks_Andrej_Karpathy
In this repo I will be following along Andrej Karpathy's yt videos on neural networks. Link: https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ

1. micrograd_from_scratch.ipynb
   1.1 Write code for fundamentals like derivative, slope, etc.
   1.2 Define class Value and various basic functions like add, mul, pow, radd, exp, tanh, etc. and their gradients that are used for backpropogation.
   1.3 The gradient of a weight x w.r.t. L is dL/dx which basically tells us how L will change with a slight increase in x. We then use chain rule to calculate the gradients of weights and this is the fundamental idea of backpropogation.
   1.4 Gradient descent is just updating the weights in the negative direction of the gradient so as to minimise loss.
   1.5 Use pytorch to define vectors/ tensors of numbers that can be used by deep learning libraries.
   1.6 Define class Neuron using Value class, and build classes Layer and MLP using the previous class(es).
   1.7 Use MLP to make a prediction on data and use gradient descent to update the weights.
