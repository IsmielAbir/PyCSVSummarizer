# PyCSVSummarizer

[![PyPI version](https://img.shields.io/pypi/v/PyCSVSummarizer)](https://pypi.org/project/PyCSVSummarizer/)

A simple Python package to **summarize CSV files** using various features.

---

## Features
- Total Rows and Columns
- Column Names
- File Size
- Estimated Memory Usage
- Null Counts and Percentages
- Duplicate Rows
- Top Frequent Values
- Unique Values Per Column
- Numeric vs Categorical Columns
- Basic Stats (mean, min, max)
- Columns with Constant Values
- Largest Columns by Memory

---

## Installation

```bash
pip install PyCSVSummarizer
```

## Usage

```bash
from PyCSVSummarizer import CSVSummarize

CSVSummarize('path_to_your_file.csv')
```
