# 👩‍💻 Ziyan Chen – Project Reflection

## Project Theme: Understanding Student Performance through Machine Learning

---

## 🎯 My Goals

- Learn to apply supervised machine learning techniques (Decision Trees, Random Forests)
- Improve data preprocessing and feature engineering skills
- Understand model evaluation metrics beyond just accuracy
- Experiment with hyperparameters and interpret model outputs effectively

---

## 🔍 My Approach

- **Dataset**: I selected a dataset from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/856/higher+education+students+performance+evaluation) with 145 student records, each including GPA, attendance, study habits, and parental background.
- **Data Cleaning**: I removed non-predictive fields (like Course ID), handled duplicates, and prepared the data for modeling.
- **Modeling**: I applied both Decision Tree and Random Forest classifiers, and experimented with:
  - Tree depth
  - Train/test split ratio
  - Random seed values
  - `zero_division` handling to resolve classification warnings
- **Evaluation**: I used a range of metrics: Accuracy, Precision, Recall, F1-score, and Confusion Matrix.

---

## 📊 What I Discovered

- **Key Influencing Factors**:
  - Cumulative GPA
  - Weekly study hours
  - Parental education and occupation
- **Model Performance**:
  - Best Decision Tree model accuracy: **~34%**
  - Notable class imbalance: some classes had zero recall/precision
  - Random Forest slightly improved stability but not performance (due to small dataset)
- **Challenges**:
  - Overfitting in high-depth trees
  - Underfitting in shallow trees
  - Misclassifications in less frequent grade categories

---

## 🌱 What I Learned

- Real-world data is **noisy**, and preprocessing is critical
- Evaluation should go beyond accuracy — **Precision, Recall, and F1** provide clearer insights
- Decision Trees provide **transparency**, but are prone to overfitting
- Hyperparameter tuning is essential — even small changes can affect results

---

## 🔮 Future Improvements

- Address class imbalance using **SMOTE** or **undersampling**
- Try ensemble methods like **Gradient Boosting** or **XGBoost**
- Apply **model interpretability tools** like SHAP or LIME
- Work with **larger and more diverse datasets** to enhance generalizability

---

## 🔗 Resources That Helped Me

- [ML Cheat Sheet – DataCamp](https://s3.amazonaws.com/assets.datacamp.com/email/other/ML+Cheat+Sheet_2.pdf)  
- [Scikit-Learn Cheat Sheet](https://images.datacamp.com/image/upload/v1676302380/Marketing/Blog/Scikit-Learn_Cheat_Sheet.pdf)  
- [Matplotlib Guide – GeeksforGeeks](https://www.geeksforgeeks.org/data-visualization-using-matplotlib/)

---

## ✨ Final Thoughts

This project challenged me to think critically about how different data factors impact machine learning results. Despite limited accuracy, I gained a lot through model tuning, error analysis, and exploring the real-world complexities of educational data.

