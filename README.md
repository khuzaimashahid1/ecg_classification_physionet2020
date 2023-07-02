# 12 lead ECG Classification || Physionet2020
Identification of clinical diagnoses from 12-lead ECG recordings defined as a multi-label multi-class problem. Solution accepted in online challenge.
CNN Feature Extractor with binary SVCs for final diagnosis using TensorFlow and Scikit-Learn.
# Solution Overview
In this work we proposed deep learning model to classify ECG automatically. Our proposed system consists of 2 phases.
Firstly, a deep Convolutional neural network based feature extractor extracts necessary information from a given ECG signal and then the features are finally classified into one or many of the 24 classes through the use of binary support vector classifiers which are trained using 1 vs rest approach. The results indicate that automatically categorizing 12-lead ECGs has significant application value.

# Reproduction
Download training data in data folder and run the script. It will train fetaure extractor and then the binary SVCs and will evaluate the solution for all provided challenge metrics used in the original competition.
