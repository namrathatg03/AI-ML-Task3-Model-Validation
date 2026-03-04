# AI & ML Task 3 – Model Validation, Overfitting Control & Hyperparameter Tuning

## Project Overview
This project demonstrates how to detect and control overfitting in machine learning models using cross-validation and hyperparameter tuning.

The California Housing Dataset was used to build a house price prediction model. Multiple regression models were evaluated and compared to select the best-performing model.

## Dataset
The dataset used in this project is the **California Housing Dataset**, which contains information collected from the 1990 U.S. Census.

Features include:
- Median Income
- House Age
- Average Rooms
- Average Bedrooms
- Population
- Average Occupancy
- Latitude
- Longitude

Target variable:
- House Price

## Machine Learning Workflow
The following steps were performed:

1. Data Loading
2. Data Preprocessing
3. Feature Scaling
4. Train-Test Split
5. Overfitting Detection
6. Cross Validation
7. Hyperparameter Tuning using GridSearchCV
8. Model Evaluation
9. Model Comparison
10. Final Model Selection

## Models Used
The following regression models were implemented:

- Linear Regression
- Ridge Regression
- Decision Tree Regression (Tuned)

## Evaluation Metrics
Model performance was evaluated using:

- RMSE (Root Mean Squared Error)
- R² Score

## Key Results
The tuned Decision Tree model achieved the best performance after hyperparameter tuning using GridSearchCV.

Key results:

- RMSE ≈ 0.645
- R² ≈ 0.682

This indicates that the optimized model explains approximately **68% of the variance in house prices**.

## Project Files

Repository contains:

- `AI_ML_Task3_Model_Validation_Tuning.ipynb` → Jupyter Notebook implementation
- `AI_ML_Task3_Report.pdf` → Project report
- `README.md` → Project overview

## Tools & Libraries
The project was implemented using:

- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Conclusion
This project demonstrates the importance of proper model validation techniques. Overfitting was successfully detected and controlled using cross-validation and hyperparameter tuning, leading to improved model reliability and performance.
