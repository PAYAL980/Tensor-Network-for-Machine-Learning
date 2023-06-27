# Tensor-Network-for-Machine-Learning

This model is based on the Google X paper[1] 'Tensor Networks for Machine Learning' by Jack Hidary et al. The model is created using TensorFlow and the TensorNetwork library of Python. Explanatory.ipynb contains the pictorial representation and explains the process used to create the model. Final model.ipynb contains a classifier model for MNIST dataset with just 6310 parameters.
The key to these much fewer parameters is that the traditional 'dense' layer of neural networks is replaced with an MPS (Matrix Product State). To know more about the approach, refer to [1].

[1] Richik Sengupta, Soumik Adhikary, Ivan Oseledets, and Jacob Biamonte. Tensor networks in machine learning, 2022.
