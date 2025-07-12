Covid-19 Detection Using Machine Learning


📝 Description:


This project aims to detect Covid-19 infections using machine learning techniques based on symptoms and health data. The system leverages classification algorithms to predict whether a person is likely infected with Covid-19 using a labeled dataset containing medical symptoms, contact history, and health status.

🏗️ Project Structure:


Covid-19-Detection-Using-Machine-Learning/
├── data/
│   └── Covid Dataset.csv
├── notebooks/
│   └── covid_detection.ipynb
├── src/
│   ├── preprocessing.py
│   ├── models.py
├── requirements.txt
├── README.md

📝 Dataset Description:


The dataset used in this project includes patient data with various features such as:
Fever (yes/no or temperature)
Cough
Sore Throat
Shortness of Breath
Age
Contact with Covid-Positive person
Test Result (Target Variable: Positive or Negative)
The dataset is assumed to be in CSV format (e.g., Covid Dataset.csv) and is used for training and testing classification models.

🔧 Requirements:


To run this project, the following libraries are required:
Required Libraries:
pandas – For data manipulation
numpy – For numerical computations
matplotlib / seaborn – For data visualization
scikit-learn – For machine learning models

🔍 Data Preprocessing:


Before applying ML algorithms, the dataset undergoes several preprocessing steps:
Handling Missing Values: Removing or imputing null entries.
Label Encoding: Converting categorical variables (e.g., Yes/No) into numerical format.
Feature Selection: Selecting the most relevant columns that influence Covid detection.
Train-Test Split: Dividing the data typically into 80% training and 20% testing sets.

🤖 Algorithms Used:


Multiple supervised machine learning algorithms are used to compare accuracy and performance:
Logistic Regression
Support Vector Machine (SVM)
Decision Tree Classifier
Random Forest Classifier
K-Nearest Neighbors (KNN)
Naive Bayes
Each algorithm is evaluated based on metrics like accuracy, precision, recall, and confusion matrix.

📊 Results:


The best-performing model in terms of accuracy was:
Model: Random Forest
Accuracy: ~96% (example)
F1 Score: High precision and recall
Confusion matrix and classification reports are generated for all models to validate performance.




