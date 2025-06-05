
# 🩺 Pima Indians Diabetes Prediction using Tree-Based Models

## 🧾 Description

This project applies **Decision Tree** and **Random Forest** classifiers to the **Pima Indians Diabetes Dataset** to predict whether a patient has diabetes based on medical diagnostic measurements. The goal is to evaluate model performance using metrics such as accuracy, classification report, and cross-validation.

---

## 📁 Dataset Overview

* **Source**: [UCI / Kaggle – Pima Indians Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)  
* **Filename**: `diabetes.csv`  
* **Attributes**:

  1. **Pregnancies**  
  2. **Glucose**  
  3. **BloodPressure**  
  4. **SkinThickness**  
  5. **Insulin**  
  6. **BMI**  
  7. **DiabetesPedigreeFunction**  
  8. **Age**  
  9. **Outcome** (0 = Non-diabetic, 1 = Diabetic)  

---

## 🛠️ Technologies Used

* Python 3  
* pandas, numpy  
* matplotlib, seaborn  
* scikit-learn  

---

## 📌 Project Structure

| File                                      | Description                                                          |
| ----------------------------------------- | -------------------------------------------------------------------- |
| `decision_tree_random_forest_pima.ipynb` | Jupyter notebook for training Decision Tree and Random Forest models |
| `README.md`                               | Project overview and instructions                                    |

---

## 🚀 How to Run

1. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database).  
2. Place the dataset file as `diabetes.csv` in your working directory.  
3. Open `decision_tree_random_forest_pima.ipynb` in Jupyter Notebook.  
4. Run the cells sequentially to:

   * Load and inspect the data  
   * Split into training and test sets  
   * Train and evaluate Decision Tree and Random Forest models  
   * Visualize the decision tree  
   * Display feature importances  
   * Perform 5-fold cross-validation  

---

## 📈 Evaluation Metrics

* **Accuracy**  
* **Classification Report** (Precision, Recall, F1-score)  
* **Cross-validation mean and standard deviation**  

---

## 📚 References

* [Pima Indians Diabetes Dataset on Kaggle](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)  
* [Scikit-learn Documentation](https://scikit-learn.org/)  
