# Ecommerce-Purchase-Prediction

### Introduction:
This project aims to develop machine learning models to predict the purchasing intention of e-commerce visitors based on their online activity information, including clickstream and session data. The dataset contains relevant information, and the goal is to explore the data, preprocess it, select appropriate machine learning methods, implement the models, and evaluate their performance.

### Task:
The main task of this project is to build and evaluate various machine learning models for predicting visitors' purchasing intention in an e-commerce context. 

### Steps:
1. Data Exploration
2. Data Pre-processing
3. Model Selection and Implementation
4. Model Performance Evaluation:

### Results:
The final output table summarizes the performance of each implemented machine learning model on both the training and testing datasets. The following metrics are presented:

* Accuracy Score Train: The accuracy of the model on the training dataset.
* ROC-AUC Score Train: The ROC-AUC score of the model on the training dataset.
* Accuracy Score Test: The accuracy of the model on the testing dataset.
* ROC-AUC Score Test: The ROC-AUC score of the model on the testing dataset.

The table lists various models and their corresponding performance metrics, allowing easy comparison and identification of the top-performing models.

| 	Model	| 	Accuracy Score Train	| 	ROC-AUC Score Train	 | 	Accuracy Score Test	 | 	ROC-AUC Score Test	 |
| 	:-----:	| 	:-----:	| 	:-----:	 | 	:-----:	 | 	:-----:	 |
| 	Logistic|	0.846237|	0.923399|	0.840633|	0.876679	 |
| 	Decision Tree	|1.000000|	1.000000|	0.862936|	0.783592	 |
| 	Naive Bayes|	0.579286|	0.656004|	0.294809|	0.633782|
|Random Forest|	1.000000|	1.000000|	0.893350|	0.930671|
|KNN	|0.883806	|0.963881	|0.723844	|0.706968|
|Bagging|	0.996393|	0.999909|	0.880779|	0.905881|
|Ada-Boost|	0.905145	|0.965189	|0.884428	|0.921009|
|Gradient Boost	|0.925643	|0.981165|	0.890916|	0.936724|
|LGBM|	0.961529|	0.994580|	0.900649|	0.935665|
|Soft Voting	|0.995612	|0.999938|	0.892944|	0.933197|
|Weighted Soft |Voting	|0.998257|	0.999990|	0.890105|	0.929662|
|XGB	|0.919512|	0.979301	|0.888483|	0.935443|
|SVM|	0.877434|	0.943612|	0.815085|	0.837505|
