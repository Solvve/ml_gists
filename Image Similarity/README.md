# Image Similarity Network
[![Solvve](https://img.shields.io/badge/made%20in-solvve-blue)](https://solvve.com/)

## Description
Notebook for training siamese networks for image distance/similarity extraction. Training process of 2 types of models  one that take 2 images and return similarity score other that takes 1 image and return its embeddings (image2vec). The goal is to get score 1 if 2 images are similar or embeddings that has Euclidean distance ner 0 for similar images
Reference: https://pyimagesearch.com/2020/11/23/building-image-pairs-for-siamese-networks-with-python/

## Dataset
Dataset contains 7272 pairs of images, 5090 for training. Each pair contains images form on of 100 classes (at the time this readme file was created) from the StopFundingWar project dataset. Half of all pairs it is pairs with images that belong to the same class with label 1, others has different class images and label 0
Examples:
![alt text](https://github.com/Solvve/ml_gists/blob/master/MRI_anomaly_localization/data.png)

## Results
Example of anomaly localization of KNN method
Images:
![alt text](https://github.com/Solvve/ml_gists/blob/master/MRI_anomaly_localization/prediction.png)
Videos:
https://github.com/Solvve/ml_gists/blob/master/MRI_anomaly_localization/prediction_patient1.mp4
https://github.com/Solvve/ml_gists/blob/master/MRI_anomaly_localization/prediction_patient8.mp4
