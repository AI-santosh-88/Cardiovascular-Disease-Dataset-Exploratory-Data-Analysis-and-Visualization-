
# TITLE : Cardiovascular Disease Dataset: Exploratory Data Analysis and Visualization using Python

## Description : 
This project implements a comprehensive exploratory data analysis (EDA) pipeline on a cardiovascular disease dataset. The methodology encompasses statistical analysis and data visualization techniques to characterize the dataset's statistical properties, identify potential data quality issues (e.g., outliers), and uncover underlying relationships between predictor variables and the target variable (presence/absence of heart disease). The analysis is performed using Python's scientific computing ecosystem, focusing on univariate, bivariate, and multivariate analysis.

## Responsibilities :
#### Data Ingestion and Preprocessing: 
* Loading the dataset from a CSV file using Pandas' read_csv() function. Initial data inspection includes determining dataset dimensionality (shape), data types (dtypes), and generating descriptive statistics (describe()).

#### Univariate Statistical Analysis: 
* Analyzing the distribution of individual variables. For categorical variables (e.g., 'target'), frequency counts (value_counts()) and count plots are used. For numerical variables (e.g., 'age', 'thalach'), descriptive statistics (mean, median, standard deviation, etc.) and distribution plots (histograms, KDE plots) are generated.

#### Bivariate Statistical Analysis: 
* Investigating relationships between pairs of variables. Correlation analysis (Pearson's r) is performed to quantify linear relationships. Categorical-numerical relationships are explored using grouped statistics (groupby()) and visualizations like strip plots and box plots.

#### Multivariate Statistical Analysis: 
* Examining relationships among multiple variables. Correlation matrices and heatmaps are generated to visualize inter-variable correlations. Pair plots are used to visualize pairwise relationships between multiple numerical variables.

#### Data Quality Assessment:
* Checking for missing values using isnull() and notnull() functions. Outlier detection is performed using box plots to identify data points falling outside the interquartile range (IQR).
Data Visualization: Generating informative visualizations using Matplotlib and Seaborn libraries. This includes histograms, KDE plots, count plots, strip plots, box plots, scatter plots, heatmaps, and pair plots.

## Libraries Used :
#### 1.NumPy (Numerical Python): 
* Provides fundamental numerical computing capabilities, including array operations and mathematical functions.
#### 2.Pandas (Python Data Analysis Library): 
* Offers data structures (DataFrames) and functions for data manipulation, analysis, and I/O.
#### 3.Seaborn: 
* Built on top of Matplotlib, provides a high-level interface for creating statistically informative and visually appealing graphics.
#### 4.Matplotlib: 
* A comprehensive library for creating static, interactive, and animated visualizations in Python.
#### 5.SciPy.stats (Scientific Python - Statistics): 
* Provides statistical functions and distributions.

## Summary : 
* This project conducts a rigorous EDA on a cardiovascular disease dataset. The analysis employs a combination of descriptive statistics, correlation analysis, and data visualization techniques to characterize the dataset, identify potential data anomalies, and explore relationships between variables. The use of Python's scientific computing libraries (NumPy, Pandas, Seaborn, Matplotlib, SciPy.stats) facilitates efficient data manipulation, statistical analysis, and the creation of informative visualizations. The results of this EDA provide a foundation for subsequent data preprocessing, feature engineering, and predictive modeling tasks.
