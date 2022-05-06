# Anomaly localization on MRI images
[![Solvve](https://img.shields.io/badge/made%20in-solvve-blue)](https://solvve.com/)

## Description
Unsupervised learning for finding abnormall parts of brain on MRI images. Training of 2 types of models  using https://github.com/rvorias/ind_knn_ad.git for KNN and  https://github.com/cvblab/anomaly_localization_vae_gcams.git for Encoder/Decoder approach

## Dataset
Dataset contains images of 16 patients, 8 with healthy brain and 8 has some diseases. For each of them 3 views presents: side, top, front with 79, 79, 95 scans respectively
Example:
![alt text](https://github.com/Solvve/ml_gists/blob/master/MRI_anomaly_localization/data.png)

## Results
Example of anomaly localization of KNN method
Images:
![alt text](https://github.com/Solvve/ml_gists/blob/master/MRI_anomaly_localization/prediction.png)
Videos:
https://github.com/Solvve/ml_gists/blob/master/MRI_anomaly_localization/prediction_patient1.mp4
https://github.com/Solvve/ml_gists/blob/master/MRI_anomaly_localization/prediction_patient8.mp4
