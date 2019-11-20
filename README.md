# Convolutional_Neural_Network

Convolutional Neural Network implementation and discussion following the [coursera](https://www.coursera.org/learn/convolutional-neural-networks?specialization=deep-learning) course as reference

## Introduction

Convolutional Neural Network (CNN) topics have been grown rapidly in recent years. One of the reasons is the high potential in computer vision area. **Image Classification**, **Object Detection**, **Neural Style Transfer** are examples of hot-topics nowadays that receive high investiment from big companies. The name "convolutional" cames from the convolutional mathematical operation. However, the most appropriate name for the CNN matrix operation is the cross-correlation. In summanry, It is neural networks that use cross-correlation in place of general matrix multiplication.

## Convolutional layers

1 - Conv Filter or kernel (Schar and Sobel filter)
2 - Padding (Valid conv and Same conv)
3 - Strided

Impotant to note that a 6x6x3 image when applied a 3x3x3 filter, it results in a 4x4 matrix.

## Parameters calculation

Suppose you have 10 filters that are 3x3x3 in one layer of a neural network, how many parameters does that layer have?

=> 3x3x3 = 27. The adding the bias => 27+1 = 28. Then multiply by 10 => 280 parametes.

## Pooling layer

1 - Max pooling - Divide the image or matrix in parts and extract the maximum value of that parts. The aim is to detect features from each part and keep it. The max pooling layer does not have parameters.

## Challenges

One of the challenges of computer vision problem is the intput (process images is usually expensive). This is due to the fact that it is necessary a large number of parameters which might result in overfitting.

## Why CNN

1- Parameter sharing
2- Sparsity coonections



