**Student ID: 1080915 & 1079686**

## Overview
* Human pose recognition, and related tasks like gesture recognition and action recognition, are important
tasks for AI systems that interact with people. There are many algorithms for classifying pose;
for example, deep convolutional neural networks can be trained to classify pose directly from images.
However, these methods tend to be “black boxes” and it’s difficult to understand what features they
are using. Another approach, which we will use in this Project, uses neural networks to first identify
keypoints corresponding to the main parts of the body (as shown above), and then learns to recognize
pose based on the positions of these body parts.</br>
* In this project, we implement a supervised na¨ıve Bayes learner to classify pose from keypoints
provided by a deep convolutional neural network. We train, test, and evaluate the classifier
on a provided dataset, and then we use it to answer some conceptual questions about na¨ıve Bayes.

## Instructions:
Run the functions in order:
First import the libraries, then run
preprocess -> train -> gaussian -> predict -> evaluate
At the end, assign the datasets and then implement the functions to get the prediction accuracy
you may change the train and test file to other datasets
There is also a cell of code that allows you to get the output prediction to a csv file called "result.csv"
