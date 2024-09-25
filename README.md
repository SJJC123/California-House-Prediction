# California Housing Price Prediction Model
This project aims to predict median housing prices in the U.S. state of California using various machine learning models. The workflow includes comprehensive exploratory data analysis (EDA), data cleaning, feature engineering, and model evaluation.

## Files
Cali_House_ML.ipynb - Jupyter Notebook file containing the code, outputs, and notes for the project

Cali_House_ML.html - An html file of the project for easier viewing on a Google Chrome browser without the need for an IDE

housing.csv - the California Housing dataset that I used for this project. It was obtained from Kaggle and I've attached the link below:

https://www.kaggle.com/datasets/camnugent/california-housing-prices 

## Project Overview:
### Data Exploration and Cleaning:

Conducted EDA to understand the dataset, including distributions and relationships between variables.
Cleaned the data to handle missing values and outliers, ensuring the dataset was ready for modeling.
### Feature Engineering:

Applied log transformation to improve the distribution of housing prices, resulting in better histogram visualizations.
Utilized one-hot encoding to convert categorical variables into binary format (1s and 0s), making them suitable for machine learning models.
Generated new column variables from dataset to find new insights within the data.
### Model Development:

Built and evaluated multiple predictive models, including:

**Linear Regression:** A baseline model to understand linear relationships in the data.

**Random Forest Regressor:** A more complex model to capture non-linear relationships and interactions.
Employed GridSearchCV for hyperparameter tuning, optimizing model performance.
### Model Evaluation:

Used R² score to assess the performance of each model, with the Random Forest Regressor achieving an R² score of 0.81, while the Linear Regression model achieved 0.66.
### Visualizations:

Created heatmaps, scatterplots, and histrograms to illustrate correlations between features, aiding in feature selection and understanding model performance.
### Conclusion:
This project demonstrates the application of machine learning techniques for predicting housing prices, showcasing data preprocessing, model development, and evaluation. The results highlight the effectiveness of methods like Random Forest in regression tasks.
