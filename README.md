# Algerian Fire Weather Index (FWI) Analysis and Prediction

## Project Overview
This project focuses on analyzing and modeling the **Fire Weather Index (FWI)** using the Algerian Forest Fire dataset. The goal is to explore the meteorological factors affecting fire occurrence and develop machine learning models to predict FWI. The notebook includes data preprocessing, visualization, and the application of various regression models.

## Steps Performed
1. **Data Loading and Preprocessing**
   - Handled missing values, outliers, and scaled numerical features.
   - Properly formatted and categorized relevant features.

2. **Exploratory Data Analysis (EDA)**
   - Visualized relationships between variables such as temperature, relative humidity, wind speed, and rain.
   - Conducted correlation analysis to examine multicollinearity.

3. **Model Building and Evaluation**
   - Implemented multiple regression models to predict FWI, including:
     - **Linear Regression**
     - **Polynomial Regression**
     - **Ridge Regression**
     - **Lasso Regression**
     - **ElasticNet Regression**
   - Hyperparameter tuning using **GridSearchCV** to optimize regularization parameters.
   - Evaluated models based on R², MSE, MAE, and RMSE.

4. **Cross-Validation**
   - Used cross-validation to assess model generalization on unseen data.

## Results and Insights
- The analysis compares the performance of Ridge, Lasso, and ElasticNet models against linear and polynomial regression.
- Performance metrics were visualized and compared using R² scores.
- ElasticNet showed lower performance, which highlighted the importance of regularization parameter tuning.

## Technologies Used
- **Python** (pandas, numpy, matplotlib, seaborn)
- **Scikit-learn** for machine learning model development and hyperparameter tuning
- **Jupyter Notebook** for exploratory data analysis and model development

## How to Use the Notebook
1. Clone or download this repository.
2. Open the `algerian_FWI.ipynb` file in Jupyter Notebook or any compatible environment.
3. Run the cells to reproduce the analysis and model predictions.

## Repository Content
- `algerian_FWI.ipynb`: Jupyter Notebook containing the complete analysis and modeling process.
