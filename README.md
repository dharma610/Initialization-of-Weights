# Initialization-of-Weights
In this notebook you can see how results(Accuracy of a neural network model on training as well as test sets) may vary depending upon how we **initialize weight** while training neural network .In this notebook weights are initialized in 3 different way and then found out accuracy on training as well as development set./
**Important Conclusion**
1) Initializing all parameter as zero is meaningless as all layers becomes the same and doesn't make sense.
2)**Random initialization** may be a good idea but in this Notebook we can see large random values initialization is not perhaps the best idea if we consider number of steps it take to minimize the loss function, it is computationally costly to iterate such large number of times.
3) **"he"** type of initialization is quite good considering the number of steps it takes to minimize cost function is very less as compared to large random initialization.

**you can see notebook and can relate to above points mentioned**
