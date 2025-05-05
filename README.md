# 🧱 LEGO Data Analysis: Exploring the Brick by Brick

Welcome to the LEGO Data Analysis project! This notebook takes you on a data-driven journey through the iconic world of LEGO, combining storytelling, exploration, and advanced analytics to uncover fascinating insights from the LEGO dataset hosted on [Kaggle](https://www.kaggle.com/datasets/rtatman/lego-database).

> 🔍 This notebook is designed not only to explore the data, but to **showcase the skills of a data scientist** — from EDA and data cleaning, to beautiful visual storytelling, clustering, and interactive dashboards.

---

## 📚 Dataset Overview

The dataset consists of **eight interrelated CSV files** that form a relational database of LEGO sets, parts, themes, and colors:

| File | Description |
|------|-------------|
| `colors.csv` | All LEGO brick colors and metadata |
| `inventories.csv` | Inventory versions for each LEGO set |
| `inventory_parts.csv` | Parts and colors used per inventory |
| `inventory_sets.csv` | Links inventories back to sets |
| `part_categories.csv` | High-level categories for parts |
| `parts.csv` | Part numbers and names |
| `sets.csv` | Each LEGO set with metadata like year and theme |
| `themes.csv` | LEGO themes and sub-themes |

The relational schema is illustrated early in the notebook to guide joins and analysis.

---

## 📊 Highlights of the Analysis

### ✅ Step-by-Step Workflow

- **Step 1:** Import libraries and load all datasets
- **Step 2:** Clean and validate datatypes
- **Step 3:** Profile datasets with missing value checks, shapes, dtypes, and duplicates
- **Step 4:** Relational schema understanding and EDA plan

### 📈 Visual Explorations

- Top LEGO sets by piece count, year, and theme
- Most popular LEGO themes and their evolution
- A **treemap of themes and sets**
- Color analysis including:
  - Interactive color frequency charts
  - Circle-packed bubble plots using true LEGO color codes

### 🤖 Advanced Analytics

- **Clustering LEGO Sets by Complexity** using K-Means
- **Dimensionality reduction with PCA** to explore trends
- **Interactive Plotly dashboards** to explore themes, years, and part complexity

---

## 💡 Key Skills Demonstrated

- 🧼 Data Cleaning & Validation
- 🔗 Relational Database Merging
- 📊 Data Visualization (Matplotlib, Seaborn, Plotly, Circlify)
- 🧠 Machine Learning (Clustering with K-Means)
- 🎨 Color Theory in Data Design
- ✨ Notebook Design for Storytelling & Flow

---

## 🚀 Running the Notebook

> ✅ Make sure you have the datasets locally downloaded in a directory like:
> `/Users/yourname/Downloads/Lego Data`

Required Python libraries:
```bash
pip install pandas matplotlib seaborn plotly scikit-learn circlify
