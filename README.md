# elevate-labs-task-03
AI &amp; ML Internship – Task 3: Simple and Multiple Linear Regression

# Task 3: Linear Regression

## AI & ML Internship – Elevate Labs

### Objective
To implement and understand Simple and Multiple Linear Regression using Scikit-learn.

## Dataset
- **Dataset:** Medical Insurance Cost
- **Source:** [Kaggle – Medical Cost Personal Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance)
- **File:** `insurance.csv`
- **Target Variable:** `charges`
- **Initial Records:** 1,338
- **Final Records:** 1,337
- **Features:** age, gender, bmi, children, smoker, region

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## Data Preprocessing
The following preprocessing steps were performed:

1. Loaded and inspected the dataset.
2. Checked for missing values.
3. Identified and removed duplicate records.
4. Converted categorical features into numerical values using One-Hot Encoding.
5. Separated independent variables (X) and the target variable (y).
6. Split the dataset into training (80%) and testing (20%) sets.

## Models Implemented

### 1. Simple Linear Regression
- Used `age` as the independent variable.
- Used `charges` as the target variable.
- Implemented using Scikit-learn's `LinearRegression`.
- Visualized actual values and the regression line.

**Regression Equation:**

Charges = 3534.09 + 242.26 × Age

### 2. Multiple Linear Regression
- Used all eight encoded input features.
- Predicted insurance charges using multiple independent variables.
- Examined the model coefficients and intercept.

## Model Evaluation

Both models were evaluated using:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

### Results

| Metric | Simple Linear Regression | Multiple Linear Regression |
|---|---:|---:|
| MAE | 9657.79 | 4177.05 |
| MSE | 166275348.23 | 35478020.68 |
| R² Score | 0.0951 | 0.8069 |

### Result Interpretation
- Multiple Linear Regression performed better than Simple Linear Regression.
- The multiple regression model achieved an R² score of approximately 0.807.
- This indicates that the model explains approximately 80.69% of the variation in insurance charges on the test dataset.
- The lower MAE and MSE indicate smaller prediction errors compared with the simple regression model.

## Project Structure

- `README.md` – Project documentation
- `insurance.csv` – Dataset
- `Task_3_Linear_Regression.ipynb` – Jupyter Notebook containing implementation
- `Task_3_Linear_Regression_Screenshots.pdf` – Screenshot documentation

## Conclusion
This task demonstrated the implementation of Simple and Multiple Linear Regression using Scikit-learn. The comparison showed that using multiple features produced better prediction performance for the Medical Insurance Cost dataset.

## Internship
**AI & ML Internship – Elevate Labs**
