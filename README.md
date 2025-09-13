# Exploratory Data Analysis (EDA) on Retail Sales Data

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)

---

## 📌 Project Overview
In this project, I worked with a dataset (`menu.csv`) containing nutritional information about McDonald’s menu items.  
The goal is to perform **Exploratory Data Analysis (EDA)** to uncover patterns, trends, and insights that can help understand nutritional characteristics and support data-driven decision-making in retail/food business analysis.

---

## 📂 Dataset
- **Rows:** 260  
- **Columns:** 24  
- **Features:**  
  - **Categorical:** Category, Item, Serving Size  
  - **Numerical:** Calories, Total Fat, Sodium, Protein, Sugars, etc.  

Each row corresponds to a unique food item from the menu.

---

## 🛠️ Data Loading
```python
import pandas as pd

# Load the dataset
df = pd.read_csv('/content/menu.csv')

# Preview the dataset
display(df.head())
display(df.info())
