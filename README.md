🚗 Car Price Prediction Project
This project presents a machine learning model to predict the prices of used cars based on various features. The model is trained using a dataset containing vehicle specifications and is visualized with insights to aid in understanding the factors that influence car prices.

📌 Objective
To develop a predictive model that can estimate the selling price of a car based on key features like brand, manufacturing year, fuel type, transmission, and mileage. This helps car dealers and individuals assess vehicle value more accurately.

📂 Project Structure
Exploratory Data Analysis (EDA): Uncovered insights about car prices and their relation to other features.

![image](https://github.com/user-attachments/assets/89704c56-022d-4be0-83e2-0efa216b5a17)

Data Preprocessing: Handled missing values, converted categorical data, and scaled numerical features.

Model Building: Trained multiple regression models and selected the best-performing one.

Evaluation: Compared models using metrics like R² Score and RMSE.

Visualization: Used Power BI (or can be integrated with Tableau) to visualize key insights like brand-wise price comparison, fuel type distribution, and mileage vs. price trend.

🧠 Machine Learning Models Used
Linear Regression

Lasso Regression

Ridge Regression

Random Forest Regressor

Gradient Boosting Regressor

📊 Key Insights
Cars with fewer years of usage fetch higher prices.

Diesel and Petrol are the most common fuel types.

Manual transmission cars are more prevalent in the dataset.

Certain brands have significantly higher average prices.

🛠️ Tools and Technologies
Languages: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn

Visualization: Power BI / Tableau (optional)

Environment: Jupyter Notebook

📁 Files in Repository
Car_Price_Prediction.ipynb: Jupyter notebook containing the entire workflow.

README.md: Description of the project, objectives, and findings.

dataset.csv: (if added) Contains the data used for training the model.
