Heart Disease Prediction using Data Mining
Overview:
This project focuses on data mining techniques applied to the Heart Disease Dataset obtained from the UCI Machine Learning Repository. The primary objective is to explore the dataset, preprocess the data, perform feature engineering, and train machine learning models to predict the likelihood of heart disease.

Objectives:
Data Exploration: Understand the dataset and its distribution.
Exploratory Data Analysis (EDA): Perform univariate and bivariate analysis to explore relationships between features and the target variable.
Data Preprocessing: Handle missing data and treat outliers.
Feature Engineering: Encode categorical features, select relevant features, and remove unwanted ones.
Model Training: Train the dataset using Decision Tree, Random Forest, and K-Nearest Neighbors (KNN) algorithms.
Model Evaluation: Assess model performance using F1 Score, Precision, Recall, and Accuracy.
Dataset
The dataset is sourced from the UCI ML Repository and contains records from:

Cleveland
Hungary
Switzerland
VA Long Beach

Dataset Characteristics
Multivariate dataset: Comprising 14 key attributes related to heart disease prediction.
Total attributes: 76 (only 14 are commonly used in ML research).
Prediction goal: Determine whether a patient has heart disease based on medical attributes.
Key Features
Age
Sex
Chest Pain Type
Resting Blood Pressure
Serum Cholesterol
Fasting Blood Sugar
Resting ECG Results
Maximum Heart Rate Achieved
Exercise-Induced Angina
ST Depression (Oldpeak)
Slope of Peak Exercise ST Segment
Number of Major Vessels (Colored by Fluoroscopy)
Thalassemia
Target (Presence or absence of heart disease)
Implementation Steps
Data Preprocessing

Handle missing values
Detect and treat outliers
Encode categorical variables
Exploratory Data Analysis (EDA)

Statistical summary and visualization
Correlation analysis
Feature Engineering

Select most relevant features
Remove unnecessary attributes
Model Training

Train models using Decision Tree, Random Forest, and KNN
Hyperparameter tuning for optimal performance
Model Evaluation

Compare models based on Accuracy, Precision, Recall, and F1-Score
Technologies Used
Python
Pandas, NumPy (Data manipulation)
Matplotlib, Seaborn (Data visualization)
Scikit-Learn (Machine Learning models)
How to Use
Clone the repository:
bash
Copy
Edit
git clone https://github.com/your-username/heart-disease-prediction.git
Navigate to the project directory:
bash
Copy
Edit
cd heart-disease-prediction
Install dependencies:
bash
Copy
Edit
pip install -r requirements.txt
Run the Jupyter Notebook or Python script for training and evaluation.
Contributing
Contributions are welcome! If you'd like to improve this project, feel free to submit a pull request.

License
This project is licensed under the MIT License.
