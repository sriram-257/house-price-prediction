# 🏠 House Price Prediction

## Objective

Build a machine learning model to predict house prices based on numerical features from the California Housing dataset.

## Dataset

The **California Housing dataset** from Scikit-learn is used for this project.

The dataset contains numerical features related to housing and a target variable representing the median house value.

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow

### 1. Data Loading

The California Housing dataset is loaded using Scikit-learn.

### 2. Exploratory Data Analysis

The dataset is explored using:

- Dataset information
- Statistical summary
- Missing-value analysis
- Feature distribution plots
- Correlation heatmap

### 3. Data Preprocessing

The data is prepared for machine learning by:

- Separating features and target variable
- Splitting the dataset into training and testing sets
- Standardizing numerical features using `StandardScaler`

### 4. Model Training

A **Linear Regression** model is trained using the training data.

### 5. Model Evaluation

The model is evaluated using:

- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

## Model Performance

| Metric | Result |
|---|---:|
| Mean Squared Error (MSE) | **0.5559** |
| Root Mean Squared Error (RMSE) | **0.7456** |
| R² Score | **0.5758** |

The model achieved an **R² score of 0.5758**, meaning it explains approximately **57.58% of the variation in the target house values** on the test data.

## Visualizations

The project includes:

- Feature distribution plots
- Correlation heatmap
- Actual vs Predicted house values plot
- Feature coefficient analysis

## Skills Demonstrated

- Data Loading
- Exploratory Data Analysis
- Data Preprocessing
- Feature Scaling
- Linear Regression
- Regression Model Evaluation
- Data Visualization
- Python Machine Learning

## Conclusion

A Linear Regression model was developed to predict house values using the California Housing dataset.

The complete workflow includes data exploration, preprocessing, feature scaling, model training, prediction, and evaluation using MSE, RMSE, and R².

The project demonstrates the fundamental workflow of a supervised **regression machine learning problem**.

## Project Files

```text
house-price-prediction/
│
├── House_Price_Prediction.ipynb
├── README.md
├── requirements.txt
└── .gitignore
