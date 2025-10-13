# Cancer Identification using Machine Learning

### Poject Overview

The Cancer Identification Project aims to develop a predictive machine learning model that can distinguish between benign and malignant cancer cases based on diagnostic data. The dataset, obtained from Kaggle, contains various numerical features computed from digitised images of breast tissue. Each feature describes characteristics of the cell nuclei present in the image.

The project’s primary goal is to build a reliable and interpretable classification model that assists in early cancer detection and improve diagnostic efficiency. 

### Objectives

- Explore and understand the dataset through exploratory data analysis (EDA).
- Preprocess data by handling missing values, encoding categorical variables, and standardizing features.
- Develop and evaluate machine learning models, particularly Logistic Regression and Random Forest Classifier to classify cancer cases.
- Apply Principal Component Analysis (PCA) to reduce dimensionality and assess whether PCA improves model performance.
- Evaluate models using metrics such as accuracy, precision, recall, F1-score, and confusion matrix.


### Data source

https://www.kaggle.com/datasets/erdemtaha/cancer-data

This dataset contains the characteristics of patients diagnosed with cancer. The dataset includes a Unique ID for each patient, the type of cancer (diagnosis), the visual features of the cancer, and the average values of these features.

### Tools

Python

### Key Steps

1. Data Preprocessing: 

Removed irrelevant columns (ID, unnamed columns with missing values).
Encoded the target variable diagnosis (M = 1, B = 0).
Standardized numeric features (mean = 0, standard deviation = 1).

2. Model Development:
   
Trained Logistic Regression and Random Forest classifiers.
Compared performance before and after applying PCA (retaining 95% variance).

3. Model Evaluation:
   
The Logistic Regression model achieved ~95–98% accuracy after PCA.
PCA reduced dimensionality while slightly improving model accuracy and computational efficiency.

### Conclusion

The Logistic Regression and Random Forest models both achieved high accuracy, with Logistic Regression performing slightly better after applying PCA, reaching an accuracy of 98%. PCA not only reduced the number of features while preserving most of the variance but also improved model interpretability and highlighted the most influential features through PCA loadings.

Overall, this analysis demonstrates that careful preprocessing, dimensionality reduction, and model selection can produce a robust and interpretable predictive model for cancer diagnosis.




