# cnn-image classification

## Description

This repository hosts a Convolutional Neural Network (CNN) implemented in Python, using the Keras library, designed to classify images of cats and dogs. The process begins by standardizing all images to a 100x100 pixel size and scaling their RGB values to the range [0, 1]. The model architecture comprises two convolutional layers, each equipped with 32 filters of size 3x3 and employing the Rectified Linear Unit (ReLU) activation function. Additionally, max-pooling layers are utilized for downsampling the input data. Following the convolutional layers, the model features two dense layers: the first with 64 neurons, which produce a vector with 64 elements, and the second (output) layer, which reduces the input to a single value between 0 and 1 using the sigmoid activation function, representing either a cat or a dog.

## Dataset
The dataset used in this CNN can be found here:
https://drive.google.com/drive/u/0/folders/1dZvL1gi5QLwOGrfdn9XEsi4EnXx535bD

## Dependencies

This project requires the following dependencies:
- Python 3.x
- Jupyter Notebook
- Keras
- Tensorflow
- NumPy
- Matplotlib

Install the necessary Python packages using pip
'''bash
pip install keras tensorflow numpy matplotlib
