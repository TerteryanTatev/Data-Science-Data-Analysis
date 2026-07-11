# Predictive Modeling: Linear Regression

This folder contains the Machine Learning phase of the pipeline, focusing on building and evaluating predictive regression models using structured dataset features.

## Implementation Workflow
* **Data Splitting:** Partitioning the dataset into training (80%) and testing (20%) subsets using `train_test_split` to ensure unbiased model evaluation and prevent overfitting.
* **Model Training:** Fitting a classical `LinearRegression` model from Scikit-Learn to map the linear relationship between independent features and the continuous target variable.
* **Performance Evaluation:** Quantifying the model's predictive accuracy using standard regression metrics.

##  Evaluation Metrics Explained
* **RMSE (Root Mean Squared Error):** Measures the average magnitude of the prediction error. Lower values indicate better fit.
* **R² Score (Coefficient of Determination):** Indicates the proportion of variance in the dependent variable that is predictable from the independent variables. Closer to 1.0 (100%) implies an excellent fit.

##  Technologies Used
* **Python 3**
* **Scikit-Learn:** For train-test splitting, model instantiation, and validation metrics.
* **NumPy & Pandas:** For mathematical conversions and array manipulation.
