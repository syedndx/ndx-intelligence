## EXP-001: The Accuracy Paradox
* **Date:** 2024-12-27
* **Context:** Imbalanced binary classification (95:5) with Naive Logistic Regression.
* **The Trap:** Optimizing for Accuracy on imbalanced data.
* **The Lie:** Model reported **96.0% Accuracy**.
* **The Truth:** Model missed **62%** of the minority class (Recall 0.38).
* **Lesson:** Accuracy is a vanity metric. It hides total failure in the minority class. Never use accuracy alone for imbalance ratios > 80:20.
