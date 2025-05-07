# Sales Analysis of Trial vs. Control Store

## Overview
This Python script performs a basic analysis of a retail dataset to compare the performance of a trial store against a control store. It calculates the total sales revenue, the number of customers, average transactions, and compares sales performance between the two stores.

## Libraries Used
- **NumPy**: For numerical operations.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib**: For data visualization (though not utilized here, you can enhance visualizations).
- **Seaborn**: For data visualization (optional, could be used for further improvements in visual analysis).

## Data
- **Dataset Source**: The dataset is loaded from an Excel file, `QVI_transaction_data.xlsx`, which contains sales transaction data with columns such as `TOT_SALES`, `TXN_ID`, `STORE_NBR`, etc.
  
## Code Explanation

### 1. Importing Libraries
```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
