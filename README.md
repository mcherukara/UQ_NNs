# UQ_NNs

### Background
We use Alex Kendall and Yarin Gal's brilliant paper "[What Uncertainties Do We Need in Bayesian Deep Learning for Computer Vision]([url](https://proceedings.neurips.cc/paper/2017/hash/2650d6089a6d640c5e85b2b88265dc2b-Abstract.html))" to simultaneously estimate data and model uncertainties of a simple regression MLP model.

To quantify model uncertainty, we introduce dropout at each layer of the MLP, which we _retain in testing_ unlike conventional use of Dropout for network regularization. 

### Aleatoric (data) and Epistemic (model) uncertainty on training data
![Uncertainty1](images/both_training.png)

### Aleatoric (data) and Epistemic (model) uncertainty on test data
![Uncertainty2](images/both_test.png)

