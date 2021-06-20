# Malicious-Website-Detection

## Aim
Website security is one of the major concerns in the digital world as different businesses, eCommerce, banks, and educational websites are being utilized by a large number of people. These websites handle sensitive data like bank credentials and vital information such as credit card numbers and personal details. Therefore the possibility of a website attack is very high. The aim of this project is to train a machine learning model on the selected dataset to predict benign and malicious websites. 

## Data Collection 
The dataset used in this project was contributed in IEEE, Kaggle (https://ieee-dataport.org/documents/malicious-and-benign-websites) by "Christian Urcuqui". This dataset was created as part of the project "classification of malicious and benign websites". The information was gathered by examining a variety of malicious and benign URLs and analyzing network traffic in a low-interactive client honeypot. The dataset is prepared for the classification of malicious websites from benign websites which contain a total of 1781 samples along with 20 features. The class distribution of the dataset is 1565 benign class and 216 malicious class.

## Model Selection and Performance Evaluation
The model is constructed using Random Forest Classification in this proposed system. Random forest is an ensembling method that generates single answers by voting. It is most effective when categorical and numerical values are used. SVM classifier is taken as a benchmark model for this project. The dummy model used for this project is a dummy classifier from scikit learn. This baseline helps to know whether the model is good or not. The strategy selected is stratifica-
tion, because for classification task stratification makes sure that the data is drawn uniformly from all the classes. The use of a weighted parameter can aid in the handling of severely unbalanced datasets.

For this project, F1-score, Precision, and Recall are the matrics choosen to evaluate the model.

## End Results
Random forest performed well with 99.2% F1-score, 98.4% recall, and 100% precision when compared to SVM and dummy model. SVM showed a variation of 91.6% F1-score, 84.6% recall, and obtained 100% precision value. While the dummy classifier showed low performance with range of 16.7 F1-score, 16.9 recall and 16.6 precision.

As a next step, the proposed method can be implemented using deep learning algorithms and compare the results.
