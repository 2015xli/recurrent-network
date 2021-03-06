## A simple tutorial on recurrent network in Python

It has a stochastic gradient descent algorithm. The recurrent network supports both external recurrence and internal recurrence. 
 - The external recurrence happens when forwarding more than one sample consecutively before back-propagation and parameters update. The times of external recurrence are decided by the input data.
 - The internal recurrence happens within a sample's forwarding, which can be considered as external recurrence but reusing a same sample. The times of internal recurrence are specified in argument. 

Without any extra control, the vanilla RNN implementation is sensitive to parameter set size, initial values and learning rate.

An example for MNIST is given that gets >97% accuracy with much smaller set of parameters. The MNIST case uses RNN in a way that, it splits one digit image data into equal-length pieces, and feeds the pieces into the network one by one recurrently, then outputs the recognization result with a softmax layer. 

Another example for sequence prediction is given too. This example uses a sequence of 30 consecutive nosiy sine values (real numbers) to predict the following sine value(s) in the sequence. The 30 samples are generated by sine function with noise added.

