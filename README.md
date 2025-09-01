# 📊 CodeSentinel_DataAnalytics-Project3 🎯

## 📌 Project Overview
This project focuses on building a predictive model to estimate house prices based on various features such as square footage, number of bedrooms/bathrooms, lot size, year built, garage size, and neighborhood quality. By applying Linear Regression, the project demonstrates how statistical modeling and data visualization can turn raw housing data into valuable business insights.

--- 

## 🎯 Objectives
- 🔹 Perform Exploratory Data Analysis (EDA) to understand dataset patterns and distributions.
- 🔹 Handle missing values and ensure clean, structured data.
- 🔹 Build a Linear Regression model to predict house prices.
- 🔹 Evaluate the model using MSE, RMSE, and R² metrics.
- 🔹 Visualize results using interactive and detailed plots.
- 🔹 Identify key features influencing house prices.

---

## 🛠️ Tools & Technologies
- Python 🐍
- Pandas → Data manipulation & cleaning
- NumPy → Mathematical operations
- Matplotlib & Seaborn → Data visualization
- Scikit-learn → Machine Learning (Linear Regression, Train-Test Split, Model Evaluation)
- Jupyter Notebook / VS Code → Development Environment


---

## 📊 Workflow
### 1️⃣ Data Loading & Exploration
- Imported the dataset House_Price_Regression_Dataset.csv.
- Checked shape, missing values, and dataset summary.
- Displayed first few rows to understand the structure.
### 2️⃣ Data Cleaning
- Removed rows with missing target variable (House_Price).
- Replaced missing numeric values with median.
- Replaced missing categorical values with mode.
### 3️⃣ Feature Selection
- Selected relevant independent variables (Square_Footage, Bedrooms, Bathrooms, Lot Size, etc.).
-  Defined dependent variable as House_Price.
### 4️⃣ Train-Test Split
Divided the dataset into:
- 80% Training Data
- 20% Testing Data
### 5️⃣ Model Training
- Used Linear Regression to train on housing data.
### 6️⃣ Model Evaluation
Evaluated performance using:
- ✅ Mean Squared Error (MSE)
- ✅ Root Mean Squared Error (RMSE)
- ✅ R² Score (Coefficient of Determination)

---

## 📈 Visualizations:-
To make insights more interactive and detailed, multiple plots were generated:
### 📊 Actual vs Predicted Plot
- Shows how close predictions are to actual house prices.
### 📉 Residuals Distribution
- Highlights how errors are distributed and model’s accuracy.
### 📈 Residuals vs Predicted Plot
- Helps detect non-linearity, outliers, or heteroscedasticity.
### 🏆 Feature Importance (Coefficients)
- Displays which variables have the strongest impact on price.
### 🔥 Correlation Heatmap
- Visualizes relationships between all numeric features.
### 📦 Top Features vs House Price (Scatterplots)
- Deep dive into top 3 features affecting housing prices.
### 🌍 Neighborhood Quality vs House Price (Boxplot)
- Demonstrates the effect of qualitative features on prices.

---

## 🏆 Results & Key Insights
- ✅ The Linear Regression model achieved a strong R² score, indicating good explanatory power.
- ✅ Square_Footage, Lot_Size, and Neighborhood_Quality emerged as the most influential predictors.
- ✅ Visualization confirmed positive correlation between house size and price.
- ✅ Residuals analysis showed errors were normally distributed, validating the regression assumptions.

---

## 🚀 Future Improvements
- 🔹 Apply feature engineering to capture non-linear relationships.
- 🔹 Experiment with other regression algorithms (Ridge, Lasso, Random Forest Regressor).
- 🔹 Hyperparameter tuning to improve accuracy.
- 🔹 Deploy the model as a web app using Flask/Streamlit for real-time predictions.
- 🔹 Create an interactive dashboard in Power BI / Tableau for business users.

---

## 📬 Author
### 👨‍💻 Abdullah Umer
### 📊 Data Analyst | Power BI Developer | Python Enthusiast


---


## 🔗 Connect
### 💼 LinkedIn: https://www.linkedin.com/in/abdullah-umar-730a622a8/
### 💼 Portfolio: https://linktr.ee/AbdullahUmar.DataAnalyst
### 📧 Email: umerabdullah048@gmail.com

---


### Task Statement:-
![Preview](https://github.com/Abdullah321Umar/DataZenixSolutions_DataAnalytics-Project3/blob/main/Project%203.png)


---

### Screenshots / Demos:-
Show what the Code and Output look like.
![Preview](https://github.com/Abdullah321Umar/DataZenixSolutions_DataAnalytics-Project3/blob/main/Project-3%20(Code%2BOutput).ipynb)
