### Metadata

| File Name    | File Type |       Description |  Link   |
| --------- | ------- | -------------| ----------|
| Cardiovascular_Risk_Prediction_Classification.ipynb     |    Colab Notebook     |  	Contains code for ML model implementation of the project    |    [View](https://githubtocolab.com/yahya-ansariii/CardiovascularRisk/blob/master/Cardiovascular_Risk_Prediction_Classification.ipynb)    |
| README.md    |    Markdown     |  The README file for the project    |    [View](https://github.com/yahya-ansariii/CardiovascularRisk/blob/master/README.md)    |
| banner.png     |    Image     |  	An image used in the readme of the project    |    [View](https://github.com/yahya-ansariii/CardiovascularRisk/blob/master/banner.png)    |
| cardio.gif   |    GIF Animation  |  	A GIF animation to display usage of deployed website   |   [View](https://github.com/yahya-ansariii/CardiovascularRisk/blob/master/cardio.gif)   |
| data_cardiovascular_risk.csv     |    CSV     |  A CSV file containing data used in the project    |    [View](https://github.com/yahya-ansariii/CardiovascularRisk/blob/master/data_cardiovascular_risk.csv)    |

# Cardiovascular Risk Prediction - Classification

**AlmaBetter Verified Project** - [**Credentials**](https://certificates.almabetter.com/en/verify/28459737371995)

![banner](banner.png)

<font size=1>Image Courtesy: https://www.istockphoto.com/portfolio/lemono?mediatype=illustration</font>

Check the actual **deployment of the model** on a live server below.
- [**Deployment**](http://cardio.pythonanywhere.com/)

---

## Deployment Demo

![demo](cardio.gif)

---

## Problem Statement

The dataset is from an ongoing cardiovascular study on residents of the town of Framingham, Massachusetts. The classification goal is to predict whether the patient has a 10-year risk of future coronary heart disease (CHD). The dataset provides the patients' information. It includes over 4,000 records and 15 attributes. Each attribute is a potential risk factor. There are both demographic, behavioral, and medical risk factors.

---

## Project Summary

The goal of this project was to use machine learning techniques to predict the 10-year risk of future coronary heart disease (CHD) in patients using data from an ongoing cardiovascular study on residents of the town of Framingham, Massachusetts. The dataset provided information on over 4,000 patients and included 15 attributes, each representing a potential risk factor for CHD. These attributes included demographic, behavioral, and medical risk factors.

To prepare the data for analysis, extensive preprocessing was performed to clean and transform the data. This included handling missing values using median, mode, and KNN imputation techniques, as well as identifying and removing outliers using the Interquartile Range (IQR) method. Skewed continuous variables were also transformed using log and square root transformations to reduce skewness and improve model performance.

Feature selection was performed using variance inflation factor to remove multicollinearity and a new feature called pulse pressure was created to capture the relationship between systolic and diastolic blood pressure. Redundant columns were also removed to simplify the dataset. The most important features for predicting CHD risk were identified as ‘age’, ‘sex’, ‘education’, ‘cigs_per_day’, ‘bp_meds’, ‘prevalent_stroke’, ‘prevalent_hyp’, ‘diabetes’, ‘total_cholesterol’, ‘bmi’, ‘heart_rate’, ‘glucose’, and ‘pulse_pressure’.

To handle the imbalanced nature of the dataset, the SMOTE combined with Tomek links undersampling technique was used to balance the class distribution and improve model performance. The data was also scaled using standard scalar method to ensure that all features were on the same scale.

Several machine learning models were evaluated on their performance on the primary evaluation metric of recall. After careful analysis, the Neural Network (tuned) was chosen as the final prediction model because it had the highest recall score among the models evaluated. By selecting a model with a high recall score, the goal was to correctly identify as many patients with CHD risk as possible, even if it meant having some false positives.

Overall, this project demonstrated the potential of machine learning techniques to accurately predict CHD risk in patients using data from a cardiovascular study. By carefully preprocessing and transforming the data, selecting relevant features, and choosing an appropriate model based on its performance on a relevant evaluation metric, it was possible to achieve a positive business impact by accurately predicting CHD risk in patients.

---

## Conclusion

In conclusion, this project demonstrated the potential of machine learning techniques to accurately predict the 10-year risk of future coronary heart disease (CHD) in patients using data from an ongoing cardiovascular study. Key points from this project include:

- Careful data preprocessing and transformation improved the performance of machine learning models and enabled more accurate predictions.
- Feature selection was important for identifying the most relevant predictors of CHD risk.
- The Neural Network model (tuned) was chosen as the final prediction model due to its high recall score.
- Techniques such as SMOTE combined with Tomek links undersampling and standard scalar scaling were used to handle imbalanced data and improve model performance.
- This project provides a valuable example of how machine learning techniques can be applied to real-world problems to achieve positive business impact.

Overall, this project highlights the importance of careful data preparation and analysis in machine learning projects. By taking the time to clean and transform the data, select relevant features, and choose an appropriate model, it is possible to achieve accurate predictions and support decision-making in a wide range of domains.

---

## Authors

- [Mohammed Yahya Ansari](https://www.linkedin.com/in/yahya-ansari/)
- [Prafull Korde](https://www.linkedin.com/in/prafull-korde-400560126/)
