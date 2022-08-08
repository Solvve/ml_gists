# Image Similarity Network
[![Solvve](https://img.shields.io/badge/made%20in-solvve-blue)](https://solvve.com/)

## Description
Notebook for training siamese networks for image distance/similarity extraction. Training process of 2 types of models  one that take 2 images and return similarity score other that takes 1 image and return its embeddings (image2vec). The goal is to get score 1 if 2 images are similar or embeddings that has Euclidean distance ner 0 for similar images <br>
Reference: https://pyimagesearch.com/2020/11/23/building-image-pairs-for-siamese-networks-with-python/
<br>
Similarity network: <br>
![alt text](https://github.com/Solvve/ml_gists/blob/master/Image%20Similarity/keras_siamese_networks_sisters.webp)

## Dataset
Dataset contains 7272 pairs of images, 5090 for training. Each pair contains images form on of 100 classes (at the time this readme file was created) from the StopFundingWar project dataset. Half of all pairs it is pairs with images that belong to the same class with label 1, others has different class images and label 0
Examples: <br>
![alt text](https://github.com/Solvve/ml_gists/blob/master/Image%20Similarity/pair_neg.png)
![alt text](https://github.com/Solvve/ml_gists/blob/master/Image%20Similarity/pair_pos.png)

