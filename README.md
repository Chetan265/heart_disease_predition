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

0.9103139013452914

AUC

0.9101663046975547

### After hyperparameter tuning

Accuracy
 
0.905829596412556

AUC

0.9056919642857143

## XG Boost

### Before hyperparameter tuning	
Accuracy

0.8699551569506726	

AUC

0.8696157094594594

### After hyperparameter tuning

Accuracy

0.8817264573991032	

AUC

0.8814450611325612

### Gradient Boost

### Before hyperparameter tuning	
Accuracy

0.8733183856502242	

AUC

0.8729790057915059

### After hyperparameter tuning

Accuracy

0.875560538116592

AUC

0.8752815315315315
		
## Ada Boost
### Before hyperparameter tuning	
Accuracy

0.844170403587444

AUC

0.8438857384169883

### After hyperparameter tuning

Accuracy

0.8677130044843049

AUC

0.8673835666023166
		
## Decision Tree
### Before hyperparameter tuning	
Accuracy

0.8223094170403588

AUC

0.8223536036036037

### After hyperparameter tuning

Accuracy

0.8307174887892377

AUC

0.8307744128056629

		
## KNN
### Before hyperparameter tuning

Accuracy

0.8015695067264574    

AUC

0.8023246460746459	

### After hyperparameter tuning
Accuracy

0.8312780269058296	    

AUC

0.8319608671171171

## Logistic Regression

Accuracy

0.6423766816143498	  

AUC

0.6425655566280567


## Naïve Bayes

Accuracy 

0.6104260089686099
   
 AUC
 
0.6093649453024452

## Stacking

Prediction

0.896358543417367


## SVC

### Before hyperparameter tuning

Accuracy

0.6647982062780269   

AUC

0.6650880791505792	

### After hyperparameter tuning
Accuracy

0.7634529147982063	    

AUC

0.7637598536036037


## Result
Random forest is best model compare to other models.
