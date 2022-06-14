# Predicting the Onset of Diabetes

Data mining and machine learning is helping medical professionals make diagnosis easier by bridging the gap between huge data sets and human knowledge. We can begin to apply machine learning techniques for classification in a dataset that describes a population that is under a high risk of the onset of diabetes.

---


### Context

This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian heritage.

### Content

The datasets consists of several medical predictor variables and one target variable, Outcome. Predictor variables includes the number of pregnancies the patient has had, their BMI, insulin level, age, and so on.

### Feature Description

<b>Pregnancies</b> : number of times the person was pregnant

<b>Glucose</b>:Plasma glucose concentration a 2 hours in an oral glucose tolerance test

<b>BloodPressure</b>:Diastolic blood pressure (mm Hg)

<b>SkinThickness</b>:Triceps skin fold thickness (mm)

<b>Insulin</b>:2-Hour serum insulin (mu U/ml)

<b>BMI</b>: Body mass index (weight in kg/(height in m)^2)

<b>DiabetesPedigreeFunction</b>: "Diabetes Pedigree Function, pedi. It provided some data on diabetes mellitus history in relatives and the genetic relationship of those relatives to the patient. This measure of genetic influence gave us an idea of the hereditary risk one might have with the onset of diabetes mellitus. Based on observations in the proceeding section, it is unclear how well this function predicts the onset of diabetes." https://machinelearningmastery.com/case-study-predicting-the-onset-of-diabetes-within-five-years-part-1-of-3/

<b>Age</b>: Age (years)

<b>Outcome</b>: Has diabetes or not (Class variable 0 or 1)


## Observations

- Distribution of medical predictors;
- Diabetic and Non Diabetic split;
- DIstribution of Outcome feature with individual predictor variables;
- Minimum values for different parameters;
- Checking the outliners;
- Relations between predictor variables to Outcome;

 
## Prerequisites & Getting started

<u>None.</u> All libraries used are in the notebook ready to be downloaded:

	* numpy
	* pandas
	* matplotlib
	* seaborn


