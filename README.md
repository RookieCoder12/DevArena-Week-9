# DevArena-Week-9

## Overview
This project applies machine learning techniques to solve two predictive problems: car defect classification and house price estimation. The workflow includes data preprocessing, exploratory analysis, feature engineering, model training, and evaluation.
Using Python libraries such as Pandas, Scikit-learn, the project develops a classification model to identify car defects and a regression model to estimate housing prices based on key features. The process involves handling missing values, encoding categorical variables, and optimizing model performance.
Model effectiveness is evaluated using metrics such as accuracy, precision, and recall for classification, and Mean Absolute Error (MAE), Mean Squared Error (MSE), and R² for regression. Overall, the project demonstrates the practical application of both classification and regression techniques to generate data-driven predictions.

## Files
- `CarDefXGB1.ipynb` - <b>Python notebook file</b> that contains code and analysis for logistic regression model.
- `house_data.csv` - <b>CSV file</b> that contains the raw data that will be used in the linear regression model for price prediction model.
- `house_price_prediction.ipynb` - <b>Python Notebook file</b> that contains code and analysis for linear regression model.
- `model_evaluation_report.md` - <b> </b> .
- `prediction_vs_actual_linear_regression.png` - Contains the photo of the graph that compares actual vs predicted.
- `prediction_vs_actual.png` - 
- `README.md` - This file.
- `requirements.txt` - Consist of <b>Python libraries</b> required for this project.
- `UCI_Credit_Card.csv` - <b>CSV file</b> that contains the raw data that will be used in the logistic regression model for customer classification model.

## Getting Started

### Prerequisites
Ensure you have Python 3.x installed on your system.

### Cloning Repository
Cloning the repository:
```zsh
git clone https://github.com/RookieCoder12/DevArena-Week-9.git    
```

### Installation
Install the required dependencies:
```zsh
pip install -r requirements.txt
```

### Running the Project

#### Running the Python Notebook
1. Run jupyter notebook:
```zsh
jupyter notebook
```
2. Open ```CarDefXGB1.ipynb```, Open ```house_price_prediction.ipynb```.

## Structure     
In this project, a structured machine learning workflow was implemented using Python to develop predictive models for car defect classification and house price estimation.<br>

During the preprocessing phase, both datasets were cleaned and prepared by handling missing values, encoding categorical variables, and ensuring appropriate data types. Feature engineering techniques were applied to improve model input quality and capture relevant patterns in the data.<br>

The analysis begins with Exploratory Data Analysis (EDA), where key relationships, distributions, and correlations between variables were examined to understand underlying data patterns and identify influential features.<br>

For the car defect dataset, a classification approach was implemented using XGBoost, leveraging its ability to model complex non-linear relationships and interactions between features. The model was trained and optimized to accurately classify defect occurrences..<br>

For the house price dataset, regression techniques were applied to predict continuous target values. Feature scaling and transformation were used where necessary to improve model performance and ensure better generalization.<br>

Model evaluation was carried out using appropriate performance metrics. Classification performance was assessed using accuracy, precision, recall, and confusion matrix, while regression performance was evaluated using Mean Absolute Error (MAE), Mean Squared Error (MSE), and R² score.<br>

Overall, this project integrates data preprocessing, exploratory analysis, machine learning modeling, and performance evaluation to build reliable predictive systems and demonstrate the practical application of both classification and regression techniques.