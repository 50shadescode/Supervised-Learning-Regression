# Supervised-Learning-Regression

Project Overview
This project focuses on applying Machine Learning techniques to solve a specific problem using a structured workflow. The analysis and model building were conducted in Jupyter Notebook.
Dataset
Name: 5G-Energy Consumption
Source: International Telecommunication Union (ITU)
Description: This dataset was provided by the ITU in 2023 as part of a global challenge or competition for data scientists worldwide to solve the 5G energy consumption modeling problem using machine learning techniques.
Size: [Mention number of rows and columns]

Objective
The objective is to build and train a ML model to estimate the energy consumed by different 5G base stations, taking into consideration the impact of various engineering configurations, traffic conditions, and energy-saving methods.
Machine Learning Workflow

Data Exploration:
Checked for missing values
Visualized data distributions
Identified correlations

Data Preprocessing:
Handled missing values
Performed feature engineering
Scaled and transformed data as needed

Feature Selection:
Identified important features
Applied dimensionality reduction if necessary
Model Selection & Training:
Tested multiple algorithms (e.g., Linear Regression, Decision Trees, Random Forest, etc.)
Tuned hyperparameters
Evaluated model performance using appropriate metrics

Model Evaluation:
Compared model accuracy, precision, recall, and other relevant metrics
Performed cross-validation
Model Evaluation Interpretation
The model's performance was assessed using multiple evaluation metrics. The Mean Absolute Error (MAE) of 3.87 indicates that, on average, the model’s predictions deviate by approximately 3.87 units from the actual energy consumption values, suggesting relatively small errors. The Mean Squared Error (MSE) of 27.64 reflects the average squared differences between predicted and actual values, where lower values indicate fewer large deviations. Since MSE is in squared units, the Root Mean Squared Error (RMSE) of 5.26 provides a more interpretable measure, showing that the model’s predictions, on average, deviate by 5.26 units from the actual values.
The R² score of 0.8544 indicates that the model explains approximately 85.44% of the variance in energy consumption, demonstrating strong predictive power. A value closer to 1 suggests that the model effectively captures patterns in the data, while a lower R² would indicate poor explanatory ability.

Overall, the model is performing well, as reflected by its relatively low error values and high R² score. To further improve performance, potential next steps include refining feature engineering, conducting additional hyperparameter tuning, or exploring ensemble modeling techniques.

Technologies Used
Python
Jupyter Notebook
Pandas, NumPy
Scikit-Learn
Matplotlib, Seaborn

Author
Name: 50ShadesCode


