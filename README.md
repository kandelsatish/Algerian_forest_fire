## Algerian Forest Fire Dataset Analysis

### Overview
This project focuses on analyzing the Algerian Forest Fire dataset to predict the burned area using regression models. The analysis involves data cleaning, feature engineering, model development, and evaluation. The following machine learning techniques are used: Multiple Linear Regression, Polynomial Regression, and Regularization (Lasso and Ridge).

### Contents
* Dataset Overview
* Data Preprocessing
* Data Visualization
* Model Development
* Model Evaluation
* Requirements
* Results



### Dataset Overview
The dataset contains meteorological and forest fire data such as temperature, humidity, wind speed, and rainfall. The goal is to use these features to predict the extent of the burned area.

### Data Preprocessing
* Handling Missing Values: Missing values are identified and filled using appropriate imputation techniques (e.g., mean substitution).
* Outlier Treatment: Box plots and statistical methods are employed to detect and handle outliers.
* Feature Selection and Engineering: Relevant features such as Temperature, Humidity, Wind Speed, and Rain are selected. Interaction terms and polynomial features are created to capture complex relationships.
  
### Data Visualization
Exploratory Data Analysis (EDA) is conducted using visualizations to understand the correlations and patterns within the dataset:

* Pair Plots: Show the relationships between features and the target variable (Burned Area).
* Histograms and Scatter Plots: Highlight the distributions and dependencies of the data.
Observations provide insights into the dynamics influencing forest fires.

### Model Development
* Multiple Linear Regression:
A baseline model is built using selected features.

* Polynomial Regression:
Polynomial features are added to capture non-linear relationships.
* Regularization Models (Lasso & Ridge):
Ridge and Lasso regression models are applied to reduce overfitting and optimize the model's performance.
Hyperparameter tuning is performed using GridSearchCV to find the optimal parameters.
Model Evaluation
* Evaluation Metrics: Models are evaluated using Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared.
* Cross-Validation: GridSearchCV is utilized for hyperparameter tuning and validation.
* Testing on Unseen Data: Models are tested on a separate dataset to assess their generalizability. The results are analyzed to determine the effectiveness and robustness of each model.

  
### Requirements
* Python 3.x
* Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, pickle
* Jupyter Notebook for running the analysis

### Results
The performance of the models is summarized below:

* The Multiple Linear Regression model provides a basic baseline.
* Polynomial Regression improves the model by capturing non-linear patterns.
* Regularization models (Lasso & Ridge) optimize performance by reducing overfitting.
* The final model's performance on unseen data shows the importance of hyperparameter tuning and feature selection.

### How to Run
Clone the repository:
> https://github.com/kandelsatish/Algerian_forest_fire.git

Navigate to the project directory and open the Jupyter Notebook:
> jupyter notebook forest_fire_analysis.ipynb


