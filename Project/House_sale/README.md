# House Sales Data Visualization Project

🚀 **By Mulkesh Sharma**

This project is a **data analysis and visualization tool** for house sales data from a city or town in the USA. It leverages Python to preprocess data, explore patterns, and create meaningful insights with the help of **Matplotlib**, **Seaborn**, and **Scikit-learn**. 📊🏠

---

## 📌 Features
- ✅ **Data Cleaning & Preprocessing** using Pandas and Scikit-learn pipelines
- ✅ **Exploratory Data Analysis (EDA)** with Matplotlib & Seaborn
- ✅ **Data Visualizations** for trends, correlations, and feature relationships
- ✅ **Predictive Analysis** with Linear Regression using Scikit-learn
- ✅ **Feature Importance Analysis** to highlight key factors influencing house prices

---

## 🚀 Installation

1. Clone this repository:
   ```sh
   git clone <your-repo-url>
   cd House_Sales_Data_Visualization
   ```
2. Install required dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Launch Jupyter Notebook:
   ```sh
   jupyter notebook
   ```

---

## 📊 Project Overview

### 🔹 **Objective**
This project aims to **analyze house sales data** to identify trends, correlations, and key factors influencing house prices. Through **data visualization** and **machine learning**, it provides insights into the housing market for better decision-making.

### 🔹 **Dataset**
- The dataset consists of **house sales data** such as `price`, `size`, `location`, `bedrooms`, and `bathrooms`.
- Data is processed with **Pandas & Scikit-learn** for efficient analysis and machine learning.

### 🔹 **Key Features**
✅ **Data Transformation** – Using Scikit-learn pipelines to preprocess data.  
✅ **Correlation Analysis** – Visualizing relationships between numerical attributes using Seaborn heatmaps.  
✅ **EDA** – Distribution of prices, square footage, and other key metrics.  
✅ **Regression Models** – Predicting house prices with Scikit-learn's linear regression module.  
✅ **Visual Analysis** – Stunning bar plots, scatter plots, and line charts to explore data insights.

---

## 🔧 Sample Code Snippet
```python
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt
from sklearn.pipeline import Pipeline
from sklearn.preprocessing import StandardScaler
from sklearn.linear_model import LinearRegression

# Load dataset
df = pd.read_csv("house_sales_data.csv")

# Preprocessing pipeline
pipeline = Pipeline([
    ('scaler', StandardScaler()),
    ('regressor', LinearRegression())
])

# Visualize correlations
sns.heatmap(df.corr(), annot=True)
plt.show()
```

---

## 💡 Usage
- Open the Jupyter Notebook or Python script.
- Run the code to process data, perform EDA, and generate visualizations.
- Explore insights interactively and customize as needed.

---

## 📦 Dependencies
- Python >= 3.x
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📈 Visual Representation
Using **Matplotlib** and **Seaborn**, the following visualizations are generated:
📈 **Line Charts** – House price trends over time or across neighborhoods.  
📊 **Bar Graphs** – Sales volume by regions or price ranges.  
📉 **Scatter Plots** – Correlations between house size and price.  

---

## 👨‍💻 Author
### **Mulkesh Sharma**
