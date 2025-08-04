# Titanic Dataset – Data Cleaning & Preprocessing

This project marks the beginning of my journey into the world of data science and machine learning. I started with one of the most well-known datasets — the Titanic dataset — to learn how to clean, preprocess, and prepare real-world data for analysis and modeling.

---

##  What I Worked On

Here's a breakdown of what I explored and applied:

-  Handling Missing Data
  - Filled missing Age values using the median, which is less sensitive to outliers
  - Replaced missing Embarked values with the most common port
  - Dropped the Cabin column due to a high number of missing entries

-  Encoding Categorical Data
  - Converted Sex into numerical values (0 = male, 1 = female)
  - Applied One-Hot Encoding to Embarked to handle non-numeric categories

-  Feature Scaling
  - Normalized Age and Fare columns to a range between 0 and 1 using MinMaxScaler

-  Outlier Detection
  - Visualized Fare values using boxplots to identify potential outliers
  - Chose to retain them for analysis, as they might represent real-world scenarios

---

##  Why I Did This

The goal was to understand:
- How to prepare raw data for machine learning
- The impact of missing values and different ways to handle them
- How to turn text-based features into numeric values
- Why scaling and normalization are important for ML models

This helped me build a strong foundation for the preprocessing stage — one of the most crucial steps in any data pipeline.

---

## 📁 Files Included

| File | Description |
|------|-------------|
| cleaned_titanic.csv | Cleaned and normalized dataset |
| task1.ipynb | Full preprocessing notebook |
| README.md | This documentation file |

---

## 🛠 Tools Used

- Python 
- Pandas & NumPy
- scikit-learn
- Seaborn & Matplotlib
- Google Colab
