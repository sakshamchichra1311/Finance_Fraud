# Financial-Fraud-Detection-using-Machine-Learning
This is a Machine Learning model for detecting fraudulent financial transactions using Random Forest. The project includes data preprocessing, feature engineering, SMOTE for class balancing, and fraud trend visualization using Matplotlib.

# Key Features
Preprocessed and analyzed **5.3M transactions** to extract fraud-related patterns.
Implemented **Random Forest Classifier**, achieving **99.9% accuracy** in fraud detection.
Engineered features such as transaction amount ratios and balance differences to enhance model performance.
Applied **SMOTE** to handle class imbalance, improving fraud recall.
Generated data visualizations using **Matplotlib** to analyze fraud trends.

# Technologies Used
Python: Pandas, NumPy, Scikit-learn, Matplotlib
Machine Learning: Random Forest, SMOTE (oversampling), Feature Engineering
Data Processing: Data Cleaning & Preprocessing
Visualization: Matplotlib

# Usage
Download the dataset from [Kaggle](https://www.kaggle.com/datasets/sriharshaeedala/financial-fraud-detection-dataset). 
Place the dataset inside the data/ folder.
Open and run fraud_detection.ipynb in Jupyter Notebook or Google Colab.
The trained model will be saved in the models/ folder for later use.

# Results
The Random Forest model achieved 99.9% accuracy, successfully identifying fraudulent transactions.
Feature importance analysis highlighted amount ratio and balance differences as key fraud indicators.
Data visualizations provided insights into fraudulent behavior patterns.

# License
This project is open-source and available under the MIT License.
