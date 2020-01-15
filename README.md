# Coronary_Heart_Disease

Humans are generating data at a very rapid speed and the healthcare industry holds the paramount data which needs to be analyzed much differently than the traditional approaches. The power of today's modern computers helped us in identifying the hidden patterns from Exabyte's of structured or unstructured data and building the decision support systems on top of it. 

Worldwide each year Cardiovascular disease causes an estimated 17 million deaths accounting for one-third of all deaths worldwide. Out of this, more than one-third of deaths occur in middle-aged adults. Cardiovascular disease majorly includes Coronary heart disease (CHD) and Cerebrovascular disease (stroke). 

In this project, I worked with the heart disease dataset to identify the best classification algorithm for classifying the heart illness of a person. I comprehensively used the various machine learning models for predicting the outcome with the maximum accuracy. I also used several data pre-processing techniques and performed the extensive model tuning and feature selection techniques to classify the heart disease in a normal and abnormal person with superior precision.

**_This is the supervised learning classification project for predicting the Heart Disease._**

**_Coronary_Artery_Disease.ipynb_** : Contains the code with below stages:

    1. Data Import
    2. Data Cleansing
     2.1 Null or missing values handling
     2.2 Datatype handling
    3. Exploratory Data Analysis
    4. Data Pre-processing
        4.1 Quantitative variables
             a. Feature Scaling
             b. Feature Transformation
             c. Outlier detection
             d. Outlier handling
        4.2 Categorical variables
            a. Get_dummies
    5. Handling class imbalance
        4.1 Used Random Over Sampler
    6. Models Evaluation
        6.1 Naive Bayes
        6.2 Logistic Regression
        6.3 Gradient Boosting Classifier
        6.4 Decision Trees
        6.5 Random Forest
    7. Model Hyperparameter tuning
        7.1 Gradient Boosting Classifier
        7.2 Random Forest
    8. Extensive Feature Selection with F1 & ROC Scores
        8.1 Gradient Boosting Classifier
        8.2 Random Forest
 
 **_processed.cleveland.data_** : Cleveland Data
 
 **_processed.hungarian.data_** : Hungarian Data
 
 **_Features detailed handbook.docx_** : Features detailed description handbook
 
 **_Heart Disease Data.xlsx_** : Dataset in excel
 
 **_heart-disease.names_** : Dataset variables description
 
**Thanks to below dataset creators who donated this dataset on the UCI Machine Learning Repository:**

    1. Hungarian Institute of Cardiology. Budapest: Andras Janosi, M.D.
    2. University Hospital, Zurich, Switzerland: William Steinbrunn, M.D.
    3. University Hospital, Basel, Switzerland: Matthias Pfisterer, M.D.
    4. V.A. Medical Center, Long Beach and Cleveland Clinic Foundation: Robert Detrano, M.D., Ph.D.
