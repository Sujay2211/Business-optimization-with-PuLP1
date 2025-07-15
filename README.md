# 🧃 Juice Product Mix Optimization using Linear Programming

This project demonstrates how to solve a **real-world product mix optimization problem** using Python and the `PuLP` library for Linear Programming (LP).

A fictional juice factory produces:
- 🍎 Apple Juice
- 🍊 Orange Juice
- 🍇 Mixed Fruit Juice

The goal is to **maximize profit** given limited resources like machine hours and labor time.

---

## 📌 Problem Description

| Product             | Profit/unit (₹) | Machine Time (hrs) | Labor Time (hrs) | Max Units |
|---------------------|------------------|----------------------|-------------------|-----------|
| Apple Juice         | 25               | 3                    | 2                 | 60        |
| Orange Juice        | 30               | 2                    | 3                 | 60        |
| Mixed Fruit Juice   | 40               | 4                    | 4                 | 60        |

### 🔧 Constraints:
- Max available machine time: **240 hours**
- Max available labor time: **220 hours**

---

## ✅ Features

- ✔️ Linear Programming formulation using `PuLP`
- 📊 Visualization of optimal product mix using `matplotlib`
- 📥 Optional data input from Excel (simulated in this version)
- 🔁 Basic sensitivity analysis to test how changes in resources affect output

---

## 📁 Files

| File Name                               | Description                              |
|----------------------------------------|------------------------------------------|
| `Juice_Product_Mix_Optimization.ipynb` | Main Jupyter notebook                    |
| `README.md`                             | This documentation                       |
| *(Optional)* `juice_data.xlsx`         | Excel file with input data (not included)|

---

## 📦 Requirements

- Python 3.7+
- PuLP
- Pandas
- Matplotlib

### 🔧 Install via pip:

```bash
pip install pulp pandas matplotlib

  
