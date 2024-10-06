### Classification of Microsoft's CyberSecurity Threats

🚀 Classification done using RandomForestClassifier


#### Dataset Link 
🧑‍💻 - <a href="https://drive.google.com/drive/folders/18vt2lkf69MggXitrTSn9qnZ8s-ToeKcH" target=_blank>Data</a> 

### Project Overview 

### Project Overview:
This project, *Classification of Microsoft Cybersecurity Incidents*, aims to classify cybersecurity incidents using machine learning. A Random Forest model was trained to predict incident severity based on features, achieving 94% accuracy during validation and 88% on the test dataset. The model is deployed for real-time predictions using an interactive Jupyter Notebook.

### Steps:
1. **Data Preprocessing**: Loaded and cleaned the dataset, applied OneHotEncoding for categorical features, and scaled numerical features.
2. **Model Training**: Used a Random Forest classifier, optimizing hyperparameters via `GridSearchCV`.
3. **Validation**: Evaluated the model's performance, achieving high accuracy on the validation and test sets.
4. **Model Saving**: Saved the trained model using `joblib`.
