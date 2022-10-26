# Predicting-stroke

Using the stroke prediction dataset from Kaggle, I visualised the relationship between various risk factors with the probability of getting stroke. 
I also designed a predictive model to determine whether a patient is likely to get stroke based on risk factors like gender, age, various diseases, and smoking status.

The target variable is "stroke": 1 if the patient had a stroke or 0 if patient do not have a stroke.

Each row in the data provides relevant information about the patient.

The analysis comprised of four main stages; understanding of the data, data cleaning, exploratory data analysis (EDA), and classification of patients by building supervised machine learning model.
I trained 5 classification models which are logistic regression, decision tree, random forest, svc, and knn.
Since there is a large class imbalance in our data, I did oversampling using SMOTE. The oversampling and scaling is done within a pipeline to ensure that our sampling techniques don’t have data leakage.

The notebook is stroke_prediction.ipynb and the dataset is healthcare-dataset-stroke-data.csv
