# Car-Price-Prediction-using-Lasso-Regression
## 📄 Overview
This project involves predicting car prices using a **Lasso Regression** model. The dataset contains information about various car attributes, such as manufacturing year, selling price, present price, kilometers driven, fuel type, seller type, transmission type, and ownership history. The primary objective is to build a predictive model that reduces overfitting while achieving high accuracy in price prediction.

---

## 🛠️ Workflow
1. **Data Preprocessing:**
   - Loaded the dataset and analyzed its structure.
   - Checked for missing values (none were found).
   - Performed feature encoding for categorical variables:
     - `Fuel_Type`: Petrol → 0, Diesel → 1, CNG → 2
     - `Seller_Type`: Dealer → 0, Individual → 1
     - `Transmission`: Manual → 0, Automatic → 1

2. **Feature Engineering:**
   - Separated features (`X`) and target variable (`y`).
   - Dropped unnecessary columns such as `Car_Name`.

3. **Splitting the Dataset:**
   - Split the data into training (90%) and testing (10%) sets using `train_test_split`.

4. **Model Training:**
   - Trained a **Lasso Regression** model on the training dataset.
   - Calculated R² score for training and test sets to evaluate the model's performance.

5. **Visualization:**
   - Visualized actual vs predicted prices for both training and test datasets using scatter plots.

---

## 🧰 Technologies Used
- **Python Libraries:**
  - `pandas` for data manipulation.
  - `numpy` for numerical computations.
  - `matplotlib` and `seaborn` for visualization.
  - `scikit-learn` for model training and evaluation.

---

## 📊 Results
- **Training Set:**
  - R² Score: **0.84**
  - Visualization: Red scatter plot of actual vs predicted values.
  
- **Test Set:**
  - R² Score: **0.87**
  - Visualization: Blue scatter plot of actual vs predicted values.



## 🔍 Key Insights
- Lasso Regression effectively reduced overfitting while maintaining high predictive accuracy.
- Encoded categorical variables like fuel type, seller type, and transmission were significant in improving the model’s performance.
- Scatter plots indicate a strong correlation between actual and predicted car prices.

Dataset (car data.xls):
https://github.com/Parththapliyal/Car-Price-Prediction-using-Lasso-Regression/blob/main/car%20data.xls

Jupyter Notebook (car predicton with lasso.ipynb):
https://github.com/Parththapliyal/Car-Price-Prediction-using-Lasso-Regression/blob/main/car%20predciton%20with%20lasso.ipynb

PDF Documentation (lasso.pdf):
https://github.com/Parththapliyal/Car-Price-Prediction-using-Lasso-Regression/blob/main/lasso.pdf


