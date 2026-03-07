# 📌 Drug Reviews Analysis & Prediction

## 📖 Project Overview
This project aims to analyze and predict drug reviews using machine learning models. The dataset includes user ratings, effectiveness, and side effects of various drugs. The models implemented include:

- **Linear Regression** 📈
- **Random Forest Regressor** 🌳
- **Support Vector Regression (SVR)** 🤖
- **Decision Tree Classifier** 🌲

## 📂 Dataset
- **Training Data:** `drugLibTrain_raw.csv`
- **Testing Data:** `drugLibTest_raw.csv`
- Features used: `rating`, `effectiveness`, `sideEffects`
- Target variable: `rating`

## 🔧 Installation & Requirements
Make sure you have the following dependencies installed:
```bash
pip install pandas numpy scikit-learn matplotlib
```

## 🚀 How to Run the Project
1. Load the dataset using Pandas.
2. Handle missing values by dropping them.
3. Split the dataset into training and validation sets.
4. Encode categorical features using `OrdinalEncoder`.
5. Train and evaluate the models.
6. Visualize results with scatter plots and accuracy graphs.

Run the script using:
```bash
python main.py
```

## 📊 Model Performance Metrics
| Model | Training MSE | Validation MSE | R² Score |
|--------|-------------|----------------|----------|
| Linear Regression | ✅ | ✅ | ✅ |
| Random Forest Regressor | ✅ | ✅ | ✅ |
| Support Vector Regression | ✅ | ✅ | ✅ |

## 📉 Visualizations
- **Accuracy vs Epoch Graph** for Decision Tree Classifier
- **Scatter Plot of Actual vs Predicted Ratings**

## ✨ Future Enhancements
🔹 Feature Engineering to improve model performance  
🔹 Hyperparameter tuning for better optimization  
🔹 Implementing Deep Learning models  

## 💡 Contributors
👤 **Your Name: Saurabh**  
📧 **Email: sauravsingh6462@gmail.com**   
🔗 **LinkedIn:- https://www.linkedin.com/in/saurabh1826/** 

## ⚖️ License
This project is open-source and free to use under the MIT License. 🎉
