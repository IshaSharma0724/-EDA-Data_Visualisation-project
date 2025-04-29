# 📊 Project 2: Iris Dataset - Analysis & Visualization

## 📌 Overview
This project focuses on the Iris dataset to perform data cleaning, exploratory data analysis (EDA), and visualizations using Python libraries like pandas, seaborn, and matplotlib.  
The objective is to explore relationships between flower dimensions (sepal/petal) and species classification.

---

## 🛠️ Tools Used
- Python (Google Colab)
- Pandas
- Matplotlib
- Seaborn

---

## 🧹 Step 1: Data Cleaning
- Checked and confirmed no missing values or duplicates.
- Verified correct data types.

---

## 📊 Step 2: Data Visualization

### 🔹 Scatter Plot: Petal Length vs Petal Width
```python
sns.scatterplot(x='petal_length', y='petal_width', hue='species', data=df)
plt.title('Petal Length vs Petal Width by Species')
plt.show()
```
**Observation:**
- Each species forms a distinct cluster.
- Setosa has the smallest petals.
- Virginica has longer and wider petals.
- Petal dimensions are useful for classifying species.

---

### 🔹 Pairplot (All Features by Species)
```python
sns.pairplot(df, hue='species')
plt.show()
```
**Observation:**
- Petal features (length and width) show clear separation between species.
- Sepal features show more overlap, especially sepal width.
- Petal features are more effective for classification.

---

## ✅ Conclusion
- Petal features are better predictors of species than sepal features.
- Visualization provides clear species groupings and data patterns.

---

## 📎 Files Included
- `iris_analysis.ipynb` – Full Jupyter/Colab notebook
- `cleaned_iris.csv` – Cleaned dataset
- Visual outputs and markdown explanations included

---
## AUTHOR

**ISHA SHARMA**

GITHUB: IshaSharma0724
  

