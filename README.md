<div align="center">

# 🚀 Pandas Data Engineering & Analysis Journey
*A comprehensive, interactive showcase of data manipulation, cleaning, aggregation, and exploratory data analysis using Python and Pandas.*

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-2.0%2B-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)]()

</div>

---

## 📊 Interactive Journey Dashboard

> **Quick Stats Overview**
> * **Total Modules Completed:** 7 / 7
> * **Core Concepts Mastered:** Series, DataFrames, Indexing, Data Cleaning, GroupBy, Merging & Advanced EDA
> * **Primary Focus:** Exploratory Data Analysis (EDA) & Data Wrangling

| Module ID | Module Title | Core Concepts Covered | Status | Complexity | Notebook Link |
| :---: | :--- | :--- | :---: | :---: | :---: |
| **01** | **Pandas Series Basics** | 1D Data Structures, Indexing, Vectorized Operations | 🟢 Completed | Beginner | [View Notebook](pandas_series.ipynb) |
| **02** | **DataFrames Mastery** | 2D Tabular Structures, Selection, Conditional Filtering | 🟢 Completed | Intermediate | [View Notebook](pandas_dataframes.ipynb) |
| **03** | **Handling Missing Data** | Null Detection, Imputation Strategies, Data Dropping | 🟢 Completed | Intermediate | [View Notebook](pandas_missing_data.ipynb) |
| **04** | **Indexing & Selection** | Multi-indexing, Conditional Slicing, `.loc[]` / `.iloc[]` | 🟢 Completed | Intermediate | [View Notebook](pandas_indexing.ipynb) |
| **05** | **Data Aggregation & Groupby** | Split-Apply-Combine, Pivot Tables, Statistical Summaries | 🟢 Completed | Advanced | [View Notebook](pandas_groupby.ipynb) |
| **06** | **Merging & Joining Data** | Concat, Merge, Inner/Outer Joins, Data Integration | 🟢 Completed | Advanced | [View Notebook](pandas_merging.ipynb) |
| **07** | **Advanced EDA & Export** | String Operations, Datetime Parsing, Data Visualization | 🟢 Completed | Advanced | [View Notebook](pandas_eda_export.ipynb) |

---

## 🧠 Comprehensive Module Breakdown

### 1. Pandas Series Basics (`pandas_series.ipynb`)
* **Objective:** Understand one-dimensional labeled data structures capable of holding any data type.
* **Key Technical Takeaways:**
  * Initializing Series from Python lists, dictionaries, and NumPy arrays.
  * Custom labeling and explicit vs. implicit index lookup.
  * Performing element-wise vectorized arithmetic and mathematical transformations.

### 2. DataFrames Mastery (`pandas_dataframes.ipynb`)
* **Objective:** Master two-dimensional, size-mutable, potentially heterogeneous tabular data structures.
* **Key Technical Takeaways:**
  * Constructing DataFrames from multi-source dictionaries and loading external datasets.
  * Multi-column selection, row slicing, and advanced boolean masking/filtering.
  * Creating derived columns and initial data evaluation workflows.

### 3. Handling Missing Data (`pandas_missing_data.ipynb`)
* **Objective:** Identify, isolate, and remediate missing or null values to maintain dataset integrity.
* **Key Technical Takeaways:**
  * Detecting nulls using `.isnull()`, `.notnull()`, and summary heatmaps.
  * Safe data cleaning strategies: dropping missing records vs. advanced imputation.
  * Preventing downstream data pipeline errors due to `NaN` propagation.

### 4. Indexing & Selection (`pandas_indexing.ipynb`)
* **Objective:** Master precise data slicing, hierarchical index manipulation, and row/column extraction.
* **Key Technical Takeaways:**
  * Leveraging `.loc[]` for label-based and `.iloc[]` for position-based indexing.
  * Setting, resetting, and swapping multi-level index structures.
  * Applying complex boolean masking for targeted row modifications.

### 5. Data Aggregation & Groupby (`pandas_groupby.ipynb`)
* **Objective:** Implement the Split-Apply-Combine paradigm to extract high-level statistical insights.
* **Key Technical Takeaways:**
  * Grouping data by single or multiple categorical keys.
  * Applying aggregate functions (`mean`, `sum`, `agg`, `transform`, `filter`).
  * Creating multi-dimensional pivot tables and crosstabs.

### 6. Merging & Joining Data (`pandas_merging.ipynb`)
* **Objective:** Combine disparate datasets horizontally and vertically like a relational database.
* **Key Technical Takeaways:**
  * Performing SQL-style joins (`inner`, `outer`, `left`, `right`) using `.merge()`.
  * Concatenating dataframes along axes using `pd.concat()`.
  * Handling overlapping column names and resolving key mismatches.

### 7. Advanced EDA & Export (`pandas_eda_export.ipynb`)
* **Objective:** Perform robust Exploratory Data Analysis, clean unstructured text, handle datetimes, and export processed outputs.
* **Key Technical Takeaways:**
  * Vectorized string manipulation (`.str.lower()`, `.str.replace()`, regex extraction).
  * Datetime parsing, frequency resampling, and time-series extraction.
  * Exporting cleaned datasets to CSV, JSON, and Parquet formats.

---

## 🛠️ Repository Structure & Navigation

```text
pandas-journey/
│
├── pandas_series.ipynb       # Module 1: Series fundamentals & vectorization
├── pandas_dataframes.ipynb   # Module 2: DataFrame creation, selection & filtering
├── pandas_missing_data.ipynb # Module 3: Detection & remediation of missing values
├── pandas_indexing.ipynb     # Module 4: Advanced indexing & slicing techniques
├── pandas_groupby.ipynb      # Module 5: Aggregation & Split-Apply-Combine patterns
├── pandas_merging.ipynb      # Module 6: Data integration via joins & concatenation
├── pandas_eda_export.ipynb   # Module 7: Datetime, string ops, and export pipelines
└── README.md                 # Interactive dashboard & documentation
```

---

## ⚙️ Getting Started & Installation

To run these notebooks locally on your machine, clone this repository and install the dependencies:

```bash
# Clone the repository
git clone https://github.com/parvezadnan07/pandas-journey.git

# Navigate into the directory
cd pandas-journey

# Install required packages
pip install pandas numpy jupyter
```

---

## 🤝 Contribution & Feedback

Contributions, suggestions, and feedback are always welcome! If you find any bugs or want to suggest improvements to these notebooks:
1. Open an issue on the [Issues Tab](https://github.com/parvezadnan07/pandas-journey/issues).
2. Submit a Pull Request with your proposed enhancements.

<div align="center">
  <sub>Built with passion and persistence by <a href="https://github.com/parvezadnan07">Parvez Adnan</a></sub>
</div>
