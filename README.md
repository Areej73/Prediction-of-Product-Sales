# Prediction of Product Sales
![Prediction of Product Sales](your-image-url)![prediction of product sales](https://github.com/user-attachments/assets/7ea57af2-761f-4779-818b-607ca554ccca)

This repository contains a project focused on predicting sales for various products sold across multiple outlets. The goal is to analyze historical sales data and apply machine learning techniques to forecast future sales. This project demonstrates a range of data analysis, feature engineering, and modeling techniques in Python, from exploratory data analysis (EDA) to model building.

## Project Overview

This project aims to explore, analyze, and predict product sales based on a dataset consisting of different product features and outlet attributes. The dataset includes information on item type, weight, visibility, outlet size, and other key characteristics that might influence sales.

The project is structured in several parts:

1. **Data Cleaning and Preprocessing**: Handling missing values, outliers, and incorrect data entries.
2. **Exploratory Data Analysis (EDA)**: Visualizing key trends and relationships between variables.
3. **Feature Engineering**: Creating and modifying features to improve model performance.
4. **Modeling**: Training machine learning models to predict sales and comparing their performances.
5. **Evaluation**: Assessing model performance using various evaluation metrics.

## Data

The dataset used in this project contains the following key features:
![prediction of product sales](https://github.com/user-attachments/assets/da339dba-5f81-4a12-b70c-37c64e77b920)

- `Item_Identifier`: Unique product code.
- `Item_Weight`: Weight of the product.
- `Item_Fat_Content`: Indicates whether the product is low-fat or regular.
- `Item_Visibility`: Percentage visibility of the product in-store.
- `Item_Type`: Category of the product.
- `Item_MRP`: Maximum retail price of the product.
- `Outlet_Identifier`: Unique store code.
- `Outlet_Establishment_Year`: The year when the store was established.
- `Outlet_Size`: Size of the store (small, medium, high).
- `Outlet_Location_Type`: Type of store location (urban, suburban, rural).
- `Outlet_Type`: Type of store (grocery, supermarket, etc.).
- `Item_Outlet_Sales`: Sales of the product in the store (target variable).

### Data Preprocessing

Several columns had missing values in the original dataset:
- **Item_Weight**: Missing values were imputed based on the most frequent values (mode) for each `Item_Identifier`.
- **Outlet_Size**: Missing values were imputed based on the mode of `Outlet_Size` within each `Outlet_Identifier`.

### Feature Engineering

Features were engineered to enhance model performance:
- **New Categories**: Grouped similar products under new categories.
- **Interaction Features**: Created features representing interactions between item visibility and outlet size, item type, and outlet type.

## Exploratory Data Analysis (EDA)

The following visualizations were created to understand the data better:
- **Histograms** and **Boxplots**: To inspect the distribution and spread of continuous variables.
- **Countplots**: To examine the frequency of categorical variables.
- **Heatmaps**: To analyze the correlation between different features and identify potential multicollinearity.

## Machine Learning Models

Several models were trained and evaluated:
- **Linear Regression**: A baseline model to predict sales based on the features.
- **Decision Trees**: A model capturing non-linear relationships in the data.
- **Random Forest**: An ensemble model to improve performance by reducing overfitting.
- **XGBoost**: A gradient boosting model used to enhance predictive accuracy.

## Evaluation

Model performance was assessed using the following metrics:
- **Root Mean Squared Error (RMSE)**: To measure the error between predicted and actual sales.
- **R-squared**: To evaluate the proportion of variance explained by the model.

## Conclusion

This project explored various factors influencing product sales and applied machine learning models to predict future sales. Through rigorous data preprocessing, feature engineering, and model evaluation, the project showcases the end-to-end process of building a predictive model in Python.

## How to Run

1. Clone the repository:

    ```bash
    git clone https://github.com/Areej73/Prediction_of_Product_Sales.git
    ```

2. Open the Google Colab notebook by following this [link](https://colab.research.google.com).

3. Run the notebook cells step by step to explore the data, train models, and analyze the results.

## Contact

For questions or inquiries, feel free to reach out to me on [LinkedIn](https://www.linkedin.com/in/areej-taha-373628292) or check out my [GitHub](https://github.com/Areej73).

