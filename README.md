# Wine Quality (Red) – EDA Project 🍷

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the **Red Wine Quality** dataset using **Python**, **Pandas**, and **Matplotlib**.

The main goals are to:
- Understand the structure of the wine quality dataset.
- Explore how different chemical properties affect wine quality.
- Visualize patterns and relationships using simple plots.

---

## 📂 Dataset

- **File used**: `winequality-red.csv`  
- **Source**: UCI Machine Learning Repository (Red Wine Quality dataset)  
- **Separator**: `;` (semicolon)

### 🔢 Columns in the dataset

Each row represents a red wine sample with these features:

- `fixed acidity`
- `volatile acidity`
- `citric acid`
- `residual sugar`
- `chlorides`
- `free sulfur dioxide`
- `total sulfur dioxide`
- `density`
- `pH`
- `sulphates`
- `alcohol`
- `quality` (target: wine quality score, usually 0–10)

---

## 🛠️ Technologies Used

- **Language**: Python  
- **Libraries**:
  - `pandas` – data loading and analysis
  - `matplotlib.pyplot` – data visualization

---

## 📜 Basic Code Setup

```python
import pandas as pd
import matplotlib.pyplot as plt

# Load dataset
df = pd.read_csv("winequality-red.csv", sep=";")

## 🔍 EDA Steps (Planned / Typical)

You can include (or may have already done) the following:

---

## 1. Basic Inspection

```python
df.head()
df.tail()
df.shape
df.info()
df.isnull().sum()

df.describe()
df["alcohol"].hist(bins=20)
plt.xlabel("Alcohol")
plt.ylabel("Count")
plt.title("Alcohol Distribution")
plt.show()
df.groupby("quality")["alcohol"].mean().plot(kind="bar")
plt.xlabel("Quality")
plt.ylabel("Average Alcohol")
plt.title("Average Alcohol by Wine Quality")
plt.show()

# 📈 Possible Extensions

- Add more visualizations (boxplots, scatter plots)  
- Check correlation between features  
- Build a simple ML model to predict wine quality  

---

# 👩‍💻 Author

Name: Sneha Chaudhary  
Role: Data Science Intern & B.Tech CSE Student  
GitHub: github.com/snehachaudhary1528-cmd  
LinkedIn: linkedin.com/in/sneha-chaudhary  


