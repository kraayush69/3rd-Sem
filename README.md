#3rd lab Project files
# Data Visualization 

import pandas as pd
import seaborn  as sns
import matplotlib.pyplot as plt

def load_dataset(file_path):
  return pd.read_csv(file_path)
df = load_dataset("./Health_heart_experimental.csv")
df.head(10)

