# U.S.-Housing-Market-Time-Series-Analysis

## ⭐ **Overview**

This project analyzes long-term trends in the U.S. housing market using time-series data from the Federal Reserve Economic Data (FRED). It explores **median home prices**, **mortgage rates**, **housing starts**, and **vacant housing units** from 2005–2025 to understand market behavior, economic cycles, and post-crisis recovery patterns.

The analysis combines **data cleaning**, **multi-series integration**, **exploratory visualization**, **correlation analysis**, and **event-driven trend interpretation**—all implemented in **Python (Pandas, Matplotlib, Seaborn)**.

> This repository demonstrates my ability to work with real-world economic datasets, produce analytical visualizations, interpret time-dependent relationships, and communicate insights clearly—key skills for data analytics and data science roles. 

---

## 🗂️ **Datasets Used**

All datasets originate from FRED and represent critical U.S. housing market indicators:

| Variable                          | Description                              |
| --------------------------------- | ---------------------------------------- |
| **Median_Home_Price (MSPUS)**     | Median sales price of homes sold         |
| **Mortgage_Rate (MORTGAGE30US)**  | 30-year fixed mortgage rate              |
| **Housing_Starts (HOUST)**        | New privately-owned housing construction |
| **Vacant_Units (EVACANTUSQ176N)** | Total vacant housing units               |

The datasets were merged using **temporal indexing**, cleaned for missing values, and aligned into a unified multi-series dataframe. 

---

## 🛠️ **Tech Stack**

* **Python**

  * Pandas
  * NumPy
  * Matplotlib
  * Seaborn
* **Jupyter/Colab**
* **Time Series Concepts**

  * Trend analysis
  * Rolling averages
  * Multi-series comparison
  * Correlation & dual-axis visualizations

---

## 📈 **Key Insights (Executive Summary)**

### 🔹 **1. Home Prices Show Strong Long-Term Growth**

Median home prices increased **80%** from 2009 to 2021, with especially sharp acceleration during the COVID-19 period.
The line chart (page 5) and rolling average chart (page 11) highlight this clear upward trajectory. 

### 🔹 **2. Mortgage Rates Fell to Historic Lows**

30-year mortgage rates declined from **5.08% → 2.88%**, reaching record lows around 2020. This drop played a major role in stimulating buyer demand.
(Visualized on page 6.) 

### 🔹 **3. Strong Inverse Relationship Between Home Prices & Mortgage Rates**

A correlation of **–0.95** indicates a powerful negative relationship:

> *As rates fall, prices rise.*
> (Heatmap on page 10.) 

### 🔹 **4. Housing Starts Increased—but Not Enough**

New construction nearly tripled, from **534k → 1.59M**, yet vacant units *fell*, indicating supply still lagged demand.
(Pages 6–7 and page 10.) 

### 🔹 **5. Major Economic Events Had Drastic Effects**

* **2008 financial crisis** → Suppressed prices & construction
* **2020 pandemic** → Triggered price surge due to low rates, migration, and supply shortages

The annotated event graph (page 12) clearly illustrates these shifts. 

---

## 🔍 **What This Project Demonstrates**

✔ **Ability to work with real-world messy datasets**
✔ **Time-series cleaning, merging & preprocessing**
✔ **Creation of multi-metric visual dashboards**
✔ **Economic pattern interpretation**
✔ **Clear written communication of analytical insights**
✔ **Professional visualization skills**
✔ **End-to-end project workflow—from sourcing to storytelling**

Recruiters can expect the same structured approach from me in real analytics settings.

---

## 📊 **Visuals Included**

This project includes:

* Trend lines for each housing indicator
* Rolling averages
* Dual-axis comparison charts
* Multi-metric dashboards
* Correlation heatmaps
* Event-annotated economic cycles

All visuals are implemented programmatically using Python and Seaborn.
(See pages 5–12 for examples.) 

---

## 🧩 **Project Structure**

```plaintext
├── data/                # CSVs from FRED (not included here)
├── notebooks/           # Colab/Jupyter analysis notebook
├── visualizations/      # Exported plots
├── README.md            # Project documentation
└── analysis_report.pdf  # Final written analysis (from your assignment)
```

## 🙌 **About the Author**

**Rian Renold Dbritto**
Graduate Student, MS Data Analytics Engineering — Northeastern University
Passionate about data visualization, time series modeling, and translating numbers into clear, actionable insights.




