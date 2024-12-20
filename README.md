# Model Performance Evaluation for Fuel Cell Performance Data

## My Roll Number:
- **Roll Number:** 102203781

For this task, I used **Target2** 
---

## Steps Followed:
### 1. **Data Preprocessing:**
   - The dataset was filtered to select **Target2**, as per the given roll number criteria (my roll number ends with **1**).
   - The dataset was then divided into **70% training data** and **30% test data** to ensure the model could generalize well.

### 2. **Modeling with PyCaret:**
   - To streamline the process of model selection, I used **PyCaret**, a low-code machine learning library. 
   
   - **PyCaret Setup:** I initialized the **regression** module of PyCaret to set up the model environment and prepare the data for multiple model comparisons.
   - **Model Comparison:** PyCaret automatically compared several regression models, including Linear Regression, Random Forest, Decision Tree, and others.
   - After comparing the models, **Linear Regression** emerged as the best model based on its performance metrics, including **R2 score** and **RMSE**.

### 3. **Model Evaluation:**
   After selecting Linear Regression, I evaluated its performance using the following metrics:
---

## 1. **Mean Absolute Error (MAE): 0.125**
   - **Definition:** MAE measures the average magnitude of errors in a set of predictions, without considering their direction (whether over or under predictions). It gives the average absolute difference between predicted values and actual values.
   - **Interpretation:** The model's predictions, on average, are off by 0.125 units. A lower MAE indicates better model performance. In this case, the error is relatively small, suggesting the model is fairly accurate.

## 2. **Mean Squared Error (MSE): 0.0248**
   - **Definition:** MSE calculates the average of the squared differences between the predicted and actual values. Unlike MAE, MSE penalizes larger errors more heavily due to the squaring of the differences.
   - **Interpretation:** The model's MSE of 0.0248 indicates that, on average, the squared error between predicted and actual values is quite small. A smaller MSE suggests fewer large prediction errors, demonstrating the model’s reliability in making accurate predictions.

## 3. **Root Mean Squared Error (RMSE): 0.1576**
   - **Definition:** RMSE is the square root of the MSE and brings the error back to the original units of the target variable, providing a more interpretable measure of the model's prediction error.
   - **Interpretation:** The RMSE value of 0.1576 indicates that the model's average error is approximately 0.16 units. This is a strong indicator of accuracy, as smaller RMSE values reflect better predictive performance.

## 4. **R2 Score: 0.9156**
   - **Definition:** The R2 score measures the proportion of the variance in the target variable that is explained by the model. It ranges from 0 to 1, where 1 indicates perfect prediction and 0 means the model performs no better than simply predicting the mean.
   - **Interpretation:** With an R2 score of 0.9156, the model explains about **91.56%** of the variability in the target data. This high value reflects a strong model fit, where the model accounts for nearly all of the variance in the target variable.

---

## Conclusion:
- The **R2 score of 0.9156** indicates that the model explains a high percentage of the target variable’s variability.
- The **MAE of 0.125**, **MSE of 0.0248**, and **RMSE of 0.1576** show that the model's predictions are quite accurate with relatively small errors.
- **Linear Regression** proved to be the best model based on performance metrics after comparing multiple models using **PyCaret**.

These metrics suggest that the model performs very well and provides reliable predictions with a high degree of accuracy.


