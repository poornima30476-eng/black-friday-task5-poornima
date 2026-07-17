# Black Friday Sales Prediction

A Machine Learning project that predicts customer purchase amounts during Black Friday sales using demographic and product information.

## Features
- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Feature encoding
- Missing value handling
- Model training and evaluation
- Purchase amount prediction

## Dataset
- Source: Analytics Vidhya Black Friday Dataset
- Records: 537,577
- Features: User ID, Product ID, Gender, Age, Occupation, City Category, Stay in Current City Years, Marital Status, Product Categories, Purchase
- Target: **Purchase Amount**

## Models
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- XGBoost Regressor

## Evaluation Metric
- Root Mean Squared Error (RMSE)

## Requirements

```bash
pip install numpy pandas matplotlib seaborn scikit-learn xgboost
```

## Run

```bash
python black_friday_sales_prediction.py
```

or

```bash
jupyter notebook black_friday_sales_prediction.ipynb
```

## Workflow
1. Load dataset
2. Perform EDA
3. Handle missing values
4. Encode categorical features
5. Split train and test data
6. Train regression models
7. Evaluate using RMSE
8. Predict purchase amounts

## Results
Among the tested models, **XGBoost Regressor** achieved the best performance with the lowest RMSE.

## Author
Machine Learning project developed using Python, Pandas, Scikit-learn, and XGBoost.