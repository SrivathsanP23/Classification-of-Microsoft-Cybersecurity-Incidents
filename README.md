### Classification of Microsoft's CyberSecurity Threats

🚀 Classification done using RandomForestClassifier


#### Dataset Link 
🧑‍💻 - <a href="https://drive.google.com/drive/folders/18vt2lkf69MggXitrTSn9qnZ8s-ToeKcH" target=_blank>Data</a> 


### Project Overview:
This project, *Classification of Microsoft Cybersecurity Incidents*, aims to classify cybersecurity incidents using machine learning. A Random Forest model was trained to predict incident severity based on features, achieving 94% accuracy during validation and 88% on the test dataset. The model is deployed for real-time predictions using an interactive Jupyter Notebook.

**Steps That I Followed** :

1. **Data Preprocessing** :

Loading the Dataset: Loaded the dataset from the source and explored its structure.
Data Cleaning: Handled missing values by using appropriate imputation techniques and removed irrelevant columns to enhance model performance.
Feature Encoding: Applied OneHotEncoding to categorical features to convert them into a suitable format for model training.
Feature Scaling: Scaled numerical features using StandardScaler through a ColumnTransformer to ensure that all features contributed equally to the model.

2. **Exploratory Data Analysis (EDA)**:
Statistical Testing:
F-test: Conducted F-tests for categorical columns to assess the relationship between categorical features and the target variable. This helped in understanding which categorical features had significant effects on the severity of cybersecurity incidents.
Z-test: Performed Z-tests for numerical columns to determine if the means of the different groups (based on the target variable) were statistically significantly different. This analysis guided feature selection and helped identify impactful numerical features.


3. **Model Training**:
Random Forest Classifier: Trained a Random Forest classifier on the preprocessed data to leverage its ensemble learning capabilities.
Hyperparameter Tuning: Utilized GridSearchCV for hyperparameter tuning, optimizing parameters such as the number of estimators, maximum depth, and minimum samples required for splitting, to improve model performance.


4. **Model Evaluation**:
Validation: Evaluated the model on a validation set, achieving 94% accuracy on the training data and 88% accuracy on the test dataset. Metrics such as precision, recall, and F1-score were also calculated to assess the model's effectiveness.
