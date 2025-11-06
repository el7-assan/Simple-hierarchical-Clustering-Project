# Simple-hierarchical-Clustering-Project
This project applies the hierarchical Clustering algorithm to group mall customers based on their Annual Income and Spending Score.

##  Dataset

The dataset used is **`Mall_Customers.csv`**.

Each customer is described by:
- **CustomerID**
- **Gender**
- **Age**
- **Annual Income (k$)** — yearly income
- **Spending Score (1–100)** — spending score assigned by the mall

---

##  Libraries Used
```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn.cluster import AgglomerativeClustering
import  scipy.cluster.hierarchy as sch
