# Analysis of Heart Disease Prediction Dataset

## Introduction
World Health Organization has estimated 12 million deaths occur worldwide; every year due to Heart diseases. Half the deaths in the United States and other developed countries are due to cardio vascular diseases. The early prognosis of cardiovascular diseases can aid in making decisions on lifestyle changes in high-risk patients and in turn reduce the complications. This research intends to pinpoint the most relevant/risk factors of heart disease.

## Dataset
The dataset is publicly available on the Kaggle website, and it is from an ongoing cardiovascular study on residents of the town of Framingham, Massachusetts. The classification goal is to predict whether the patient has 10-year risk of future coronary heart disease (CHD). The dataset provides the patients’ information. It includes over 4,000 records and 15 attributes.

## Source
https://www.kaggle.com/amanajmera1/framingham-heart-study-dataset/data

## Tools & Libraries
• Python • Jupyter Notebook • Pandas • NumPy • Seaborn

## Machine Learning models
1. Logistic Regression
2. Decision Tree
3. Random Forest
4. Ada Boost
5. Gradient Boost
6. XG Boost
7. KNN
8. Stacking
9. Naive Bayers

## Data Description
• Sex: male or female (Nominal) (binary: “1” means “male”, “0” means “female”)

• Age: Age of the patient;(Continuous - Although the recorded ages have been truncated to whole numbers, the concept of age is continuous).

• Education: (1 = Primary School; 2 = High School; 3 = Pre-University; 4 = Graduate)

• Current Smoker: whether or not the patient is a current smoker (Nominal) (binary: “1”, means “Yes”, “0” means “No”)

• Cigs Per Day: the number of cigarettes that the person smoked on average in one day. (can be considered continuous as one can have any number of cigarettes, even half a cigarette.) Medical(history)

• BP Meds: whether or not the patient was on blood pressure medication (Nominal)
 (binary: “1”, means “Yes”, “0” means “No”)
 
• Prevalent Stroke: whether or not the patient had previously had a stroke (Nominal)
 (binary: “1”, means “Yes”, “0” means “No”)
 
• Prevalent Hyp: whether or not the patient was hypertensive (Nominal)
 (binary: “1”, means “Yes”, “0” means “No”)
 
• Diabetes: whether or not the patient had diabetes (Nominal) 
(binary: “1”, means “Yes”, “0” means “No”)

• Tot Chol: total cholesterol level (Continuous)

• Sys BP: systolic blood pressure (Continuous)

• Dia BP: diastolic blood pressure (Continuous)

• BMI: Body Mass Index (Continuous)

• Heart Rate: heart rate (Continuous - In medical research, variables such as heart rate though in fact discrete, yet are considered continuous because of large number of possible values.)

• Glucose: glucose level (Continuous)

• 10-year risk of coronary heart disease CHD 
(binary: “1”, means “Yes”, “0” means “No”)


## Data Cleaning
•	Null value treatment

## Analysis
•	Visualization is done to check the distribution of each column in the dataset.

•	Using the oversampling technique for the imbalanced dataset.

•	Treating the null values based on the distributions.

•	Used Different machine learning Algorithms to check which is the better model for the dataset.

## Predictions

## Random Forest
### Before hyperparameter tuning	
Accuracy

0.9103

AUC

0.9101

### After hyperparameter tuning

Accuracy
 
0.9108

AUC

0.9107

## XG Boost

### Before hyperparameter tuning	
Accuracy

0.8699		

AUC

0.8696

### After hyperparameter tuning

Accuracy

0.8817	

AUC

0.88144

### Gradient Boost

### Before hyperparameter tuning	
Accuracy

0.8733	

AUC

0.87297

### After hyperparameter tuning

Accuracy

0.875

AUC

0.8747
		
## Ada Boost
### Before hyperparameter tuning	
Accuracy

0.8441

AUC

0.8443

### After hyperparameter tuning

Accuracy

0.8677

AUC

0.8673
		
## Decision Tree
### Before hyperparameter tuning	
Accuracy

0.82230

AUC

0.822353

### After hyperparameter tuning

Accuracy

0.8099

AUC

0.8100

		
## KNN
### Before hyperparameter tuning

Accuracy

0.80156	    

AUC

0.8023	

### After hyperparameter tuning
Accuracy

0.83127		    

AUC

0.83196  

## Logistic Regression

Accuracy

0.6423	  

AUC

0.6425


## Naïve Bayes

Accuracy 

0.61042
   
 AUC
 
0.609364
## Stacking

Prediction

0.89635
