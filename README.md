# 🏦 Loan Acceptance Prediction using Manual SVM (No Sklearn)

This project predicts whether a customer will accept a **personal loan offer** using a custom implementation of **Support Vector Machine (SVM)** — built **from scratch** without using `sklearn.svm.SVC`.

We also explore the data through **visualization** to understand feature relationships and class distribution.

---

## 📌 Project Highlights

- ✅ Custom-built **SVM Classifier** using Gradient Descent
- ✅ **No use of external SVM libraries** like `sklearn.svm`
- 📊 Exploratory Data Analysis (EDA) with `matplotlib` and `seaborn`
- 🔍 Decision boundary visualization for model interpretation

---

## 📂 Dataset

- **Name:** Universal Bank Dataset
- **Source:** Provided as `Universalbank_1500.csv`
- **Target Column:** `Personal Loan` (1 = Accepted, 0 = Not Accepted)

---

## 🧠 Features Used

For simplicity and visualization, only two features were used in the custom SVM:

- `Income`
- `CCAvg` (Credit Card Average Spending)

> These features are normalized before training.

---

## 📈 Visualizations

- Class distribution bar plot
- Correlation heatmap of all features
- Decision boundary plot using 2D input features

---

## ⚙️ Tech Stack

- `Python`
- `NumPy`, `Pandas` – Data handling
- `Matplotlib`, `Seaborn` – Visualization
- `Sklearn` – Only used for `train_test_split` and data preprocessing

---

## 🚀 How It Works

1. **Load Data**  
   Read `Universalbank_1500.csv` and extract features.

2. **Visualize Data**  
   Understand data distribution and correlations.

3. **Preprocess**  
   Normalize features and map output class to {-1, 1}.

4. **Train Custom SVM**  
   Run gradient descent to find optimal weights and bias.

5. **Predict and Evaluate**  
   Predict on test set and calculate accuracy.

6. **Visualize Decision Boundary**  
   Plot the separating hyperplane learned by SVM.
