# 🚗 Car Price Prediction using Machine Learning

This project aims to predict the selling price of a car based on various features like present price, kilometers driven, fuel type, transmission, and car age using machine learning algorithms.

![Project Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📌 Problem Statement
Used car resale value varies depending on many factors. Predicting an accurate selling price helps both buyers and sellers. This project builds a regression model to predict car prices using historical data.

---

## 📂 Dataset Overview

| Feature          | Description                              |
|------------------|------------------------------------------|
| Car_Name         | Name of the car                          |
| Year             | Manufacturing year                       |
| Selling_Price    | Car's resale price (Target variable)     |
| Present_Price    | Price when the car was bought new        |
| Driven_kms       | Total kilometers driven                  |
| Fuel_Type        | Petrol / Diesel / CNG                    |
| Selling_type     | Dealer / Individual                      |
| Transmission     | Manual / Automatic                       |
| Owner            | Number of previous owners                |

---

## 🔧 Technologies Used

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn

---

## 🔍 Exploratory Data Analysis

- Most cars are petrol and have manual transmission
- Car age and high mileage tend to reduce resale value
- Present_Price is strongly correlated with Selling_Price

---

## 🧹 Data Preprocessing

- Dropped `Car_Name` (non-numeric)
- Created `Car_Age` feature from `Year`
- Label encoding for categorical columns
- Train-test split (80-20)

---

## 🤖 Machine Learning Models

| Model               | R² Score | MAE     |
|--------------------|----------|---------|
| Linear Regression  | ~0.85    | ~1.2    |
| Random Forest       | ~0.96    | ~0.5    |

✅ **Random Forest** performed best and is used as the final model.

---

## 📊 Visualizations

- Correlation Heatmap
- Distribution of Selling Price
- Actual vs Predicted Prices
- Feature Importance Barplot
- Residuals Histogram
- Boxplot of Car Age vs Price

---

## 📈 Results

- Random Forest Regressor provided a robust and highly accurate prediction model.
- Key influencing features: Present Price, Car Age, and Transmission type.

---

## 🔮 Future Scope

- Streamlit or Flask app deployment
- Feature engineering with insurance and brand data
- Deep learning model for image-based price prediction
- Hyperparameter tuning via GridSearchCV

---

## 👨‍💻 Author

**Arjav Jain**  
📧 arjavjain062@gmail.com  
🎓 BCA Student, TMU Moradabad  
🌐 [GitHub](https://github.com/arjav527)

---

