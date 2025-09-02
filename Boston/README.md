# ML-Projects
# Boston Housing Price Prediction

## 📖 Project Overview

This project predicts housing prices in Boston using a linear regression model based on features like the average number of rooms, percentage of lower status population, and crime rate. The goal is to understand the relationship between these factors and housing prices and build a predictive model.

---

## 🚀 Features Used in the BaseModel.ipynb are three while in other models All deatures we're used to get the most out of our models.

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

<p>The BaseModel achieved an R² score of 0.68 and MSE of 28.67 on the test data.</p>
<p>The Model_1 achieved an R² score of 0.739 and MSE of 23.41 on the test data.</p>
<p>The Model_2 achieved an R² score of 0.85 and MSE of 13.67 on the test data.</p>
<p>The Model_3 achieved an R² score of 0.90 and MSE of 8.48 on the test data.</p>
<p>The Model_4 achieved an R² score of 0.67 and MSE of 22.66 on the test data.</p>
<p>The Model_5 achieved an R² score of 0.80 and MSE of 14.91 on the test data.</p>
<p>The Model_6 achieved an R² score of 0.95 and MSE of 4.34 on the test data.</p>
<p>The Model_7 achieved an R² score of 0.92 and MSE of 6.69 on the test data.</p>
<p>The Model_8 achieved an R² score of 0.92 and MSE of 6.65 on the test data.</p>
<p>The Model_9 achieved an R² score of 0.91 and MSE of 7.96 on the test data.</p>

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
    │   |--  BaseModel.ipynb
    |   |--  Model_1.ipynb
    |   |--  Model_2.ipynb
    |   |--  Model_3.ipynb
    |   |--  Model-4.ipynb
    |   |--  Model_5.ipynb
    |   |____Model_6.ipynb
    ├── requirements.txt
    └── README.md

📞 Contact
Created by Ainebyona Abubaker
GitHub: kenbaker-gif
Email: ainebyonabubaker@proton.me