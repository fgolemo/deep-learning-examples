This example is here to illustrate a rather simple and shallow feed-forward neural network that is used to calculate posture ratings for an agent with 18 degrees of freedom. Each set of 18 variables constitutes a posture (and an input to the network) and the desired output is a single scalar floating-point value (in the range [0,12]), that rates the comfort of this pose. The calculation for the output is based on a bunch of formulas from (TODO: insert source here from Baptiste). The task of the network is to learn those formulas and predict the scalar based on the 18 inputs.

---
`_rating-robot-positions.ipynb` <- this is the Jupyter notebook that contains the python code to run this experiment

`bb-abc2.csv` <- this is test and training data in CSV format

`model-bb-abc-2.h5` <- this is the weights of the trained model in H5 binary format

`model-bb-abc-2.json` <- this is the machine-readable definition of the model. If you use the model without training it first, this is useful to restore the trained model
