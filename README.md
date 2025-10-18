# Titanic Survival Prediction

# Titanic Dataset - Exploratory Data Analysis

## Overview

This project performs exploratory data analysis (EDA) on the famous Titanic dataset from Kaggle. The goal is to understand the data patterns and relationships that might help predict passenger survival.

## Dataset Information

The dataset contains information about Titanic passengers including:

- **PassengerId**: Unique identifier for each passenger
- **Survived**: Survival status (0 = No, 1 = Yes)
- **Pclass**: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
- **Name**: Passenger name
- **Sex**: Gender
- **Age**: Age in years
- **SibSp**: Number of siblings/spouses aboard
- **Parch**: Number of parents/children aboard
- **Ticket**: Ticket number
- **Fare**: Passenger fare
- **Cabin**: Cabin number
- **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## Analysis Summary

### Missing Data Analysis

- Approximately 20% of Age data is missing
- Cabin column has significant missing data (too much for basic imputation)
- Embarked has minimal missing values

### Key Visualizations

1. **Survival Distribution**: Overall count of survivors vs non-survivors
2. **Survival by Gender**: Female passengers had significantly higher survival rates
3. **Survival by Class**: Higher-class passengers (Pclass 1) had better survival chances
4. **Age Distribution**: Histogram showing passenger age distribution
5. **Family Size**: Count of siblings/spouses (SibSp) aboard

## Technologies Used

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Setup and Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/titanic-eda.git

# Navigate to directory
cd titanic-eda

# Install required packages
pip install pandas numpy matplotlib seaborn jupyter

# Launch Jupyter notebook
jupyter notebook
```

## Usage

Open `EDA.ipynb` in Jupyter Notebook and run the cells sequentially to reproduce the analysis.

## Key Findings

- Women and children were given priority during evacuation
- Higher-class passengers had better access to lifeboats
- Family size appears to impact survival chances
- Age distribution shows many young adults aboard

## Next Steps

This EDA serves as foundation for building predictive models (like Logistic Regression) to classify passenger survival.

## License

This project uses the Titanic dataset from Kaggle. Please refer to Kaggle's data usage terms.
