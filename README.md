# facial-keypoint-detection

Summary
The toppic of this project is Kaggle competition: Facial Keypoints Detection

The idea is to create an algorithm that predicts the locations of keypoints in unlabeled images.
Performance is evaluated on the Kaggle test dataset, where keypoint locations are not publicly available. Predicted keypoints are sent as a CSV file and scored based on root mean square error.
The solution can also be tested on a self-created set of images to visually verify that it can accurately locate keypoints.

Detecting facial keypoint is a challenging problem. Facial features vary from one individual to another. Another diffiulty is caused by image variations, such as image size, 3D pose, imumination etc. Succcesfull facial keypoint detection serves as a base for many practical applications, such as:

tracking faces in video
biometrics
analysing facial expression
detectiog dysmorphic facial signs for medical diagnosis
