# 🛠️ Predictive Maintenance of Industrial Machinery

This project aims to develop a machine learning-based solution to **predict equipment failures** in industrial machinery using sensor data. It was developed as part of a capstone project for the **Mechanical Engineering Problem Statement No. 39**, and deployed using **IBM Cloud Lite Services**.

## 📌 Problem Statement

> Develop a predictive maintenance model for a fleet of industrial machines to anticipate failures before they occur. Analyze sensor data to identify patterns that precede a failure and build a classification model to predict the type of failure (e.g., tool wear, heat dissipation, power failure).

## 📂 Dataset

- **Source**: [Kaggle Dataset – Predictive Maintenance Classification](https://www.kaggle.com/datasets/shivamb/machine-predictive-maintenance-classification)
- **Features Include**:
  - Air Temperature (K)
  - Process Temperature (K)
  - Rotational Speed (RPM)
  - Torque (Nm)
  - Tool Wear (min)
  - Failure Type (target)

## 💡 Proposed Solution

The proposed system involves the following steps:
1. **Data Collection**: Using the sensor dataset from Kaggle.
2. **Data Preprocessing**: Handling missing values, scaling, encoding target classes.
3. **Model Development**: Training machine learning classifiers such as Random Forest or Decision Tree.
4. **Deployment**: Using IBM Cloud (Watson Studio and Machine Learning) to deploy the trained model as a REST API.
5. **Prediction**: Real-time inference to classify machinery status (e.g., `No Failure`, `Power Failure`, etc.).

## 🧪 Technologies Used

- Python, Pandas, NumPy, Scikit-learn
- IBM Watson Studio
- IBM Cloud Machine Learning Services
- IBM Cloud Object Storage
- Jupyter Notebooks

## 📊 Model Results

- **Prediction Type**: Multiclass Classification
- **Test Predictions**:  
  - Output: `No Failure`  
  - Confidence: 100%
- **Deployment**: Successfully deployed using IBM Cloud; supports JSON and table-based inference


## 🚀 How to Run

1. Clone the repository  
   ```bash
   git clone https://github.com/your-username/predictive-maintenance.git
   cd predictive-maintenance
