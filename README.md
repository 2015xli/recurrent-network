## A simple tutorial on recurrent network in Python

It has a single-sample-based stochastic gradient descent algorithm. The recurrent network supports both external recurrence and internal recurrence. The external recurrence happens when forwarding more than one sample consecutively before back-propagation and parameters update. The internal recurrence happens within a sample's forwarding, which can be considered as external recurrence but reusing a same sample.  

An example for MNIST is given, with >97% accuracy.
