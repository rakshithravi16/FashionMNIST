# FashionMNIST
This repository contains the code for my Fashion MNIST Classification project. In this project, I have implemented different neural network architectures. I have implemented one Fully Connected Neural Network (FCNN) and two different Convolutional Neural Networks (CNN), to classify images of fashion items into 10 different categories.

## Dataset
The Fashion MNIST dataset consists of 60,000 training images and 10,000 testing images, each of size 28x28 pixels. The dataset includes the following fashion item classes:
1. T-shirt/top
2. Trouser
3. Pullover
4. Dress
5. Coat
6. Sandal
7. Shirt
8. Sneaker
9. Bag
10. Ankle Boot

## FCNN Model
The Fully Connected Neural Network (FCNN) model comprises a series of fully connected (dense) layers.
The model has:
1 input layer with input shape 28x28,
2 hidden layers with 300 and 100 neurons, respectively, have ReLU as the activation function,
The last is the output layer with 10 neurons as there are 10 different classes and the activation function chosen is softmax.

## CNN Model
The Convolutional Neural Network (CNN) model is a more advanced approach that uses convolutional and pooling layers to capture image features. This type of model is known to perform well on image classification tasks.

The first CNN model consists of:
1 input layer with input shape 28x28,
1 Conv2D layer with 32 kernels each of size 5x5, stride=1, padding=0 and activation function is ReLU,
1 Pooling layer with stride=2,
1 Flattening layer,
1 dense layer with 100 neurons with activation function ReLU,
Finally output layer with 10 neurons and softmax as the activation function

The second CNN model consists of:
1 input layer with input shape 28x28,
2 Conv2D layers with 32 kernels each of size 3x3, stride=1 and padding=0,
1 Pooling layer with stride=2,
1 Flattening layer,
1 dense layer with 100 neurons and activation function ReLU,
Output layer with 10 neurons with 10 neurons and activation function softmax

# Result
The results of the FCNN and CNN models on the Fashion MNIST dataset are included in the project.
