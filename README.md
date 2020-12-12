# Physionet2020
 Submission to Physionet2020 that was accepted among top 20 solutions.
# Solution Overview
In this work we proposed deep learning model to classify ECG automatically. Our proposed system consists of 2 phases.
Firstly, a deep Convolutional neural network based feature extractor extracts necessary information from a given ECG signal and then the features are finally classified into one or many of the 24 classes through the use of binary support vector classifiers which are trained using 1 vs rest approach. The results indicate that automatically categorizing 12-lead ECGs has significant application value.

# Reproduction
Download training data in data folder and run the script. It will train fetaure extractor and then the binary SVCs and will evaluate the solution for all provided challenge metrics used in the original competition.
