# Coding a simple ANN

In this simple code fragment, we are aiming at predicting the vector `y = [0,0,1,1]` given the four inputs `X = [0,0,1],[0,1,1],[1,0,1],[1,1,1]`. The network uses a nonlinear sigmoid function. In the beginning, the weights are assigned randomly. Then for 1000 iterations, the output is updated in forwarding propagation, followed by an evaluation of the error and by a back propagation step which updates the weights considering the slope of the evaluated sigmoid at the error output times.

### Install

This project requires **Python 3.5** and you will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

### Run

In a terminal or command window run one of the following commands:

```ipython notebook Simple_ANN.ipynb```  
```jupyter notebook Simple_ANN.ipynb```

This will open the iPython Notebook software and project file in your browser.
