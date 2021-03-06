# Human-Activity-Recognision-with-Smartphones
The Human Activity Recognition database was built from the recordings of 30 study participants performing activities of daily living (ADL) while carrying a waist-mounted smartphone with embedded inertial sensors. The objective is to classify activities into one of the six activities performed.
More info on the data can be accessed [**here**](https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones)

Here is the link for the [**Dashboard**](https://human-action-classifier.herokuapp.com/) by which we can perform changing hyperparameters for classifiers and visualize data in 2D

This repo also contains a jupyter notebook [**'mobile_data.ipynb'**](https://github.com/samyak1234/Human-Activity-Recognision-with-Smartphones/blob/master/mobile_data.ipynb) in which I performed **Data Visualisation**, **Data cleaning**, and **Hyperparameter tuning** for various classifiers which includes -

- Logistic Regression
- Linear SVM
- Kernal SVM
- Dicision Tree
- Random Forest

The best results were given by **Linear SVM** with accuracy = 96.88 % 
The accuracies of other classifiers are as follows-

![Accuracies](https://github.com/samyak1234/Human-Activity-Recognision-with-Smartphones/blob/master/images/results12345.png)

Data visualisation in 2D space using t-SME - 

![2D](https://github.com/samyak1234/Human-Activity-Recognision-with-Smartphones/blob/master/images/2Dviz.png)

Confusion matrix for Logistic Regression

![CM_lr](https://github.com/samyak1234/Human-Activity-Recognision-with-Smartphones/blob/master/images/cm.png)






