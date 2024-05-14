MNIST Handwritten Digits Classification with TensorFlow

This repository contains code for training a deep learning model to classify handwritten digits from the MNIST dataset using TensorFlow and Keras.
The model architecture consists of a simple fully connected neural network with two hidden layers. The training script mnist_classification.py loads
the MNIST dataset, preprocesses the images by scaling pixel values, builds the neural network model, compiles it with the Adam optimizer and sparse 
categorical crossentropy loss function, and then trains the model on the training data. The training process is visualized using Matplotlib, showing
the training and validation loss as well as accuracy over epochs. After training, the model's performance is evaluated on the test set, achieving an 
accuracy of approximately [insert accuracy score here]. Additionally, the repository includes code for making predictions on individual images from 
the test set and visualizing the results. Feel free to explore the code and adapt it for your own projects!
