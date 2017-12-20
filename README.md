## A simple tutorial on recurrent network in Python

It has a single-sample-based stochastic gradient descent algorithm. The recurrent network supports both external recurrence and internal recurrence. 
 - The external recurrence happens when forwarding more than one sample consecutively before back-propagation and parameters update. The times of external recurrence are decided by the input data.
 - The internal recurrence happens within a sample's forwarding, which can be considered as external recurrence but reusing a same sample. The times of internal recurrence are specified in argument. 

An example for MNIST is given, with >97% accuracy.
