<h1 align="center">🍽️ Chipotle Data Analysis with Pandas</h1>

<p align="center">
  A beginner-friendly data analysis project exploring Chipotle restaurant orders using Python & Pandas.
</p>

---

## 📂 Project Overview

This project demonstrates how to work with real-world data using the Python library **Pandas**.  
We analyze a dataset from Chipotle’s order history to gain insights into customer behavior and popular items.

> 🔗 Dataset Source: [Chipotle Dataset (TSV format)](https://raw.githubusercontent.com/justmarkham/DAT8/master/data/chipotle.tsv)

---

## 🚀 Technologies Used

- 🐍 Python 3
- 📊 Pandas
- 📒 Jupyter Notebook

---

## 🧠 What You’ll Learn

- How to import tab-separated (`.tsv`) datasets
- Basic data wrangling and exploration
- Using `.head()`, `.info()`, `.describe()`
- Grouping, filtering & summarizing data
- Real-world application of Pandas functions

---

## 📌 Highlights from the Analysis

- ✅ Loaded dataset directly from a URL using `pd.read_csv()`
- ✅ Explored the top rows and structure of the dataset
- ✅ Identified popular items & total revenue
- ✅ Found total number of orders and unique item counts
- ✅ Grouped data to find insights (like most ordered items)

---

## 🧾 How to Run This Notebook

1. 📥 Download or clone this repository.
2. 🧠 Open `Pandas_project_done.ipynb` using Jupyter Notebook or Google Colab.
3. ▶️ Run the cells one by one to see the analysis in action.
4. 🔍 Modify it and try your own queries!

---

## 📸 Preview

```python
# Load dataset from GitHub
url = 'https://raw.githubusercontent.com/justmarkham/DAT8/master/data/chipotle.tsv'
df = pd.read_csv(url, sep='\t')

# First 10 rows
df.head(10)
