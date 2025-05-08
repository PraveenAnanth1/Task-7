## 🧠 Task 7: Support Vector Machines (SVM) for Classification

### 🎯 Objective

Use SVMs (Support Vector Machines) for linear and non-linear classification on a binary classification dataset using Scikit-learn.

---

### 🛠️ Tools Used

* Python
* Scikit-learn
* NumPy
* Matplotlib

---

### 📁 Dataset

**Breast Cancer Wisconsin Dataset** (loaded from Scikit-learn)

---

### 📌 Task Steps

1. **Load and Prepare Data**

   * Load the breast cancer dataset.
   * Standardize the features using `StandardScaler`.
   * Reduce dimensions to 2D using PCA for visualization.

2. **Train SVM Models**

   * SVM with Linear Kernel.
   * SVM with RBF (Gaussian) Kernel.

3. **Visualize Decision Boundaries**

   * Plot the decision regions for both linear and RBF models using 2D PCA data.

4. **Tune Hyperparameters**

   * Use GridSearchCV to find the best `C` and `gamma` values.

5. **Evaluate Performance**

   * Perform cross-validation to evaluate model accuracy.

---

### 📊 Output

* Decision boundary plots for both linear and RBF SVM.
* Best hyperparameters from Grid Search.
* Cross-validation accuracy scores.

---

