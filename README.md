# 🏏 IPL Winner Prediction - Machine Learning Project

## 📌 Project Overview
This project predicts the winning team of IPL matches using Machine Learning classification algorithms.

The objective is to compare multiple ML models and evaluate their performance on match-level IPL data.

---

## 📊 Dataset Information
- Total Matches: 950
- Features: Team1, Team2, TossWinner, Venue, City, etc.
- Target Variable: WinningTeam

---

## ⚙ Data Preprocessing Steps
- Removed unnecessary columns (ID, Date, Umpires, etc.)
- Handled missing values
- Encoded categorical features using One-Hot Encoding
- Label encoded target variable
- Train-test split (80-20)

---

## 🤖 Models Used
1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier

---

## 📈 Model Performance

| Model | Accuracy |
|--------|----------|
| Logistic Regression | 68% |
| Random Forest | 60% |
| Decision Tree | (Add Yours) |

---

## 🛠 Tools & Libraries
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Google Colab

---

## 📌 Conclusion
Logistic Regression performed better compared to tree-based models for this dataset. The dataset contains multi-class classification with class imbalance, making prediction moderately challenging.

---

## 🚀 Future Improvements
- Hyperparameter tuning
- Feature engineering
- Class imbalance handling
- Try XGBoost

---

## 👩‍💻 Author
Saniya Shaikh 

