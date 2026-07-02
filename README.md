# Titanic Survival Prediction – Data Cleaning Project

## 📌 Project Overview

This project focuses on preprocessing and cleaning the Titanic dataset to prepare it for machine learning. The dataset contains passenger information such as age, gender, ticket class, fare, and survival status. The project demonstrates essential data preprocessing techniques, including handling missing values, encoding categorical variables, visualizing data, and exporting the cleaned dataset.

---

## 🎯 Objectives

* Load and explore the Titanic dataset using Pandas.
* Summarize the dataset using `.info()` and `.describe()`.
* Handle missing values using appropriate imputation techniques.
* Encode categorical features for machine learning.
* Visualize the distribution of passenger ages.
* Export the cleaned dataset for future model development.

---

## 🛠️ Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 📂 Dataset

**Dataset:** Titanic Dataset (Kaggle)

The dataset contains passenger details such as:

* PassengerId
* Survived
* Pclass
* Name
* Sex
* Age
* SibSp
* Parch
* Ticket
* Fare
* Cabin
* Embarked

---

## 📋 Project Workflow

### 1. Data Loading

* Imported the Titanic dataset using Pandas.
* Displayed the first few records.

### 2. Data Exploration

* Checked dataset information using `.info()`.
* Generated summary statistics using `.describe()`.
* Identified missing values.

### 3. Data Cleaning

* Filled missing values in the **Age** column using the median.
* Filled missing values in the **Embarked** column using the mode.
* Removed the **Cabin** column due to a large number of missing values.

### 4. Feature Encoding

* Encoded the **Sex** column using LabelEncoder.
* Encoded the **Embarked** column using One-Hot Encoding.

### 5. Data Visualization

* Visualized the age distribution using a histogram with KDE.

### 6. Export

* Saved the cleaned dataset as `Titanic_Cleaned.csv`.

---

## 📊 Features Implemented

* Data Loading
* Data Exploration
* Missing Value Handling
* Label Encoding
* One-Hot Encoding
* Data Visualization
* Dataset Export

---

## 📁 Project Structure

```
Titanic_Data_Cleaning/
│
├── Titanic-Dataset.csv
├── Titanic_Cleaned.csv
├── Titanic_Data_Cleaning.ipynb
├── README.md
```

---

## 🚀 How to Run

1. Clone or download this repository.
2. Open the notebook in Google Colab or Jupyter Notebook.
3. Upload the Titanic dataset.
4. Run all cells sequentially.
5. The cleaned dataset will be generated as `Titanic_Cleaned.csv`.

---
