# --- Step 1: Import Libraries ---
import pandas as pd
import matplotlib.pyplot as plt

# --- Step 2: Load CSV file ---
# Replace 'sales.csv' with your file path
df = pd.read_csv("sales.csv")

# --- Step 3: Explore Data ---
print("First 5 rows:")
print(df.head())

print("\nShape of DataFrame:", df.shape)
print("\nColumns:", df.columns)
print("\nBasic Info:")
print(df.info())

# --- Step 4: Groupby & Aggregation ---
# Example
