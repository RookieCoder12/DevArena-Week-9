# Model-Evaluation-Report

## CarDefXGB1

### Dataset Summary
- **Number of Samples:** 30000
- **Number of Features:** 25
    - [ID, LIMIT_BAL, SEX, EDUCATION, MARRIAGE, AGE, PAY_0, PAY_2, PAY_3, PAY_4, PAY_5, PAY_6, BILL_AMT1, BILL_AMT2, BILL_AMT3, BILL_AMT4, BILL_AMT5, BILL_AMT6, PAY_AMT1, PAY_AMT2, PAY_AMT3, PAY_AMT4, PAY_AMT5, PAY_AMT6, default.payment.next.month]
<br>
- **Train:Test Split Ratio:** 70:30

### Evaluation Metrics
- **Accuracy :** 0.81
- **Precision :** 0.79
- **Recall :** 0.81
- **F1-score :** 0.76
- **Confusion Matrix :**
    -  [[3514   69]<br>
        [ 818  188]]

### Evaluation Metrics
The model performs well and provides meaningful predictions, but there is clear potential for improvement. Enhancing the dataset (more data, better feature engineering) and applying further hyperparameter tuning could significantly improve accuracy and reliability.

## house_price_prediction

### Dataset Summary
- **Number of Samples:** 1000
- **Number of Features:** 8
    - [Square_Footage, Num_Bedrooms, Num_Bathrooms, Year_Built, Lot_Size, Garage_Size, Neighborhood_Quality, House_Price]
<br>
- **Train:Test Split Ratio:** 70:30

### Evaluation Metrics
- **Mean Absolute Error (MAE) :** 8042.46
- **Mean Squared Error (MSE) :** 100639938.75
- **R² Score :** 1.0