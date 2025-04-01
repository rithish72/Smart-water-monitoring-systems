# 🚰 Smart Water Consumption Prediction

## 📌 Project Overview
This project focuses on predicting water consumption using machine learning. By analyzing factors like temperature, humidity, apartment type, income level, and appliance usage, the model helps optimize water distribution and improve resource management.

## 📊 Approach
1. **Data Preprocessing** - Handling missing values, encoding categorical variables, and normalizing numerical values.
2. **Exploratory Data Analysis (EDA)** - Analyzing trends, correlations, and patterns in the data.
3. **Feature Engineering** - Creating new features to enhance model performance.
4. **Model Selection & Training** - Testing models like Linear Regression, Random Forest, and XGBoost.
5. **Evaluation & Metrics** - Measuring performance using Mean Squared Error (MSE) and R² score.
6. **Prediction & Submission** - Generating predictions and saving results.

## 🔧 Technologies and Tools Used
| Technology/Tool          | Purpose                                                  |
|-------------------------|----------------------------------------------------------|
| **Python**              | Core programming language                               |
| **Pandas**              | Data manipulation and preprocessing                     |
| **NumPy**               | Numerical computations                                  |
| **Scikit-learn**        | Model training and evaluation                          |
| **XGBoost**             | Final model for high-performance predictions           |
| **Matplotlib & Seaborn**| Data visualization and exploratory analysis            |
| **Jupyter Notebook**    | Interactive environment for coding                     |

## 📌 Installation
Ensure you have the necessary dependencies installed:
```bash
pip install pandas numpy scikit-learn xgboost matplotlib seaborn
```

## 🚀 How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/rithish72/Smart-water-monitoring-systems.git
   cd smart-water-monitoring
   ```
2. Load and preprocess the dataset:
   ```python
   import pandas as pd
   train_df = pd.read_csv('train.csv')
   test_df = pd.read_csv('test.csv')
   ```
3. Train the model:
   ```python
   xgb_model.fit(X_train, y_train)
   ```
4. Generate predictions:
   ```python
   predictions = xgb_model.predict(X_test)
   ```
5. Save submission file:
   ```python
   submission.to_csv("submission.csv", index=False)
   ```

## 📌 Results
- **Best Model:** XGBoost
- **R² Score:** 90.87%
- **MSE:** 77.4%

## 🤝 Contributing
Feel free to submit issues or fork this repository to make improvements!

## 📧 Contact
For any inquiries, reach out via [your-email@example.com](rithishkurapati72@gmail.com).

---

⭐ Star this repo if you found it useful! 🚀
