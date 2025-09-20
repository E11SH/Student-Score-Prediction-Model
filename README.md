# 🎓 Student Score Prediction  

This project focuses on predicting students’ final exam scores using regression models.  
The goal is to understand how factors like study hours, attendance, and participation affect performance,  
and provide insights for improving learning outcomes.  

---

## 📌 Project Overview  
- **Data Preprocessing**: Removed irrelevant columns (e.g., Student_ID), handled missing values, and encoded categorical variables (Gender, Attendance, Participation).  
- **Exploratory Data Analysis (EDA)**: Used histograms, scatterplots, and boxplots to identify patterns (e.g., more study hours = higher scores).  
- **Feature Engineering**: Compared models trained with only numeric features vs. numeric + categorical.  
- **Models Trained**: Linear Regression (baseline) and Polynomial Regression (to capture non-linear patterns).  
- **Evaluation**: Metrics used include MAE, RMSE, and R² score to measure prediction accuracy.  

---

## 🛠️ Tech Stack  
- Python  
- Pandas, NumPy → Data manipulation & preprocessing  
- Matplotlib, Seaborn → Data visualization  
- Scikit-learn → Regression models & evaluation  

---

## 📂 Dataset  
The dataset contains student-related features such as:  
- Study hours per week  
- Attendance level (Always, Sometimes, Never)  
- Participation in activities  
- Sleep patterns and lifestyle habits  
- Final exam scores (target variable)  

---

## 📊 Data & Model Analysis  
- Cleaned and prepared both numeric and categorical features.  
- Created visualizations like correlation heatmaps and scatterplots.  
- Split data into training & test sets for fair evaluation.  
- Compared performance of linear vs. polynomial regression.  

---

## 🤖 Models Implemented  
- **Linear Regression** → Simple baseline predictor  
- **Polynomial Regression** → Captures complex, non-linear relationships  

---

## 📈 Model Evaluation & Insights  
- Using both numeric and categorical features improved predictions.  
- Polynomial regression fit the data better but risked overfitting.  
- Study hours and attendance showed the strongest impact on exam scores.  

---

## 📷 Visualizations  
- Correlation heatmap of features  
- Scatterplot of study hours vs. exam scores  
- Boxplot of attendance vs. performance  
