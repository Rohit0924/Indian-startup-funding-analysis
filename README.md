# Indian-startup-funding-analysis

Here’s a `README.md` for your `main.py` project:

---

# Startup Funding Analysis

## 📌 Overview

This project analyzes startup funding data from **`startup_funding.csv`** to identify trends, top sectors, cities, startups, investors, and investment types. It performs data cleaning, aggregation, and visualization.

## 📂 Files

* **`main.py`** → Python script for data cleaning, analysis, and visualization.
* **`startup_funding.csv`** → Dataset containing startup funding details (must be placed in the correct directory).

## 🛠 Requirements

Install the required Python libraries:

```bash
pip install pandas matplotlib seaborn
```

## 📊 Features

1. **Data Cleaning**

   * Removes unnecessary columns.
   * Fills missing values with `"Unknown"`.
   * Cleans numeric fields and converts to proper data types.
   * Handles inconsistent formats and converts to lowercase.

2. **Feature Engineering**

   * Extracts **Funding Year** and **Funding Month**.

3. **Analysis**

   * Yearly and monthly funding trends.
   * Top 10 sectors, cities, startups, and investors (by funding and deals).
   * Investment type summaries.

4. **Visualization**

   * Line plots for trends.
   * Bar plots for top categories.

## ▶️ How to Run

```bash
python main.py
```

Ensure that:

* `startup_funding.csv` is in the same directory or update the file path in `main.py`.
* All dependencies are installed.

## 📈 Output

The script will:

* Print cleaned dataset info.
* Display top categories and trends.
* Show visualizations for each analysis.

---
