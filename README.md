# ML Journey
Learning machine learning with PyTorch.

## Progress log
- Day 1: tensors, autograd, gradient descent from scratch
  Day 2: nn.Linear, optimizers, first neural network
         work with two Sgd and Adam models that are differente with their maner of optimization: 
         sgd: optimize the step with lr*gradient. A steeper slope gives a bigger step from somewhere we arrive ti inf
         Adam: normalize each step with: 
                                        m = b1*m + (1-b1)g
                                        v = b2*v + (1-b2)g**2
                                        step = lr*m/sqrt(v+e)
        