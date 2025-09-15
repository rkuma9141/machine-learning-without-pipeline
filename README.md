# Machine Learning Project (Without Pipeline)

This project explains how to build a Machine Learning model **without using Scikit-Learn Pipelines**.  
We manually handle each step: data preprocessing, feature engineering, encoding, scaling, model training, evaluation, and prediction.  

---

## 📌 Project Workflow

### 1. Import Required Libraries
```python
import pandas as pd
import numpy as np
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import OneHotEncoder, StandardScaler
from sklearn.linear_model import LogisticRegression
from sklearn.metrics import accuracy_score, classification_report
