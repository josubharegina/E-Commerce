# E-Commerce Sales Analytics & Revenue Prediction

## Project Overview

This project focuses on analyzing e-commerce sales data and building a machine learning model to predict revenue generated from customer orders. The project includes data preprocessing, exploratory data analysis (EDA), feature engineering, model building, evaluation, and visualization.

---

## Objective

* Analyze sales trends across product categories and regions.
* Understand customer purchasing patterns.
* Predict order revenue using machine learning.
* Evaluate model performance using regression metrics.

---

## Dataset

The dataset contains **5,000 e-commerce sales records** with information about customer orders.

### Features

* Order ID
* Order Date
* Customer ID
* Product Category
* Region
* Quantity
* Unit Price
* Discount
* Payment Method
* Delivery Days
* Customer Rating

### Target Variable

* Revenue

---

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

---

## Data Preprocessing

The following preprocessing steps were performed:

* Checked dataset information.
* Verified missing values.
* Converted **Order Date** into datetime format.
* Extracted:

  * Year
  * Month
  * Day
  * Day of Week
* Removed the original Order Date column.
* Applied feature scaling using **StandardScaler**.
* Encoded categorical variables using **OneHotEncoder**.
* Built preprocessing pipelines using **ColumnTransformer**.

---

## Exploratory Data Analysis (EDA)

The following visualizations were created:

### 1. Order Distribution Across Product Categories

A count plot showing the number of orders in each product category.

### 2. Average Revenue by Product Category and Region

A heatmap displaying the average revenue generated across different product categories and regions.

---

## Machine Learning Model

### Algorithm Used

**Gradient Boosting Regressor**

### Model Parameters

* n_estimators = 300
* learning_rate = 0.05
* max_depth = 4
* random_state = 42

The preprocessing pipeline and regression model were combined using Scikit-learn's **Pipeline**.

---

## Model Evaluation

The model was evaluated using the following metrics:

| Metric                         | Value      |
| ------------------------------ | ---------- |
| R² Score                       | **0.9993** |
| Mean Absolute Error (MAE)      | **17.07**  |
| Root Mean Squared Error (RMSE) | **22.35**  |

The model achieved an excellent prediction accuracy with an R² score close to **1**, indicating that it explains almost all the variance in the revenue data.

---

## Visualization

An **Actual vs Predicted Revenue** scatter plot was generated to compare the model's predictions against the actual revenue values.

The points closely align with the reference line, demonstrating the model's strong predictive performance.

---

## Project Workflow

1. Import required libraries.
2. Load the dataset.
3. Explore and inspect the data.
4. Perform data preprocessing.
5. Engineer date-based features.
6. Split the dataset into training and testing sets.
7. Build preprocessing pipelines.
8. Train the Gradient Boosting Regression model.
9. Predict revenue on the test dataset.
10. Evaluate model performance.
11. Visualize prediction results.

---


<img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/a3491385-b87f-4342-90bd-176b1da4e658" />
<img width="921" height="590" alt="image" src="https://github.com/user-attachments/assets/3711ae7a-64e3-47b4-a196-d9fb45845212" />



## Conclusion

This project demonstrates how machine learning can be applied to e-commerce sales analytics for accurate revenue prediction. By combining data preprocessing, feature engineering, and the Gradient Boosting Regressor, the model achieved outstanding predictive performance. The project also highlights the importance of exploratory data analysis in understanding customer purchasing behavior and business trends.

---

## Future Enhancements

* Deploy the model using Streamlit or Flask.
* Build an interactive Power BI dashboard.
* Include additional business metrics such as profit and customer lifetime value.
* Experiment with advanced models like XGBoost, LightGBM, or CatBoost.
* Perform hyperparameter tuning to further optimize model performance.

---

## Author

**Subha S M**

**Aspiring Business Analyst | BCA Student**

**Skills:** Python • Pandas • NumPy • Scikit-learn • SQL • Excel • Power BI • Data Visualization • Machine Learning
