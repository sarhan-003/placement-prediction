# 🎓 Placement Prediction using Machine Learning

## 📌 Project Overview

This project predicts whether a student will get placed or not based on academic performance and other factors using **Machine Learning classification algorithms**.

The model is trained on a dataset containing student details such as academic scores and test results. After training, the model predicts the **placement status (Placed / Not Placed)**.

---

## 🚀 Features

* Data preprocessing and cleaning
* Machine Learning model training
* Accuracy evaluation of the model
* Decision boundary visualization
* Placement prediction based on student data

---

## 🗂️ Project Structure

```
placement-prediction/
│
├── placement.csv                # Dataset used for training
├── placement_prediction.ipynb   # Jupyter Notebook with full ML workflow
└── README.md                    # Project documentation
```

---

## 🧠 Machine Learning Workflow

### 1️⃣ Import Libraries

The following libraries are used:

* pandas
* numpy
* matplotlib
* scikit-learn
* mlxtend

---

### 2️⃣ Data Loading

Dataset is loaded from:

```
placement.csv
```

It contains student academic details and placement status.

---

### 3️⃣ Data Preprocessing

Steps performed:

* Checking missing values
* Selecting important features
* Splitting data into **training and testing sets**

---

### 4️⃣ Model Training

A **classification algorithm** is used to train the model on the dataset.

The model learns patterns between student scores and placement results.

---

### 5️⃣ Model Evaluation

Model performance is evaluated using **Accuracy Score**.

Example result from the model:

```
Accuracy = 0.90
```

This means the model predicts correctly **90% of the time**.

---

### 6️⃣ Decision Boundary Visualization

Using `mlxtend` library, the decision regions are plotted to visualize how the model separates placed and not placed students.

```
from mlxtend.plotting import plot_decision_regions
```

This helps understand how the model classifies data points.

---

## 📊 Technologies Used

* Python
* Jupyter Notebook
* Scikit-learn
* Pandas
* NumPy
* Matplotlib
* Mlxtend

---

## ⚙️ Installation

Clone the repository:

```
git clone https://github.com/sarhan-003/placement-prediction.git
```

Navigate to the project folder:

```
cd placement-prediction
```

Install required libraries:

```
pip install pandas numpy matplotlib scikit-learn mlxtend
```

Run the Jupyter Notebook:

```
jupyter notebook
```

Open:

```
placement_prediction.ipynb
```

---

## 📈 Future Improvements

* Add more features to improve prediction accuracy
* Deploy the model as a **web application**
* Build a **student placement prediction dashboard**

---

## 👨‍💻 Author

**Sarhan Bakarman**

GitHub:
https://github.com/sarhan-003

---

⭐ If you like this project, give it a star on GitHub!
