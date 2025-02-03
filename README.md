# Training Neural Networks via Gradient Descent with Backpropagation

This neural network is trained to determine hand-written digits using the MNIST data set.

## Description

This training of this neural network involved the implementation of batch gradient descent with backpropagation to recognize hand-written digits using the MNIST data set with 60,000 training samples and 10,000 test samples. The MNIST data is contained in files:
- trainx.csv: 60,000 pixel images of hand-written digits
- trainy.csv: the actual digits/answers for the data in trainx.csv
- testx.csv: 10,000 pixel images of hand-written digits
- testy.csv: the actual digits/answers for the data in testx.csv

Each 28 × 28 pixel image consists of 784 greyscale pixels, each pixel having a value in the range 0 to 255. The number of neurons in layers 1,2, and 3 are 784, 30, and 10 respectively. This equates to 784 predictor variables per observation with each neuron at the output layer producing a value between 0 and 1 to predict the digit (utilizing the sigmoid activation function) that corresponds with the highest output neuron. The response is the classification of that digit to a value between 0 and 9.

### Dependencies

Necessary libraries:
- pandas
- numpy
- random

Necessary files (included): 
- trainx.csv
- trainy.csv
- testx.csv
- testy.csv

## Acknowledgments

This project was part of an assignment from the course "Industrial Engineering 3013: Optimization for Machine Learning" at the University of Minnesota with Professor England. Part of the code was provided by the professor in the coding language Julia, and I translated it to Python in my implementation. The function descriptions (above each function), parameters, and tuning parameters were provided by the professor. The body of the functions feedforward(), classify(), compute_gradients(), GD(), and BGD() were completed by me. 

