# IMDb India Movies Analysis

📌 **Project Overview**

This project focuses on analyzing and predicting movie ratings from an Indian movie dataset. The dataset is preprocessed, cleaned, and used to train a linear regression model to predict IMDb ratings based on features such as release year, votes, and duration.

📂 **Dataset**

The dataset used in this project contains IMDb data for Indian movies. It includes features such as:

- **Year**: The release year of the movie.
- **Votes**: The number of votes the movie received.
- **Duration**: The runtime of the movie in minutes.
- **Rating**: IMDb rating of the movie (Target variable).

🛠️ **Technologies Used**

- Python (pandas, numpy, scikit-learn, matplotlib, seaborn)
- Machine Learning: Linear Regression
- Data Preprocessing: StandardScaler for feature scaling
- Evaluation Metrics: MSE, MAE, R² Score

📊 **Project Workflow**

### Data Cleaning & Preprocessing:
- Remove missing and duplicate values.
- Convert categorical values to numerical formats.
- Standardize numerical features.

### Exploratory Data Analysis (EDA):
- Visualizing relationships between features.
- Identifying correlations.

### Model Building:
- Splitting data into training and testing sets.
- Training a Linear Regression model.

### Model Evaluation:
- Computing performance metrics (MSE, R² Score).
- Comparing predicted vs actual values.
The initial model's performance metrics:

- **Mean Squared Error (MSE):** 0.4083
- **R² Score:** 0.7795

## 🔥 Future Improvements

- Feature engineering to extract more meaningful insights.
- Experimenting with different regression models (e.g., Ridge, Lasso, Random Forest).
- Hyperparameter tuning to optimize the model.
- Handling outliers and improving data quality.
