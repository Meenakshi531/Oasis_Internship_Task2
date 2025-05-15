# Oasis_Internship_Task2
# Car Price Prediction Project

## Objective
The goal of this project is to build a machine learning model to predict the selling price of used cars based on various features such as manufacturing year, present price, kilometers driven, fuel type, selling type, transmission, and ownership details.

## Technologies Used
- Python
- Jupyter Notebook
- Pandas & NumPy
- Scikit-learn (for preprocessing, encoding, scaling, and modeling)
- Matplotlib & Seaborn (for data visualization)


## Dataset Features
- **Year**: Manufacturing year of the car
- **Present_Price**: Current ex-showroom price of the car (in lakhs)
- **Driven_kms**: Kilometers driven by the car
- **Fuel_Type**: Type of fuel used (Petrol, Diesel, CNG)
- **Selling_type**: Dealer or individual sale
- **Transmission**: Manual or Automatic
- **Owner**: Number of previous owners

## Features & Pipeline
- Data cleaning and preprocessing
- Label encoding categorical variables
- Feature scaling using StandardScaler
- Training regression models ( Random Forest Regressor)
- Predicting car price from user input after appropriate preprocessing

## Results & Performance

- The model was trained on a dataset containing used car features and their selling prices.
- Training Accuracy: The model achieved 98% indicating a good fit.
- Testing Accuracy: On the testing it scored 96% showing that the model generalizes well to unseen data.
- Mean Absolute Error (MAE): The average absolute difference between predicted and actual prices is 0.6 , and R2 score is 0.98 something which is reasonable for price estimation in this domain.
- The model predicted car prices with reasonable precision when the input features were preprocessed correctly (including proper label encoding and scaling).
- Some discrepancies in prediction may occur if user inputs contain categories or values not seen during training (e.g., new fuel types). Proper handling of such cases is essential for real-world deployment.

Overall, the model serves as a reliable tool for quick price estimation of used cars, helping buyers and sellers make informed decisions.












