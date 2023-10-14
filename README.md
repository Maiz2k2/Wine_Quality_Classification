# Wine_Quality_Classification
Red Wine Quality Classification

This project revolves around the classification of red wine quality using machine learning techniques. It's a Python-based project, and here's an overview of the project:

•	Data Acquisition: The project commences by importing data from an Excel file, which contains a myriad of attributes associated with red wine.

•	Data Preprocessing: The data is meticulously scrutinized, checked for any missing values, and any gaps are filled with the mean values where necessary. This data cleansing process ensures that the dataset is pristine and prepared for analysis.

•	Data Visualization: The distribution of continuous attributes within the dataset is visually represented using histograms. This aids in gaining insights into the data's inherent characteristics.

•	Quality vs. Alcohol Content: A bar plot is generated to illustrate the interplay between wine quality and its alcohol content.

•	Feature Redundancy: The project identifies and subsequently eliminates redundant features by constructing a correlation heatmap. This step ensures that the dataset used for classification is free from irrelevant attributes.

•	Classification Objective: The primary aim is to predict whether a wine can be classified as "high quality" (quality > 5) or not. The dataset is segregated into features (attributes) and a target variable. Subsequently, machine learning models (such as Logistic Regression, XGBoost, and Support Vector Machine) are trained to classify red wine quality based on these attributes.

•	Model Assessment: The project rigorously assesses the accuracy of the models, both during the training phase and on a distinct validation dataset. Additionally, it provides visual representations of confusion matrices and delivers comprehensive classification reports to gauge the models' performance.

This project serves as a pragmatic illustration of employing machine learning to categorize the quality of red wine based on its intrinsic attributes.
