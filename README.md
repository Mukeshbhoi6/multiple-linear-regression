# Commodity Price Prediction using Multiple Linear Regression


## Tech Stack
- Language: Python
- Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- Environment: Jupyter Notebook

## Dataset Details
The dataset 'Date-Wise-Prices-all-Commodity.xlsx' contains:
- Categorical Features: State, District, Market, Commodity, Variety, Grade.
- Numerical Features: Min Price, Max Price.
- Target Variable: Modal Price.

## Key Steps in Notebook
1. Data Preprocessing: Handling missing values and dropping unnecessary columns like diffgr:id and Arrival_Date.
2. Feature Encoding: Converting categorical text data into numerical format using LabelEncoder.
3. Model Training: Splitting data into training and testing sets and fitting a LinearRegression model.
4. Evaluation: Checking the coefficients and intercept of the model.
