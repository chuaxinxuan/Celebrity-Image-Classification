# Celebrity-Image-Classification

## Overview
The assignment involves building an algorithm using only variants of logistic regression models (e.g. regularization, feature engineering) to classify whether a celebrity image is a Male or Female. We also investigated on the following tasks below to determine how different training data affects the performance of the algorithm.

1. How does the accuracy (ie. tested on the last 5,000 images) depend on the size of the training set? Is it necessary to use all the training set, or does the accuracy stabilize before?
2. How does the accuracy depend on the resolution of the input image?
3. Is it necessary to use colored images (or black & white images are enough)? Is it helpful to increase the contrast of the images? Other preprocessing ideas?
4. What if one only uses the area around the eyes? Around the mouth? The hair? The ears? Etc..
5. Is it useful to use an ensemble of models (eg. for example, you can use a different model for each part of the face, and then try to find a way to ensemble these models)?
6. Report the error rate and AUC of your best model (when evaluated on the last 5,000 images)
7. Suppose now that you can only use 1% of the data, i.e. only the first 200 images, to train your model. What is the best model you can come up with? Is it helpful to use data-augmentation strategies? Is it helpful to use regularization strategies? Ensembling? Report the error rate and AUC of your best model (when evaluated on the last 5,000 images).

<hr \>

## Summary of Jupyter notebooks
1. **assignment1_file_1.ipynb**
    * Naive Gradient Descent with Automatic Step Size Selection (Black & White images)
    * Stochastic Gradient Descent (Black & White images)
    * Task 1: Impact of Different Training Sizes
    * Task 4: Model trained on specific features: Eyes, Front Face
    * Task 6: Best Model - Model trained on Front Face


2. **assignment1_file_2.ipynb**
    * Task 3: Model trained on coloured images
    * Task 4: Model trained on specific features: Mouth, Nose
    * Task 5: Ensemble of the models on specific features
    * Task 6: Best Model - Stochastic Gradient Descent on RGB, original sized images with contrast intensity = 1.9


3. **assignment1_file_3.ipynb**
    * Naive Gradient Descent with Fixed Step Size (Black & White images)
    * Task 2: Effect of Resolution of images on test accuracy
    * Task 7: Training on 1% of the data

<hr \>

## Contributions
| Jupyter Notebooks | Contributors |
|-------------------|--------------|
|assignment1_file_1.ipynb|Xin Xuan, Jie Yi|
|assignment1_file_2.ipynb|Joey, Jie Yi|
|assignment1_file_3.ipynb|Su Ning|

<hr \>

## Members
* [Chua Xin Xuan](https://github.com/chuaxinxuan)
* [Tan Jie Yi](https://github.com/jieyitann)
* [Quek Su Ning](https://github.com/suning19)
* [Joey Tan Xin Yi](https://github.com/joeytxy)