Library used:
1.) Tkinter library
    -Tkinter is the standard GUI library for Python. Python when combined with Tkinter provides a fast and easy way to create GUI applications.
2.) Keras
    -Keras is an open-source software library that provides a Python interface for artificial neural networks. 



Implement a handwritten digit recognition app using MNIST dataset
Use Deep neural network that is Convolutional Neural Networks
Build GUI in which you can draw the digit and recognize it straight away

The MNIST dataset contains 60,000 training images of handwritten digits from zero to nine and 10,000 images for testing.

First, we are going to import all the modules that we are going to need for training our model

Create our CNN model in Python data science project. A CNN model generally consists of convolutional and pooling layers. It works better for data that are represented as grid structures, this is the reason why CNN works well for image classification problems. The dropout layer is used to deactivate some of the neurons and while training, it reduces offer fitting of the model. We will then compile the model with the Adadelta optimizer.

Now for the GUI, we have created a new file in which we build an interactive window to draw digits on canvas and with a button, we can recognize the digit. The Tkinter library comes in the Python standard library. We have created a function predict_digit() that takes the image as input and then uses the trained model to predict the digit.