# 🎓 Student Placement Prediction

A machine learning classification project that predicts whether a student is likely to be **Placed** or **Not Placed** based on their academic performance, technical skills, internships, projects, aptitude, communication skills, certifications, and other student attributes.

---

## 📌 About the Project

The purpose of this project is to build a machine learning model that can identify patterns between a student's academic and skill-based profile and their placement outcome.

The model uses **12 input features** and predicts a binary placement outcome:

* `0` → Not Placed
* `1` → Placed

This project was built as part of my initial journey into Machine Learning to understand the complete process of developing and evaluating a classification model.

---

## 📊 Dataset Features

| Feature        | Description                             |
| -------------- | --------------------------------------- |
| Age            | Student's age                           |
| Gender         | `0 = Female`, `1 = Male`                |
| CGPA           | Student's CGPA                          |
| Internships    | Number of internships completed (`0–3`) |
| Projects       | Number of projects completed            |
| Coding         | Coding skill rating (`1–10`)            |
| Communication  | Communication skill rating (`1–10`)     |
| Aptitude       | Aptitude score (`0–100`)                |
| Soft Skills    | Soft skills rating (`1–10`)             |
| Certifications | Number of certifications (`0–3`)        |
| Branch         | Student's academic branch               |
| Degree         | Degree type                             |

### Branches

`CSE` · `Civil` · `ECE` · `IT` · `ME`

### Degree Encoding

| Value | Degree |
| ----: | ------ |
|     1 | BSc    |
|     2 | BTech  |
|     3 | BCA    |
|     4 | MCA    |

---

## 🧠 Machine Learning

### Problem Type

**Binary Classification**

### Target

`Placement`

The model predicts whether a student will be:

```text
Placed
Not Placed
```

### Workflow

```text
Raw Dataset
     ↓
Data Preprocessing
     ↓
Feature Encoding
     ↓
Train / Test Split
     ↓
Model Training
     ↓
Prediction
     ↓
Model Evaluation
```

---

## 📈 Model Performance

The model achieved an accuracy of:

### **95.54%**

```text
Accuracy: 0.9554444444444444
```

### Confusion Matrix

```text
[[5308  401]
 [   0 3291]]
```

| Actual / Predicted | Not Placed | Placed |
| ------------------ | ---------: | -----: |
| **Not Placed**     |       5308 |    401 |
| **Placed**         |          0 |   3291 |

### Classification Report

| Class            | Precision |   Recall | F1-Score |
| ---------------- | --------: | -------: | -------: |
| Not Placed       |      1.00 |     0.93 |     0.96 |
| Placed           |      0.89 |     1.00 |     0.94 |
| **Macro Avg**    |  **0.95** | **0.96** | **0.95** |
| **Weighted Avg** |  **0.96** | **0.96** | **0.96** |

**Test samples:** 9,000

---

## 🧪 Example Prediction

### Student Input

```text
Age            : 19
Gender         : 1
CGPA           : 9
Internships    : 2
Projects       : 5
Coding         : 9
Communication  : 9
Aptitude       : 70
Soft Skills    : 6
Certifications : 0
Branch         : CSE
Degree         : BSc
```

These features are passed to the trained model to generate the student's predicted placement outcome.

---

## 🛠️ Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Scikit-learn**
* **Matplotlib**
* **Jupyter Notebook**

---


## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/ayushahirrao2007/Placement-Prediction--Machine-learning.git
```

### 2. Navigate to the project

```bash
cd Placement-Prediction--Machine-learning
```

### 4. Run the notebook

```bash
jupyter notebook
```

Open the placement prediction notebook and run the cells to train and evaluate the model.

---

## 📋 Requirements

```text
pandas
numpy
scikit-learn
matplotlib
jupyter
```

## 🎯 What I Learned

Through this project, I learned the fundamentals of building a machine learning classification model, including:

* Loading and understanding a dataset
* Data preprocessing
* Encoding categorical variables
* Splitting data into training and testing sets
* Training a classification model
* Making predictions
* Evaluating model performance
* Understanding confusion matrices
* Evaluating Precision, Recall and F1-score

---

## ⚠️ Disclaimer

This project is created for **educational purposes**.

A student's actual placement depends on many factors that may not be represented in this dataset. Therefore, the model's prediction should not be considered a guarantee of placement.

---

## 👨‍💻 Author

AI & Machine Learning Enthusiast

[GitHub](https://github.com/ayushahirrao2007)
