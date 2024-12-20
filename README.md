# Model Performance Evaluation for Fuel Cell Performance Data

## My Roll Number:
- **Roll Number:** 102203781
- **Target Used:** Target2

---

## Steps Followed:

### 1. **Data Preprocessing:**
   - Filtered the dataset to select **Target2** based on my roll number (ends with 1).
   - Split the data into **70% training** and **30% testing**.

### 2. **Modeling with PyCaret:**
   - Used **PyCaret** to compare multiple regression models (e.g., Linear Regression, Random Forest, Decision Tree).
   - **Linear Regression** was chosen as the best model based on its performance.

### 3. **Model Evaluation:**

| Metric                | Value      | Pre-requisite Definition                                                                                 |
|-----------------------|------------|-----------------------------------------------------------------------------------------------------------|
| **Mean Absolute Error (MAE)** | 0.125      | Measures the average absolute difference between predicted and actual values. Lower MAE indicates better accuracy. |
| **Mean Squared Error (MSE)**  | 0.0248     | Measures the average squared difference between predicted and actual values. Smaller MSE indicates fewer large errors. |
| **Root Mean Squared Error (RMSE)** | 0.1576     | The square root of MSE, giving the error in the original units of the target variable. Lower RMSE indicates better model accuracy. |
| **R2 Score**           | 0.9156     | The proportion of variance in the target variable explained by the model. Values closer to 1 indicate better model fit. |

![download (1)](https://github.com/user-attachments/assets/b6a0e554-d777-4809-98f1-c88303d0d360)
- The residual plot shows:
  1. **Scatterplot (Left):** Residuals (errors) vs. predicted values. Residuals close to zero indicate good predictions, though slight patterns may suggest bias.
  2. **Histogram (Right):** Residuals are roughly normally distributed, centered around zero.
  3. **Performance:** High R2 values (Train: 0.918, Test: 0.913) indicate the model explains most of the variance and generalizes well.
---

# Code-flow

1. **Install and Import Libraries**

2. **Load and Display Data**

3. **Set up the Regression Environment**

4. **Model Comparison**

5. **Finalizing Models**

6. **Make Predictions**

7. **Model Saving**

8. **Load and Predict**

9. **Metrics Calculation**

10. **Plot Residuals**

11. **Download Model**

---

## Conclusion:
- The **Linear Regression** model performed well with an **R2 score of 0.9156** and relatively low error metrics.
- The model provides accurate and reliable predictions, making it the best model after comparison using **PyCaret**.



