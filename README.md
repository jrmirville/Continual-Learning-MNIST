# Continual-Learning-MNIST
Project 1- Continual Learning
In this project I will be utilizing the MNIST dataset.

# Pre-requisites
torch, keras, matplot, numpy, pandas, tensorflow, sklearn

# Contents
MNIST digits classification with intital and then rotated data with a Keras Convolutional Neural Network.

# How to use
Download the repository from Github to a folder on your disk
If using Google Colab, upload all the notebooks (*.ipynb) and Python modules (*.py) files to your Google Drive to a folder called Colab Notebooks
If using offline: start IPython Notebook and browse to folder where you downloaded these notebooks and use as usual. 

# Observation
While Working on this project, I had trouble finding ways to demonstrate continual learning on the MNIST dataset. I saw many examples of Convolutional Neural Networks and I decided to utilize that. I used multiple resources to work on this project. I utilized helper functions to display and plot graphs. I also utilized different example code to create and utilize the model, and also augment the MNIST dataset. 

During my first attempt, I used the standard MNIST dataset to test the accuracy of the model. Once I completed that and saw that it was pretty accurate I then looked at ways to augment the MNIST. I saw examples of rotation, shift, shear, and zoom. I chose rotation based off of the examples listed in the project. The model was still pretty accurate but suffered from overfitting as shown in the graph.

This project can definately be improved and will also tested with the other augmentation of MNIST.
