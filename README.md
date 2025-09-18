# K-Nearest Neighbors (KNN) Classifier – Social Network Ads Dataset

This project implements a K-Nearest Neighbors (KNN) classifier to predict user behavior from the **Social Network Ads** dataset. It includes data visualization, feature scaling, training/testing split, and decision boundary visualization using `mlxtend`.

---

## 📁 Dataset

- **Name:** `Social_Network_Ads.csv`
- **Features Used:**
  - Age
  - Estimated Salary
- **Target:** Purchased (0 = No, 1 = Yes)

---

## 🔍 Key Features

- KNN classifier using `scikit-learn`
- Feature scaling with `StandardScaler`
- Visualization of decision boundaries
- Accuracy evaluation on test set

---

## 📈 Model Performance

- **Test Accuracy:** ~0.90 (with `k=3`)
- You can experiment with other `k` values to observe accuracy changes

---

## 📊 Visualizations

- Scatter plot of raw data (`Age` vs `EstimatedSalary`)
- Decision region plot to visualize KNN classification boundaries

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/shahzadmustafa15/KNNClassifier.git
   cd KNNClassifier
