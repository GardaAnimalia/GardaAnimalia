# Import necessary libraries for data analysis and visualization
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
%matplotlib inline  # Display plots inline in Jupyter notebooks
sns.set_style("whitegrid")  # Set the seaborn plot style to whitegrid
# Set warning filters to ignore warnings
import warnings
warnings.filterwarnings('ignore')

# Configure pandas to display all columns of a DataFrame
pd.pandas.set_option('display.max_columns', None)
