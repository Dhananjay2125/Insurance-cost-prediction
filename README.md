
## Health insurance cost prediction

### Overview
This project aims to predict the insurance costs of individuals based on various features such as age, sex, BMI, children, smoking habits, and region using machine learning algorithms. The goal is to build a model that can accurately predict the insurance charges to help insurance companies assess risk and set appropriate pricing.

The dataset used in this project is the **Insurance dataset**, which contains information about individuals and their respective medical insurance charges.
## Features
- Data preprocessing with statistical insights and feature encoding.
- Supports multiple machine learning models:
- Linear Regression
- Support Vector Regression (SVR)
- Random Forest Regressor
- Gradient Boosting Regressor
- Visual performance comparison of models.
- Model evaluation using metrics such as R², Mean Squared Error (MSE), and Mean Absolute Error (MAE).
- Save trained models for future predictions using joblib.
- User-friendly GUI for new customer predictions.

## Technologies Used
- Programming Language: Python
- Libraries and Frameworks:
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- joblib
- tkinter (or Streamlit/Flask) for GUI
## Workflow
- Get Overall Statistics of the Data
- Understand data distribution and summary statistics.
- Data Preprocessing
- Convert categorical columns (sex, smoker, region) to numerical values.
- Feature and Target Splitting
- Feature Matrix: X
- Target Variable: y (insurance charges).
- Train/Test Split
- Split data into training and testing sets (e.g., 80/20 split).
- Model Training
- Train multiple models:
- Linear Regression
- Support Vector Regression
- Random Forest Regressor
- Gradient Boosting Regressor
- Prediction on Test Data
- Test model performance on unseen data.
- Visual Performance Comparison
Use matplotlib to compare predicted vs. actual values.
Evaluate Models
- Assess models using metrics such as R², MSE, and MAE.
- Predict Charges for New Customers
- Input customer details through a GUI to generate predictions.
- Save Model
- Save the best-performing model using joblib.
- GUI Development
- Build a graphical user interface for user interaction.
## Usage
- Running the System
- Preprocess data:
- Use data_preprocessing.py to clean and encode your data.
- Train models:
- Run model_training.py to train and evaluate multiple models.
- Save the best model:
- Use joblib to save the model for deployment.
- Launch the GUI:
- Start the GUI application by running:
- bash
- Copy code

## Dataset

This system uses a structured dataset with the following features:

Age	- 30

Sex	- male

BMI	- 25.3

Children - 	1

Smoker	- yes

Region - southeast	

Charges - 22000.5


Replace insurance.csv in the repository with your dataset if needed.
## Feel free to modify as per your project’s specific requirements!
