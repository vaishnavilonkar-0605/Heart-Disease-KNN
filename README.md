# ❤️ Heart Disease Prediction using K-Nearest Neighbors (KNN)

## 📌 Project Overview

This project focuses on predicting the likelihood of heart disease using the **K-Nearest Neighbors (KNN)** Machine Learning algorithm.

The project includes:

* Data preprocessing
* Exploratory Data Analysis (EDA)
* Feature scaling
* Model training using KNN
* Elbow Method for selecting optimal K value
* Model evaluation using classification metrics

The goal is to build a classification model that can predict whether a patient has heart disease based on various medical attributes.

---

## 📂 Dataset Information

The dataset used in this project:

**File Name:** `Heart Prediction Quantum Dataset.csv`

### Features in Dataset

* Age
* Gender
* Blood Pressure
* Cholesterol
* Heart Rate
* Diabetes
* Smoking
* Obesity
* Exercise Hours
* Stress Level
* Blood Sugar
* Family History
* And other health-related attributes

### Target Variable

* `HeartDisease`

  * `0` → No Heart Disease
  * `1` → Heart Disease Present

---

## 🛠️ Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 📊 Exploratory Data Analysis (EDA)

The project performs detailed EDA using:

* Distribution plots
* Boxplots
* Correlation heatmap
* Statistical summaries
* Missing value checks
* Duplicate value checks

### Visualizations Included

* Feature distribution analysis
* Outlier detection using boxplots
* Correlation heatmap between variables
* Elbow Method graph for K selection

---

## ⚙️ Machine Learning Workflow

### 1️⃣ Data Loading

The dataset is loaded using Pandas.

### 2️⃣ Data Cleaning

* Checked for null values
* Checked for duplicate records

### 3️⃣ Feature Selection

Separated:

* Independent variables (`X`)
* Target variable (`y`)

### 4️⃣ Feature Scaling

Used `StandardScaler` to standardize the dataset.

### 5️⃣ Train-Test Split

Dataset split into:

* 80% Training Data
* 20% Testing Data

### 6️⃣ Model Training

Implemented:

* `KNeighborsClassifier`
* Euclidean distance metric

### 7️⃣ Optimal K Selection

Used the **Elbow Method** to identify the best K value.

### 8️⃣ Model Evaluation

Evaluated using:

* Accuracy Score
* Classification Report

---

## 🤖 K-Nearest Neighbors (KNN)

KNN is a supervised machine learning algorithm used for classification problems.

It classifies a new data point based on the majority class among its nearest neighbors.

### Distance Metric Used

* Euclidean Distance

---

## 📈 Results

* Successfully trained a KNN classification model.
* Applied feature scaling to improve model performance.
* Used Elbow Method to choose the optimal number of neighbors.
* Generated classification metrics for model evaluation.

---

## 🚀 How to Run the Project

### Clone the Repository

```bash
git clone https://github.com/vaishnavilonkar-0605/Heart-Disease-KNN.git
```

### Navigate to Project Folder

```bash
cd Heart-Disease-KNN
```

### Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Run Jupyter Notebook

```bash
jupyter notebook
```

Open:

```bash
KNN heart disease prediction.ipynb
```

Run all cells step by step.

---

## 📁 Project Structure

```bash
Heart-Disease-KNN/
│
├── Heart Prediction Quantum Dataset.csv 
├── KNN heart disease prediction.ipynb
├── README.md
```

---

## 🎯 Future Improvements

* Hyperparameter tuning
* Cross-validation
* Model deployment using Streamlit or Flask
* Compare KNN with other ML algorithms
* Improve prediction accuracy

---

## 🙋‍♀️ Author

### Vaishnavi Lonkar

* GitHub: [https://github.com/vaishnavilonkar-0605](https://github.com/vaishnavilonkar-0605)

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!
