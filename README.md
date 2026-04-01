# 🚗 Engine Health Prediction (Predictive Maintenance)

A machine learning project to predict the health condition of automotive engines based on key operational parameters such as engine RPM, oil pressure, fuel pressure, and temperature.

The goal is to enable **predictive maintenance**, helping reduce unexpected failures and improve efficiency in automotive systems.

---

## 🚀 Features

* 📊 Data preprocessing (handling missing values, duplicates, and feature selection)
* 🔍 Exploratory Data Analysis (EDA) using boxplots and statistical insights
* 🤖 Machine Learning model using Random Forest Classifier
* ⚖️ Handles class imbalance for better prediction stability
* 📈 Model evaluation using accuracy, confusion matrix, and classification report
* 📊 Feature importance analysis to identify key influencing factors

---

## 🛠️ Tech Stack

* Python 🐍
* Pandas, NumPy → Data manipulation
* Scikit-learn → Model building & evaluation
* Matplotlib, Seaborn → Data visualization
* Jupyter Notebook

---

## 📂 Project Workflow

### 1️⃣ Data Collection

Dataset (`engine_data.csv`) includes engine parameters such as:

* Engine RPM
* Lubrication Oil Pressure
* Fuel Pressure
* Coolant Temperature
* Lubrication Oil Temperature

Target:

* Engine Condition (0 = Unhealthy, 1 = Healthy)

---

### 2️⃣ Exploratory Data Analysis (EDA)

* Checked missing values and duplicates
* Analyzed statistical distributions
* Used boxplots to compare feature behavior across engine conditions
* Observed that most features have overlapping distributions

---

### 3️⃣ Data Preprocessing

* Removed unnecessary columns
* Split dataset into training and testing (80/20)
* Applied stratified sampling to maintain class balance

---

### 4️⃣ Model Training

* Used **Random Forest Classifier**
* Tuned parameters like:

  * max_depth
  * min_samples_split
  * max_features
---

### 5️⃣ Model Evaluation

Metrics used:

* Accuracy Score
* Confusion Matrix
* Classification Report (Precision, Recall, F1-score)

---

## 📊 Results

* Final Model: Random Forest Classifier
* Accuracy: ~65–68%
* Model performs better for one class due to feature overlap
* Balanced model improves fairness across predictions

---

## 🔍 Key Insights

* Engine RPM is the most important feature
* Other features show overlapping distributions
* Data limitation is the main reason for moderate accuracy
* Feature engineering can significantly improve performance

---

## 🚀 Future Improvements

* Add features like:

  * Engine age
  * Usage hours
  * Load conditions
* Integrate real-time IoT sensor data
* Deploy as a web-based predictive system

---

## 📌 How to Use

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/Engine-Health-Prediction.git
```
