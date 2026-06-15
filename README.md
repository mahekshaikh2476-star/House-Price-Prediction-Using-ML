# 🏠 House Price Prediction using Machine Learning

## 📌 Project Overview

House Price Prediction is a Machine Learning project that estimates residential property prices using housing characteristics such as area, number of bedrooms, bathrooms, parking availability, furnishing status, and other property-related features.

The objective is to build a predictive regression model that can accurately estimate house prices based on historical housing data. This project demonstrates the complete Machine Learning workflow, including data preprocessing, exploratory data analysis, feature engineering, model training, evaluation, and prediction.

---

## 🎯 Problem Statement

Determining the correct market value of a property is challenging because multiple factors influence house prices.

This project aims to:

* Analyze housing data
* Identify important price-driving factors
* Build predictive regression models
* Compare model performance
* Generate accurate house price predictions

---

## 🌍 Industry Relevance

House price prediction systems are widely used by:

* Real Estate Companies
* Property Listing Platforms
* Banks & Mortgage Providers
* Investment Firms
* Property Consultants
* Home Buyers & Sellers

Machine Learning-based valuation systems help organizations make faster and more accurate pricing decisions.

---

## 🚀 Project Objectives

* Perform data cleaning and preprocessing
* Conduct Exploratory Data Analysis (EDA)
* Understand relationships between housing features and price
* Train multiple regression models
* Evaluate model performance using industry-standard metrics
* Predict prices for new properties
* Visualize key insights using charts and graphs

---

## 🛠️ Tech Stack

### Programming Language

* Python

### Libraries Used

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn

### Machine Learning Models

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor

---

## 📂 Dataset Information

The dataset contains various housing-related attributes such as:

| Feature           | Description                     |
| ----------------- | ------------------------------- |
| Area              | Property area in square feet    |
| Bedrooms          | Number of bedrooms              |
| Bathrooms         | Number of bathrooms             |
| Stories           | Number of floors                |
| Parking           | Parking spaces available        |
| Main Road         | Property connected to main road |
| Guest Room        | Guest room availability         |
| Basement          | Basement availability           |
| Air Conditioning  | AC availability                 |
| Preferred Area    | Located in preferred area       |
| Furnishing Status | Furnishing level                |
| Price             | Target variable                 |

Target Variable:

**Price**

---

## 📊 Exploratory Data Analysis

Several visualizations were created to understand housing market trends and feature relationships.

### EDA Visualizations

* House Price Distribution
* Area vs Price
* Bedrooms vs Price
* Bathrooms vs Price
* Stories vs Price
* Parking vs Price
* Furnishing Status vs Price
* Air Conditioning vs Price
* Correlation Heatmap
* Pair Plot Analysis
* Outlier Detection

---

## ⚙️ Machine Learning Workflow

### 1. Data Collection

* Housing dataset loaded into Python environment

### 2. Data Cleaning

* Checked missing values
* Removed duplicates
* Converted categorical variables

### 3. Feature Engineering

* Encoded categorical variables
* Prepared dataset for model training

### 4. Model Training

Three regression models were trained:

#### Linear Regression

Used as baseline model.

#### Decision Tree Regressor

Captures non-linear relationships.

#### Random Forest Regressor

Ensemble model providing higher prediction accuracy.

### 5. Model Evaluation

Models were evaluated using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

---

## 📈 Model Performance

| Model             | MAE | RMSE | R² Score |
| ----------------- | --- | ---- | -------- |
| Linear Regression | XX  | XX   | XX       |
| Decision Tree     | XX  | XX   | XX       |
| Random Forest     | XX  | XX   | XX       |

Replace the values above with your actual results after training.

---

## 🏆 Best Performing Model

Random Forest Regressor achieved the highest predictive performance and was selected as the final model for house price prediction.

---

## 🔍 Feature Importance Analysis

The model identified the following features as major contributors to house prices:

* Area
* Bathrooms
* Bedrooms
* Parking
* Air Conditioning
* Preferred Area
* Furnishing Status

These factors showed the strongest influence on property valuation.

---

## 📸 Project Outputs

### Dataset Preview

Dataset inspection and summary statistics.

### Correlation Analysis

Feature relationship visualization using heatmaps.

### Feature Importance

Identification of key drivers affecting house prices.

### Actual vs Predicted Prices

Model prediction accuracy visualization.

### House Price Prediction

Price estimation for new housing records.

---

## 📁 Project Structure

```text
House-Price-Prediction/
│
├── data/
│   └── Housing.csv
│
├── notebooks/
│   └── House_Price_Prediction.ipynb
│
├── images/
│   ├── 01_House_Price_Distribution.png
│   ├── 02_Area_vs_Price.png
│   ├── 03_Bedrooms_vs_Price.png
│   ├── 04_Bathrooms_vs_Price.png
│   ├── 05_Parking_vs_Price.png
│   ├── 06_Feature_Importance.png
│   ├── 07_Actual_vs_Predicted.png
│   └── 09_Correlation_Heatmap.png
│
├── README.md
├── requirements.txt
└── House_Price_Prediction.ipynb
```

## ▶️ How to Run the Project

### Clone Repository

```bash
git clone https://github.com/mahekshaikh2476-star/House-Price-Prediction.git
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Notebook

Open:

```text
House_Price_Prediction.ipynb
```

Run all cells sequentially.

---

## 📚 Skills Demonstrated

### Data Analysis

* Data Cleaning
* Data Transformation
* Exploratory Data Analysis

### Machine Learning

* Regression Models
* Model Training
* Model Evaluation
* Prediction Systems

### Data Visualization

* Histograms
* Scatter Plots
* Box Plots
* Heatmaps
* Feature Importance Charts

### Tools

* Python
* GitHub
* Scikit-Learn

---

## 🎓 Learning Outcomes

Through this project, I gained practical experience in:

* Real-world Machine Learning workflows
* Regression problem solving
* Data preprocessing techniques
* Model evaluation and comparison
* Data visualization and storytelling
* GitHub project documentation

## 👨‍💻 Author

**Mahek Shaikh**


Focused on building practical projects in Data Analytics, Machine Learning, Business Intelligence, and Predictive Modeling.
