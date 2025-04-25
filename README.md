# Diabetes Prediction
A machine learning model that predicts how likely a patient has diabetes or not 

# Introduction
The prevalence of diabetes is increasing globally. Diabetes is a significant public health concern due to its associated health complications and economic burden on individuals, families, and healthcare systems. As a result, there is a growing need for data-driven approaches to diabetes prevention, early detection, and management.

Diabetes is a chronic metabolic disorder characterized by high blood glucose levels resulting from defects in insulin secretion, insulin action, or both. Insulin is a hormone produced by the pancreas that regulates blood glucose levels by facilitating the uptake of glucose from the blood into cells for energy production or storage. In individuals with diabetes, the body either does not produce enough insulin or cannot effectively use the insulin produced, resulting in high blood glucose levels, which can lead to various complications, such as damage to the kidneys, nerves, eyes, and blood vessels.

# Overview of the data
The dataset used for this project was Pima Indians Diabetes Database ( from Github). This dataset is used to predict how likely a patient has diabetes or not based on the input parameters like Pregnancies, Glucose, Blood pressure, Insulin, Body mass index, etc. All patients used in this data are at least 21 years old.

Features of the dataset:

The dataset contains 2000 individuals data with 9 features set. The detailed description of all the features are as follows:

* Pregnancies: indicates the number of pregnancies
* Glucose: indicates the plasma glucose concentration
* Blood Pressure: indicates diastolic blood pressure in mm/Hg
* Skin Thickness: indicates triceps skinfold thickness in mm
* Insulin: indicates insulin in U/mL
* BMI: indicates the body mass index in kg/m2
* Diabetes Pedigree Function: indicates the function which scores likelihood of diabetes based on family history
* Age: indicates the age of the person
* Outcome: indicates if the patient had a diabetes or not (1 = yes, 0 = no)

# Libraries Used 
* Pandas- used for data manipulation and analysis
* Numpy- used for N-dimensional arrays, matrices and linear algebra
* Seaborn- used for data visualization
* Matplotlib- used for data visualization
* Scikit Learn- used for machine learning algorithms

# Techniques Used
* Data Cleaning
* Data Visualization
* Machine Learning Modeling

# Algorithm Used 
* Decision Tree

# Model Development
* Trained a Decision Tree Classifier with preprocessed data.
* Visualized the tree structure to interpret decision paths.
* Evaluated model performance using key metrics:
   * Accuracy - 83.8 %
   * Precision - 91.3%
  * Sensitivity (Recall) - 90.9%
  * Specificity - 13.2%
  * F-score - 91.1%

# Results & Evaluation
* Constructed a confusion matrix to analyze model performance.
* High precision and recall indicate effective detection of diabetic cases.
* Low specificity suggests need for further refinement to reduce false positives.

# Next Steps
* Implement dataset balancing techniques to address class imbalance.
* Perform hyperparameter tuning to optimize model performance.
* Evaluate alternative machine learning models (e.g., Random Forest, Logistic Regression)
* Compare models based on specificity, interpretability, and overall performance.
