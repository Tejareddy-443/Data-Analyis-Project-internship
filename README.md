# 📊 Data Immersion & Wrangling Project

## 🎯 Objective
The objective of this project is to understand the process of data immersion, data quality assessment, data cleaning, and transformation using Python and Pandas. The final goal is to prepare an analysis-ready dataset for business insights and decision-making.

---

# 📁 Dataset Used

Dataset Name: Sample Superstore Dataset

Source:
https://www.kaggle.com/datasets/vivek468/superstore-dataset-final

The dataset contains sales transaction details including:
- Orders
- Customers
- Products
- Sales
- Profit
- Shipping details

---

# 🛠 Tools & Technologies Used

- Python
- Pandas
- NumPy
- VS Code / Jupyter Notebook
- Git & GitHub

---

# 🔹 Project Workflow

## 1️⃣ Data Access & Familiarization

- Loaded dataset using Pandas
- Explored dataset structure
- Checked:
  - Number of rows and columns
  - Column names
  - Data types
  - Sample records

### Sample Code

```python
import pandas as pd

df = pd.read_csv("Sample_Superstore.csv", encoding='latin1')

print(df.head())
print(df.info())