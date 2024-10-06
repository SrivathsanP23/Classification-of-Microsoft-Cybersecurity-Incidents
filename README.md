### Classification of Microsoft's CyberSecurity Threats

🚀 Classification done using RandomForestClassifier


#### Dataset Link 
🧑‍💻 - <a href="https://drive.google.com/drive/folders/18vt2lkf69MggXitrTSn9qnZ8s-ToeKcH" target=_blank>Data</a> 

### Project Overview 

### Project Overview:
This project, *Classification of Microsoft Cybersecurity Incidents*, aims to classify cybersecurity incidents using machine learning. A Random Forest model was trained to predict incident severity based on features, achieving 94% accuracy during validation and 88% on the test dataset. The model is deployed for real-time predictions using an interactive Jupyter Notebook.

**Steps That I Followed** :

*Data Preprocessing*:

➡️ loaded the dataset, cleaned it by handling missing values, and removed irrelevant columns.
➡️ applied OneHotEncoding to categorical features and scaled numerical features using StandardScaler with a ColumnTransformer.

*Model Training*:

➡️ trained a Random Forest classifier and tuned its hyperparameters using GridSearchCV to improve performance.

*Model Evaluation*:

➡️ validated the model, achieving 94% accuracy on the training data and 88% accuracy on the test dataset.
