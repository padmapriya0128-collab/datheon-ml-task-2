# Real Estate Housing Price Prediction

## Datheon Machine Learning & Data Science Internship — Task 2

### Project Overview
This project predicts median house values using machine learning regression techniques on a housing dataset. It compares Ordinary Least Squares (OLS) Linear Regression, Ridge Regression, and Lasso Regression.

### Objectives
- Explore and analyze the housing dataset.
- Handle missing values using imputation.
- Perform feature engineering to create additional predictive features.
- Apply numerical scaling and categorical encoding where needed.
- Train and evaluate multiple regression models.
- Tune Ridge and Lasso hyperparameters using GridSearchCV.
- Compare model performance using RMSE, MAE, and R².
- Visualize predictions and analyze residual errors.

### Models Implemented
1. **OLS Linear Regression** — baseline regression model.
2. **Ridge Regression** — applies L2 regularization.
3. **Lasso Regression** — applies L1 regularization.

### Evaluation Metrics
- **RMSE:** Root Mean Squared Error.
- **MAE:** Mean Absolute Error.
- **R² Score:** Coefficient of determination.

### Technologies Used
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook

### Project Files
- `housing.csv` — dataset used for analysis.
- `housing_price_prediction.ipynb` — notebook containing data analysis, feature engineering, model training, evaluation, and visualizations.
- `model_comparison.csv` — comparison of regression model metrics.

### How to Run
1. Clone or download this repository.
2. Install Python 3.11 or a compatible Python version.
3. Install the required libraries:

   ```bash
   python -m pip install pandas numpy matplotlib seaborn scikit-learn jupyter ipykernel
   ```

4. Open `housing_price_prediction.ipynb` in VS Code or Jupyter Notebook.
5. Ensure `housing.csv` is in the same folder.
6. Run the notebook cells in order.

### Results
The notebook compares OLS, Ridge, and Lasso regression using test-set RMSE, MAE, and R² scores. The model with the lowest RMSE is selected for the prediction and residual visualizations. Actual results are available in `model_comparison.csv`.

### Internship
Project completed as part of Task 2 of the Datheon Machine Learning & Data Science Internship.