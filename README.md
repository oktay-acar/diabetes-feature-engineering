# Diabetes Feature Engineering

**Business Problem**

It is desired to develop a machine learning model that can predict whether people have diabetes when their characteristics are specified. You are expected to perform the necessary data analysis and feature engineering steps before developing the model.

**Dataset Story**

The dataset is part of the large dataset held at the National Institutes of Diabetes-Digestive-Kidney Diseases in the USA.

Data used for diabetes research on **Pima Indian women** aged 21 and over living in Phoenix, the 5<sup>th</sup> largest city of the State of Arizona in the USA. It consists of 768 observations and 8 numerical independent variables.

The **target variable** is specified as **'outcome'**; **1** indicates **positive** diabetes test result, **0** indicates **negative**.

**Variables**
- **Pregnancies:** Number of pregnancies
- **Glucose:** 2-hour plasma glucose concentration in the oral glucose tolerance test
- **BloodPressure:** Blood Pressure *(Diastolic-Low blood pressure) (mm Hg)*
- **SkinThickness:** Skin Thickness
- **Insulin:** 2-hour serum insulin *(mu U/ml)*
- **BMI:** Body Mass Index
- **DiabetesPedigreeFunction:** A function that calculates the probability of having diabetes based on people in the lineage.
- **Age:** Age *(year)*
- **Outcome:** Information whether the person has diabetes or not. Have the disease *(1)* or not *(0)*

---

## Requirements
~~~python
matplotlib==3.7.1
numpy==1.24.3
pandas==1.5.1
seaborn==0.12.1
sklearn==1.3.1
~~~

---

## Author
[Oktay Acar](https://github.com/oktay-acar)