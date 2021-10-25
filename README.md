# risky_business
Mortgages, student and auto loans, and debt consolidation are just a few examples of credit and loans that people seek online.   Peer-to-peer lending services such as Loans Canada and Mogo let investors loan people money without using a bank. However, because investors always want to mitigate risk, a client has asked that you help them predict credit risk with machine learning techniques. 

## Resampling
**Which model had the best balanced accuracy score?**

Simple Logistic Regression balanced accuracy score : 0.5
Oversampling balanced accuracy score : 0.7946044885121808
Smote balanced accuracy score : 0.8041461911615757
Undersampling balanced accuracy score : 0.8105964283810437
Combination balanced accuracy score : 0.8041461911615757
**The Model with the best balanced accuracy score was the UNDERSAMPLING Model with a score of 0.0.810596.**

---

**Which model had the best recall score?**

Simple Logistic Regression recall score : 0.97
Oversampling recall score : 0.61
Smote recall score : 0.63
Undersampling recall score : 0.64
Combination recall score : 0.63
**The Model with the best recall score was the Simple Logistic Regression model with a score of 0.97.**

---

**Which model had the best geometric mean score?**

Simple Logistic Regression geometric mean score : 0.00
Oversampling geometric mean score : 0.77
Smote geometric mean score : 0.78
Undersampling geometric mean score : 0.79
Combination geometric mean score : 0.78
**The Model with the best geometric mean score was the UNDERSAMPLING model with a score of 0.79.**

---

## Ensemble Learning
**Which model had the best balanced accuracy score?**

Balanced Random Forest Classifier balanced accuracy score : 0.7023150163472849
Easy Ensemble Classifier balanced accuracy score : 0.7287551866739527
**The Model with the best balanced accuracy score was the Easy Ensemble Classifier Model with a score 0.7287551866739527.**

---

**Which model had the best recall score?**

Balanced Random Forest Classifier recall score : 0.81
Easy Ensemble Classifier recall score : 0.76
**The Model with the best recall score was the Balanced Random Forest Classifier model with a score of 0.81.**

---

**Which model had the best geometric mean score?**

Balanced Random Forest Classifier geometric mean score : 0.69
Easy Ensemble Classifier geometric mean score : 0.73
**The Model with the best geometric mean score was the Easy Ensemble Classifier model with a score of 0.73.**

---

**What are the top three features?**

The top three features are:
 (0.0655635817623315, 'total_rec_int'),
 (0.06528036081873223, 'last_pymnt_amnt'),
 (0.06277129875620881, 'total_pymnt_inv'),

---