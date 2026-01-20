# 🧒 Day 2: How Computers "Learn" (Supervised vs. Unsupervised)

**Series:** Learning AI Like a 4-Year-Old  
**Status:** ✅ Completed  
**Tech Stack:** Python, Scikit-Learn  
![What is AI](supervised unsupervised.png)



---

## 📖 The Analogy (ELI5)
*From my [LinkedIn Series](https://www.linkedin.com/posts/dvadash-purani-96190324b_artificialintelligence-machinelearning-datascience-activity-7419247684676505600-icaH?utm_source=share&utm_medium=member_desktop&rcm=ACoAAD3kdZkBTTYtZPrQGwgFH6V2rm7Jgz54SaE)*

Imagine teaching a child the difference between a **Cat** 🐱 and a **Dog** 🐶.

### 1. The Teacher Way (Supervised Learning) 👩‍🏫
You hold up a picture and say: *"This is a cat."* Then another: *"This is a dog."* You give the computer the "answer key" (labels). The computer learns by memorizing your examples and checking if it got the answer right.

### 2. The "Figure It Out" Way (Unsupervised Learning) 🧩
You dump a box of photos on the floor and say nothing. You just tell the computer: *"Group the ones that look similar."* The computer notices patterns (pointy ears vs. floppy ears) without knowing the names.

---

## 🧠 The Technical Concept

### Supervised Learning
* **Data:** Labeled (Input `X` + Output `y`).
* **Goal:** Learn a mapping function `y = f(X)` to predict `y` for new `X`.
* **Common Algorithms:** Linear Regression, Logistic Regression, Decision Trees.
* **Metrics:** Accuracy, Precision, Recall, RMSE.

### Unsupervised Learning
* **Data:** Unlabeled (Input `X` only).
* **Goal:** Discover hidden structures or patterns in the data.
* **Common Algorithms:** K-Means Clustering, Principal Component Analysis (PCA).
* **Metrics:** Silhouette Score, Inertia.

---





