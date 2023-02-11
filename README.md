# WII Herbaium Plant Classification using Machine Learning
As the name says this project is a machine learning supervised classification project, In this I have followed the following steps:<br>
1-> Data Acquisation<br>
2-> Data cleaning and preprocessing<br>
3-> Feature Exctraction<br>
4-> Model training and selecition<br>
5-> Evaluation/ Acurracy<br>
6-> User-Input based classification and occurence<br>
## Dataset and Goal of the project
The Dataset here used is  Wildlife Institue of India Herbarium Dataset through GBIF network you can get it from [here](https://www.gbif.org/dataset/9e7ea106-0bf8-4087-bb61-dfe4f29e0f17/project). 
The goal for now is to a make classification maodel.
## Cleaning Raw Dataset 
To get a clean dataset considering the goal. The steps i followed were: Handling null values, Removing double and duplicate data(it was done using excel, so not show in the code).
Further to get the better insides of the dataset EDA analysis was done and cleaning was done accordingly using statistical method like mean, mode , meadian and interpolation.
## Analysis and Fetaure Extraction
As the most of the variables were string categorical data types. So i used **Dython** library for it, and to analysis I used heat map and then Extracted the fetures to perform classification
## Model and Classifier
As it is classification model so it comes under supervised machine learning . The classifier algorithm used here are Random Forest , Decision Tree, SVM, KNN, Logistic Regression . But before fitting the model into classifer , **Encoding** was also done to all the extracted categorical features, so that algorithm can work smoothly.
## Evaluation and more results
For evaluation of model metrics like accuracy, recall and F1 score are used.Out of all the 5 classifier one with the high accuracy and was not seem to be overfitting was decision tree. So, decision tree classifier based model gives the best result. Other insights have also been drieved from the dataset by visualization.<br>
## User-Input base classification and occurence
As for the result Input based classification is done. Also the ocurrence (state provision and localitiy) have been extracted on the basis of classification.
## Future work
There is scope of improvement in the model as i think it is overfitting  because it is achieving around 100% accuracy in Random Forest based model. Furhter deployment of the model can also be done. Since, Herbarium dataset holds scientific value for research. 
