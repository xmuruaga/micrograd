# micrograd
Implementation of Andrej Karpathy's micrograd

micrograd is a minimalistic autograd engine that implements backpropagation (reverse-mode autodiff) over a dynamically built Directed Acyclic Graph (DAG) and a small neural networks library on top of it with a PyTorch-like API.
Despite its simplicity, with about 100 and 50 lines of code for the DAG and neural network library respectively, it's capable of building entire deep neural nets for binary classification, as demonstrated in the demo notebook.
This project might be particularly useful for educational purposes, providing insight into the inner workings of neural networks and backpropagation.



Modeling one Neuron:

![neuron_model](https://github.com/xmuruaga/micrograd/assets/17816550/a4744168-c389-4ea9-8e68-9c8cfd1973f9)

Neural Network architecture:

![neural_net2](https://github.com/xmuruaga/micrograd/assets/17816550/aea2def0-054e-4137-bd97-69bf58c535ae)
