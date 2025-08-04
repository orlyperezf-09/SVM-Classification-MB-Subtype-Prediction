# SVM-Classification-MB-Subtype-Prediction

Notebook with SVM Classification with iteration loops based on a Leave-One-Out Cross-Validation training method. The goal was to generate a radiomic and pathomic feature-based machine learning algorithm to create an alternate pathway for molecular subtype predictions of pediatric Medulloblastoma tumors. 

The notebook starts by merging and normalizing the data sets. This is followed by the initiation of an SVM classifier, which is later applied to the feature datasets with alternating parameters: Linear SVM by itself, with an RBF kernel, and with a Linear kernel. The model is also trained and tested based on 4 molecular subtypes, then 3 subtypes, and finally only 2 subtypes. 

An additional resampling method (SMOTE) was implemented at the end. However, it was not further explored as it creates imaginary data points, which would alter the final results. 
