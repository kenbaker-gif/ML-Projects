# ML-Projects
# Boston Housing Price Prediction

## 📖 Project Overview

This project predicts housing prices in Boston using a linear regression model based on features like the average number of rooms, percentage of lower status population, and crime rate. The goal is to understand the relationship between these factors and housing prices and build a predictive model.

---

## 🚀 Features Used

- **RM**: Average number of rooms per dwelling  
- **LSTAT**: Percentage of lower status population  
- **CRIM**: Per capita crime rate by town  

---

## 🛠️ Technologies & Libraries

- Python 3.x  
- pandas  
- numpy  
- scikit-learn  
- seaborn  
- matplotlib  

---

## 🔍 Data Description

The dataset contains information collected from the Boston area housing market. The target variable is:

- **MEDV**: Median value of owner-occupied homes in $1000's

The dataset includes multiple features describing various aspects of the houses and their neighborhoods.

---

## 🧩 How to Use

1. Clone the repository:

   ```bash
   git clone https://github.com/kenbaker-gif/ML-Projects.git
   cd ML-Projects/Boston

📊 Results

The linear regression model achieved an R² score of 0.68 and MSE of 28.67 on the test data.

Key coefficients:

RM: Positive correlation with housing price

LSTAT: Negative correlation with housing price

CRIM: Negative correlation with housing price

🧠 Insights
Houses with more rooms tend to have higher prices.

Neighborhoods with higher crime rates or higher percentages of lower status populations tend to have lower housing prices.

The model can be used to estimate prices for new data based on these features.

## Project Structure
ML-Projects/
└── Boston/
    ├── data/
    │   ├── train.csv
    │   └── test.csv
    ├── notebooks/
    │   └── Boston_Housing_Prediction.ipynb
    ├── requirements.txt
    └── README.md

📞 Contact
Created by Ainebyona Abubaker
GitHub: kenbaker-gif