# Model Performance Evaluation for Fuel Cell Performance Data

## My Roll Number:
- **Roll Number:** 102203781
- **Target Used:** Target2 (Roll Numbers ending with 1 or 6)

---

## Steps Followed:

### 1. **Data Preprocessing:**
   - Filtered the dataset to select **Target2** based on my roll number (ends with 1).
   - Split the data into **70% training** and **30% testing**.

### 2. **Modeling with PyCaret:**
   - Used **PyCaret** to compare multiple regression models (e.g., Linear Regression, Random Forest, Decision Tree).
   - **Linear Regression** was chosen as the best model based on its performance.

### 3. **Model Evaluation:**
   - **Mean Absolute Error (MAE):** 0.125 (average error of 0.125 units).
   - **Mean Squared Error (MSE):** 0.0248 (indicates minimal large prediction errors).
   - **Root Mean Squared Error (RMSE):** 0.1576 (error of 0.16 units, showing good accuracy).
   - **R2 Score:** 0.9156 (model explains **91.56%** of the variance in the target data).

---

## Conclusion:
- The **Linear Regression** model performed well with an **R2 score of 0.9156** and relatively low error metrics.
- The model provides accurate and reliable predictions with a high degree of accuracy, making it the best model after comparison using **PyCaret**.
