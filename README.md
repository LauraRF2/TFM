
## Classification of Parkingson's Disease (PD)

### About the dataset

This dataset from Sakar et al., 2018 was sourced from the Kaggle repository, accessible via the following link: 
https://www.kaggle.com/datasets/dipayanbiswas/parkinsons-disease-speech-signal-features


The data comprises recordings from 188 patients diagnosed with PD (107 men and 81 
women) alongside a control group of 64 individuals (23 men and 41 women). Each participant contributed 
three voice recordings, resulting in a total of 754 extracted features.

To extract clinically useful information for PD assessment, various speech signal processing algorithms 
were applied to the speech recordings of PD patients. These algorithms include Time-Frequency Features, 
Mel Frequency Cepstral Coefficients (MFCCs), Wavelet Transform-based Features, 
Vocal Fold Features, and Time-Warped Quadratic Time-Frequency (TWQT) Features.


### PD Classification

This repository contains code for analyzing the dataset and classify participants according to their condition (PD or control group). 
Main files in this repository include:

- **Descriptive Analysis**: Perform an exploratory data analysis (EDA) to summarize and visualize key characteristics of the dataset.

- **Normalization**: Implement normalization techniques to ensure that the data is on a consistent scale.

- **Variable Reduction**: Test various methods for dimensionality reduction to identify the most relevant features for classification.
  
- **Machine Learning Classification**: Apply different machine learning algorithms to classify participants as either having Parkinson's Disease or belonging to the control group. The code will evaluate model performance using metrics such as accuracy, kappa, MFCC and F1-score.

The ultimate goal of this project is to develop a robust model for classifying individuals based on their speech 
features, contributing to the understanding and assessment of Parkinson's Disease.


### References


Sakar, C.O., Serbes, G., Gunduz, A., Tunc, H.C., Nizam, H., Sakar, B.E., 
Tutuncu, M., Aydin, T., Isenkul, M.E. and Apaydin, H., 2018. A comparative analysis of speech signal processing 
algorithms for Parkinson's disease classification and the use of the tunable 
Q-factor wavelet transform. Applied Soft Computing, DOI: [Web Link] https://doi.org/10.1016/j.asoc.2018.10.022
