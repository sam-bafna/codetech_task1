**Name:** Sameksha Bafna  
**Company:** CODTECH IT SOLUTIONS  
**ID:** CT08DS7262  
**Domain:** Machine Learning  
**Duration:** August to September 2024  
**Mentor:** Neela Santhosh Kumar  

---

# Overview of the Project

# Project : Predicting Housing Prices Using Linear Regression on the Ames Housing Dataset

![image](https://github.com/user-attachments/assets/88d8904a-45e0-4ac7-84db-a0593eeff6df)

![image](https://github.com/user-attachments/assets/a0569424-4d18-415b-be6f-003132302811)


---

**Objective:**

The objective of this project is to build a predictive model using linear regression to estimate housing prices based on various features from the Ames Housing dataset. The project focuses on selecting relevant features, preprocessing the data, training the model, and evaluating its performance. Additionally, the project includes a demonstration of how the model can be used to predict the price of a house with given characteristics.

---

**Key Activities:**

1. **Data Collection:**
   - The Ames Housing dataset was loaded using the `fetch_openml` function from the `sklearn.datasets` module. This dataset provides a rich set of features about houses sold in Ames, Iowa.

2. **Feature Selection:**
   - Relevant features for the prediction model were selected: `GrLivArea` (square footage of living area), `BedroomAbvGr` (number of bedrooms), and `Neighborhood` (location). The target variable is `SalePrice`.

3. **Data Preprocessing:**
   - Generated a correlation heatmap to understand the relationship between the selected features and the target variable (`SalePrice`).
   - Converted the categorical variable `Neighborhood` into numerical values using one-hot encoding.
   - Split the dataset into training and testing sets.
   - Standardized the numerical features (`GrLivArea` and `BedroomAbvGr`) using `StandardScaler`.

4. **Model Training:**
   - A linear regression model was trained on the processed training data using `LinearRegression` from `sklearn.linear_model`.

5. **Model Evaluation:**
   - The model's performance was evaluated using Mean Squared Error (MSE) and R² score on the test data.
   - Visualized the model’s predictions by plotting actual vs. predicted prices.

6. **Prediction Example:**
   - Demonstrated the model's application by predicting the price of a house with specified characteristics (2000 sq ft, 3 bedrooms, located in 'OldTown').

---

**Technology Used:**

- **Programming Language:** Python
- **Libraries:** 
  - **Data Handling:** `pandas`, `numpy`
  - **Visualization:** `seaborn`, `matplotlib`
  - **Modeling and Evaluation:** `scikit-learn` (including `LinearRegression`, `StandardScaler`, `train_test_split`, `mean_squared_error`, and `r2_score`)

---

**Dataset:**

- **Name:** Ames Housing Dataset
- **Source:** Loaded from `fetch_openml` via `sklearn.datasets`
- **Key Features Used:**
  - `GrLivArea`: Above grade (ground) living area square footage
  - `BedroomAbvGr`: Number of bedrooms above basement level
  - `Neighborhood`: Physical locations within Ames city limits
- **Target Variable:**
  - `SalePrice`: Sale price of the house (in USD)

---

**Conclusion:**

This report outlines the systematic approach taken to develop a linear regression model for predicting house prices using the Ames Housing dataset. The process included data preprocessing, model training, evaluation, and the application of the model for making predictions on new data.
