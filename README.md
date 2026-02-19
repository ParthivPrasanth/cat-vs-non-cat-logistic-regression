# Logistic Regression from scratch

This project implements a binary image classifier using logistic regression built completely from scratch in NumPy. The model predicts whether a 64×64 RGB image contains a cat or not.

The implementation includes image preprocessing, forward and backward propagation, gradient descent, and prediction without using any machine learning libraries.

## Dataset
The dataset contains labeled cat and non-cat images. 

## Results
The model achieves around 99% training accuracy and 70–75% test accuracy.Because the logistic regression model can only identify linear patterns and also because it is trained on a limited and clean dataset, performance on real-world images may be poor(As seen in the jupyter notebook when the model classified the image of a bus as a cat).We would have to use better models like CNNs for better performance on real world data

## Technologies
Python, NumPy, Matplotlib

## Author
Parthiv Prasanth
