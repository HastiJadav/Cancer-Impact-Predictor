# 🏥 Cancer-Impact-Predictor
Cancer-Impact-Predictor is a machine learning model designed to predict the average number of cancer-related deaths per year based on various features. This project applies advanced data preprocessing and multiple regression models to analyze historical trends in cancer mortality.

## 📊 Project Overview
OncoPredict AI aims to provide insights into cancer-related deaths using machine learning models. The project involves:
✔️ Handling missing values using mean and median imputation
✔️ Encoding categorical features using One-Hot Encoding (OHE) and Label Encoding
✔️ Removing irrelevant columns to improve model efficiency
✔️ Outlier treatment using IQR Winsorization
✔️ Splitting data into 80% training and 20% testing
✔️ Applying various regression models to predict mortality trends.

## 📝 Dataset & Preprocessing
* Missing values were replaced with mean and median.
* Categorical variables were processed using One-Hot Encoding (OHE) and Label Encoding.
* Irrelevant columns were removed to improve model accuracy.
* Outliers in numerical columns were treated using IQR Winsorization:
    Lower outliers replaced with the lower fence
    Upper outliers replaced with the upper fence
* Data was split into 80% training and 20% testing.
* Linear Regression assumptions were checked:
    Linearity,
    No autocorrelation,
    Homoscedasticity,
    Normality of errors,
    Multicollinearity.

## 📈 Model Performance
![image](https://github.com/user-attachments/assets/cb9bbbb3-ee9a-44a1-9459-63ea03ae8f77)

## 📊 Results
Polynomial Regression performed the best with an R² score of 0.992.
Linear Regression and KNN Regression also had high accuracy.
SVR Regression had a lower testing accuracy (0.85), indicating room for improvement.
Decision Tree Regression performed well but may benefit from hyperparameter tuning.

## 🔍 Conclusion
Polynomial Regression was the most effective model.
Linear and KNN Regression also provided high accuracy.
SVR Regression struggled with generalization.
Further feature selection and model tuning could enhance performance.

## 🔮 Future Improvements
Try different feature selection techniques to improve model accuracy.
Optimize hyperparameters using GridSearchCV.
Implement ensemble models like Random Forest or Gradient Boosting.
Deploy the model using Flask or Streamlit for real-world use.

## 👤 Author
Hasti Jadav
👨‍💻 Data Science & Machine Learning Enthusiast
📧 hastijadav03@gmail.com
🔗 https://www.linkedin.com/in/hasti-jadav-91a210238/



