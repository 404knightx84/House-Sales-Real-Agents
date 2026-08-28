# House Sales — RealAgents 🏠

Predicting house sale prices using historical sales data. This project covers the full data science workflow — from data cleaning and exploratory analysis to building and evaluating machine learning models — to help RealAgents estimate property prices more accurately.

## 📌 Project Overview

RealAgents wants a reliable way to estimate house sale prices based on historical property data. This project:

- Cleans and validates raw housing data
- Explores relationships between property features and sale price
- Builds and compares machine learning models to predict price
- Evaluates model performance using appropriate regression metrics

## 🎯 Objectives

- Handle missing values, inconsistent formatting, and outliers in the dataset
- Perform exploratory data analysis (EDA) to identify key drivers of house price
- Engineer relevant features from raw data
- Train and compare multiple regression models
- Evaluate and select the best-performing model
- Communicate findings and recommendations clearly

## 🗂️ Dataset

The dataset contains historical house sales records, typically including features such as:

| Feature | Description |
|---|---|
| `house_id` | Unique identifier for each property |
| `city` | Location of the property |
| `sale_price` | Target variable — final sale price |
| `sale_date` | Date the property was sold |
| `months_listed` | Number of months the property was listed |
| `bedrooms` | Number of bedrooms |
| `bathrooms` | Number of bathrooms |
| `living_area` | Living area (sq. ft.) |
| `garden` | Whether the property has a garden |
| `garage` | Whether the property has a garage |
| `house_type` | Type of house (e.g., Semi-detached, Terraced, Detached) |

*(Exact column names/features may vary depending on the version of the dataset used.)*

## 🛠️ Tools & Technologies

- **Python** — pandas, NumPy
- **Visualization** — Matplotlib, Seaborn
- **Machine Learning** — scikit-learn (RandomForestRegressor, LinearRegression, etc.)
- **Environment** — Jupyter Notebook

## 🔍 Project Workflow

1. **Data Cleaning & Validation**
   - Handle missing/null values
   - Correct data types and inconsistent categories
   - Remove or treat outliers

2. **Exploratory Data Analysis (EDA)**
   - Distribution of sale prices
   - Correlation between features and target variable
   - Visualizing trends across categories (location, house type, etc.)

3. **Feature Engineering**
   - Encoding categorical variables
   - Creating derived features where useful
   - Scaling/normalizing numerical features (where required)

4. **Modeling**
   - Train-test split
   - Baseline model: Linear Regression
   - Advanced model: Random Forest Regressor
   - Hyperparameter tuning (where applicable)

5. **Model Evaluation**
   - Metrics: RMSE, MAE, R²
   - Comparison of model performance
   - Feature importance analysis

6. **Insights & Recommendations**
   - Key price-driving factors
   - Model limitations and next steps


## 🚀 How to Run

```bash
# Clone the repository
git clone https://github.com/<your-username>/House-Sales-Real-Agents.git
cd House-Sales-Real-Agents

# Install dependencies
pip install -r requirements.txt

# Launch the notebook
jupyter notebook
```

## 📁 Project Structure

```
House-Sales-Real-Agents/
│
├── house_sales.csv          # Raw historical house sales dataset
├── train.csv                 # Training data split
├── validation.csv            # Validation data split
├── notebook.ipynb             # Jupyter notebook — cleaning, EDA & modeling
└── README.md                  # Project documentation
```

## 🔮 Future Improvements

- Incorporate additional external data (e.g., neighborhood amenities, school ratings)
- Experiment with gradient boosting models (XGBoost, LightGBM)
- Deploy the model as an API or simple web app for real-time price predictions


⭐ If you found this project useful, consider giving it a star!
