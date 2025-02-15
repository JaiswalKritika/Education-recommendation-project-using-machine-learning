# Education Recommendation System using Machine Learning

## Project Overview
This project builds an **Education Recommendation System** that predicts a student's **career aspiration** based on their academic scores and other relevant features. The system uses **machine learning** techniques to classify students into different career paths based on their performance and activities.

## Features & Methodology

### 1. Data Preprocessing
- Dropping irrelevant features (`id`, `first_name`, `last_name`, `email`).
- Feature Engineering: Creating `total_score` and `average_score` from subject scores.
- Encoding categorical variables using **Label Encoding**.
- Handling class imbalance using **SMOTE (Synthetic Minority Over-sampling Technique)**.

### 2. Data Splitting & Scaling
- Splitting data into **train and test sets** (80/20 split).
- Applying **StandardScaler** to normalize features for better model performance.

### 3. Model Training & Evaluation
- **Machine Learning Model:** Random Forest Classifier
- **Hyperparameter Tuning:** GridSearchCV for optimal parameters.
- **Performance Metrics:** Accuracy, Confusion Matrix, and Classification Report.

### 4. Model Saving & Deployment
- Saving the trained model for future predictions.
- Loading the saved model for inference.

## Technologies Used
- **Programming Language:** Python
- **Libraries & Frameworks:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Imbalanced-learn (SMOTE)
- **Machine Learning Algorithm:** Random Forest Classifier

## Dataset
- The dataset consists of student academic scores in different subjects along with additional attributes like **extracurricular activities** and **part-time job participation**.


## Results & Insights
- The model successfully predicts career aspirations based on student performance.
- Class imbalance was handled effectively using **SMOTE**.
- Feature scaling improved model performance.

## Future Improvements
- Experiment with advanced models like **XGBoost or Neural Networks** for better accuracy.
- Integrate additional features like **personality traits and interests**.


