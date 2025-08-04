#  Titanic Dataset – Data Cleaning & Preprocessing

This project is a stepping stone into the field of data science and machine learning. Using the iconic Titanic dataset, I focused on learning how to clean, process, and prepare raw data for meaningful analysis and predictive modeling.

## Key Focus Areas

### Missing Data Treatment
* Imputed missing *Age* values using the median to reduce the impact of extreme values
* Filled *Embarked* entries with the most frequent category
* Removed the *Cabin* column due to excessive missing values

### Categorical Data Encoding
* Transformed *Sex* into numerical format (0 = male, 1 = female)
* Used One-Hot Encoding for *Embarked* to convert categories into binary variables

### Feature Scaling
* Applied *MinMaxScaler* to normalize *Age* and *Fare* between 0 and 1 for model readiness

### Outlier Handling
* Explored outliers in *Fare* using boxplots
* Decided to retain them to preserve potential real-world significance

## Learning Outcomes

Through this task, I gained a deeper understanding of:
* Preparing raw datasets for machine learning
* Strategies for handling incomplete data
* Converting text-based data into numerical values
* Importance of scaling features for ML algorithms

These skills form the core of any effective data preprocessing pipeline, setting the stage for model training and evaluation.

## Included Files

| File                      | Description                         |
|---------------------------|-------------------------------------|
| `Cleaned_Titanic_Dataset.csv` | Final version of the cleaned dataset |
| `task1.ipynb`             | Notebook with all preprocessing steps |
| `README.md`               | Project overview and documentation  |

## Tools & Libraries
* Python
* Pandas & NumPy
* Scikit-learn
* Seaborn & Matplotlib
* Google Colab
