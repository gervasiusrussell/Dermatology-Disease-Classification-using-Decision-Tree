# 🩺 Dermatology Disease Classification using Decision Tree

## 📖 Project Overview

This project applies **Decision Tree Classification** to the **Dermatology Dataset**, aiming to predict skin disease classes (`1–6`) based on patient attributes such as age and clinical features.

The notebook demonstrates a full **machine learning workflow**:

* Data preprocessing (missing values, outlier detection, encoding)
* Model training with **Decision Tree Classifier**
* Hyperparameter tuning via **GridSearchCV**
* Model evaluation with **classification metrics**

---

## ⚙️ Technologies Used

* **Python 3**
* **Pandas, NumPy** – Data handling
* **Matplotlib, Seaborn** – Visualization & EDA
* **Scikit-learn** – Modeling, preprocessing, and evaluation

---

## 📊 Workflow

1. **Data Preprocessing**

   * Converted `age` column to numeric type
   * Handled missing values (imputed with mean = 36.7)
   * Checked for outliers in numerical features

2. **Train-Test Split**

   * Split dataset into **80% training** and **20% testing**

3. **Modeling**

   * Trained a **Decision Tree Classifier**
   * Tuned hyperparameters (`criterion`, `max_depth`) using **GridSearchCV** with 5-fold cross-validation

4. **Evaluation**

   * Measured model performance with **classification report (precision, recall, f1-score, accuracy)**
   * Compared base Decision Tree vs tuned Decision Tree

---

## 📈 Results

* **Best Parameters (GridSearchCV):**

  * Criterion: `gini`
  * Max Depth: `8`

* **Model Performance (on test data):**

  * Achieved strong classification performance across all six disease classes.
  * Tuned model reduced overfitting compared to baseline.

---

## 🚀 How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   cd <repo-name>
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Launch Jupyter Notebook and open the project file:

   ```bash
   jupyter notebook
   ```

---

✍️ **Author**: Gervasius Russell
🎓 **Major**: Data Science, BINUS University
