# PCA & XgBoost Application

![image](https://github.com/Mansouri-Anas/PCA-XgBoost-Application-/assets/106403012/f7f2b4d2-d1c4-4291-80c3-f15a3f3a5542)


Welcome to the PCA XgBoost Application repository! This repository houses an exciting and powerful application that combines Principal Component Analysis (PCA) and the XGBoost machine learning algorithm. The application is designed to recognize gender based on voice parameters and offers an efficient and accurate solution for predictive modeling.

## Dataset

We utilized the [Voice Gender Recognition](https://www.kaggle.com/datasets/primaryobjects/voicegender) dataset from Kaggle for this application. The dataset contains a comprehensive collection of voice parameters and corresponding labels indicating the gender of the speaker. This dataset serves as the foundation for our gender recognition model.

## Dimensionality Reduction with PCA

In order to enhance the efficiency and interpretability of the gender recognition model, we employed Principal Component Analysis (PCA) to reduce the number of variables while retaining the majority of the information. By transforming the original dataset with 20 voice parameters into a lower-dimensional subspace of 5 principal components, we achieved a more concise representation without significant loss of relevant features.

## XGBoost Model

To leverage the power of ensemble learning and boost the accuracy of our gender recognition model, we integrated the state-of-the-art XGBoost algorithm. XGBoost is known for its exceptional performance in handling complex and non-linear relationships within the data. By training an XGBoost model on the transformed PCA data, we were able to achieve superior precision in predicting the gender of speakers based on their voice parameters.

![image](https://github.com/Mansouri-Anas/PCA-XgBoost-Application-/assets/106403012/ecb4f8e2-db46-41de-a2db-eaf94d947ab2)
