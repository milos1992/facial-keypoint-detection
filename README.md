# Facial keypoint detection

## Summary
The toppic of this project is Kaggle competition: Facial Keypoints Detection

The idea is to create an algorithm that predicts the locations of keypoints in unlabeled images.
Performance is evaluated on the Kaggle test dataset, where keypoint locations are not publicly available. Predicted keypoints are sent as a CSV file and scored based on root mean square error.
The solution can also be tested on a self-created set of images to visually verify that it can accurately locate keypoints.


Objective:
- Predict keypoint positions on face images
Problem:

- Supervised learning
- Regression
- Root Mean Squared Metrics - evaluation metrics
Data:

CSV format
Features - Face images
Labels - 15 keypoints to detect
7049 trainin examples, 1783 test images, 27124 keypoints to predict
Solving approach:

Train Convolutional Neural Network to detect facial keypoints
Tensorflow framework
