# Bengaluru-House-Price-Prediction  🏠


 # This project provides a machine learning solution to predict property prices in Bengaluru, India. It demonstrates a full data science pipeline, from raw data cleaning to model evaluation.

# 📁 Files in this Repository
bengaluru-house-price-prediction.ipynb: The core Jupyter Notebook with data exploration, outlier removal, and model building.

Bengaluru_House_Data.csv: The raw dataset containing property features and prices.

Interview_Answer.pdf: Documentation explaining technical concepts and project decisions.



# 🛠️ Project Workflow
Data Cleaning: Handled missing values and standardized the 'size' column.

Outlier Detection: Used business logic (price per sqft, bedroom-to-area ratio) to remove data points that would skew the model.

Dimensionality Reduction: Tagged locations with few data points as 'Other' to improve model performance.

Model Building: Evaluated multiple algorithms including Linear Regression, Lasso, and Decision Trees using GridSearchCV.

# 🚀 Technologies Used
Python

Pandas / NumPy

Matplotlib / Seaborn

Scikit-Learn
