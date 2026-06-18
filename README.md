# Rainfall-Prediction-ML
Rainfall prediction using classification algorithms in Scikit-learn.
# 🌧️ Rainfall Prediction using Classification Algorithms

## 📌 Overview

This project focuses on predicting rainfall occurrence using machine learning classification algorithms. By analyzing weather-related features such as temperature, humidity, wind speed, precipitation, cloud cover, and atmospheric pressure, the model predicts whether it will rain the following day.

The project demonstrates the complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and comparison of multiple classification algorithms.

---

## 🎯 Objectives

* Analyze weather data to identify patterns related to rainfall.
* Build machine learning models for rainfall prediction.
* Compare the performance of various classification algorithms.
* Evaluate models using standard classification metrics.

---

## 📊 Dataset

The dataset contains weather observations collected from multiple locations and includes the following features:

| Feature       | Description                             |
| ------------- | --------------------------------------- |
| Date          | Date of observation                     |
| Location      | City/Location                           |
| Temperature   | Temperature measurement                 |
| Humidity      | Humidity level                          |
| Wind Speed    | Wind speed measurement                  |
| Precipitation | Amount of precipitation                 |
| Cloud Cover   | Cloud cover percentage                  |
| Pressure      | Atmospheric pressure                    |
| Rain Tomorrow | Target variable (0 = No Rain, 1 = Rain) |

---

## 🔍 Exploratory Data Analysis (EDA)

The project includes:

* Data inspection and summary statistics
* Missing value analysis
* Unique location analysis
* Rainfall distribution visualization
* Correlation heatmap analysis
* Feature relationship exploration

---

## ⚙️ Data Preprocessing

The following preprocessing techniques were applied:

* Removal of non-numeric features for model training
* Feature-target separation
* Feature scaling using StandardScaler
* Train-Test Split (80% Training, 20% Testing)

---

## 🤖 Machine Learning Models

The following classification algorithms were implemented:

1. Logistic Regression
2. K-Nearest Neighbors (KNN)
3. Decision Tree Classifier
4. Random Forest Classifier
5. Support Vector Machine (SVM)
6. Gaussian Naive Bayes

---

## 📈 Model Evaluation

Models were evaluated using:

* Accuracy Score
* Precision Score
* Recall Score
* F1-Score
* Confusion Matrix

These metrics provide a comprehensive understanding of model performance and prediction quality.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab

---

## 📂 Project Workflow

1. Load and explore the dataset.
2. Perform data cleaning and preprocessing.
3. Visualize feature relationships.
4. Scale numerical features.
5. Split data into training and testing sets.
6. Train multiple classification models.
7. Evaluate and compare model performance.
8. Analyze results and identify the best-performing model.

---

## 🚀 How to Run

```bash
# Clone the repository
git clone https://github.com/your-username/rainfall-prediction-classification.git

# Navigate to project directory
cd rainfall-prediction-classification

# Install dependencies
pip install -r requirements.txt

# Run the notebook
```

Open the Jupyter Notebook or Google Colab notebook and execute the cells sequentially.

---

## 📌 Future Improvements

* Hyperparameter tuning
* Cross-validation
* Feature selection techniques
* Ensemble learning methods
* Deployment using Flask or Streamlit
* Real-time weather prediction integration

---

## 📜 Conclusion

This project demonstrates how machine learning classification algorithms can be applied to weather data for rainfall prediction. By comparing multiple models and evaluating their performance, the project provides insights into selecting suitable algorithms for binary weather forecasting tasks.

---

### ⭐ If you found this project useful, consider giving the repository a star!
