# The Udacity Data Science Nanodegree Capstone Project: Dog Breed Classifier

## Table of Contents

1. [Libraries Used](https://github.com/kendricng/udacity-ds-capstone#libraries-used)
2. [Project Motivation](https://github.com/kendricng/udacity-ds-capstone#project-motivation)
3. [Files Used](https://github.com/kendricng/udacity-ds-capstone#files-used)
4. [Summary of Results](https://github.com/kendricng/udacity-ds-capstone#summary-of-results)
5. [Acknowledgments](https://github.com/kendricng/udacity-ds-capstone#acknowledgments)

## Libraries Used

- Open CV and Pillow: process images
- Glob: manage file directories
- Keras: neural network building
- Matplotlib: plots and graphs
- Numpy and Pandas: vector and data processing
- Random: file randomization
- Scikit-learn: more file processing:
- Tqdm: progress bars

## Project Motivation

This project aims to understand more about deeper artificial neural networks such as convolutional neural networks (CNNs) for image recognition and the power of leveraging pre-trained neural networks with transfer learning.

Note that this is the capstone project for the Udacity Data Science Nanodegree Program.

## Files Used

- dog-app.ipynb: Jupyter Notebook that details the steps in building the transfer learning architecture for CNNs 
- extract_bottleneck_features.py: helper functions for extracting features from the pre-trained models Resnet50 and VGG16
- images: images used to test the dog breed classifier algorithm
- LICENSE: MIT license used for this repo
- [Medium article](https://medium.com/@kendricng/improve-image-recognition-models-using-transfer-learning-6cb8ca807b36): a technical explanation of my choice for CNN model architectures

## Summary of Results

We progressed from building a CNN model from scratch with an accuracy of 5% and an average loss of 4.5 to a transfer learning model using Resnet50 on top of a Global Average Pooling layer and other dropout layers with an accuracy of 82% and an average loss of 0.8.

With all the models built with these architectures, they still overfit. I suggest reducing this tendency towards high variance by adding more regularization or dropout methods as well as adding more image training data.

## Acknowledgments

I would like to thank my friends and their pets (dogs and cats) for providing sample pictures to test out the dog breed image classifier.

Other than that, I would like to thank Udacity for pushing me to learn more about convolutional neural networks and Andrew Ng's machine learning course for fundamental concepts such as graphing loss functions and fixing under/overfitting.
