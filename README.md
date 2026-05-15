# NumPy Exercises for Data Analysis

[![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)](https://numpy.org)
[![Python](https://img.shields.io/badge/Python-3.7+-blue.svg)](https://python.org)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## 📌 Overview

**130 NumPy exercises** for data analysis - from basics to advanced missing value handling, outlier detection, and visualization.

## 📚 What's Inside

| Section | Exercises | Topics |
|---------|-----------|--------|
| NumPy Basics | 1-30 | Arrays, indexing, reshaping, broadcasting |
| Advanced NumPy | 31-70 | Structured arrays, linear algebra, vectorization |
| Data Science | 71-100 | Iris dataset, statistics, normalization, bootstrapping |
| **Data Analysis** | **101-130** | **Missing values, outliers, visualization** |

## 🎯 Data Analysis Exercises (101-130)

### Missing Values
- Detect and count NaN values
- Drop rows with missing data
- Imputation: mean, median, forward/backward fill
- Interpolation, KNN, regression imputation

### Outlier Detection
- IQR (Interquartile Range) method
- Z-score method
- Mahalanobis distance
- Rolling statistics for time series

### Outlier Treatment
- Capping at percentiles
- Winsorization
- Median replacement

### Visualization
- Histograms, box plots, violin plots
- Heatmaps, scatter plots, pair plots
- Q-Q plots for normality testing

## 🚀 Quick Start



# Install dependencies
pip install numpy matplotlib seaborn pandas scipy jupyter

# Launch notebook
jupyter notebook 130_Numpy_exercises.ipynb
📖 Exercise Format
python
# EXERCISE 108: Detect outliers using IQR method
# Difficulty: ★★☆

# Your code here:
data = np.array([10, 12, 14, 100, 13, 200])
Q1, Q3 = np.percentile(data, [25, 75])
IQR = Q3 - Q1
outliers = data[(data < Q1 - 1.5*IQR) | (data > Q3 + 1.5*IQR)]
📊 Difficulty Levels
★☆☆ - Beginner (basic syntax & operations)

★★☆ - Intermediate (reshaping, aggregations)

★★★ - Advanced (complex algorithms, optimization)

🛠 Requirements
text
numpy>=1.19.0
matplotlib>=3.3.0
seaborn>=0.11.0
pandas>=1.2.0
scipy>=1.6.0
jupyter>=1.0.0
💡 Learning Path
Week 1-2: Exercises 1-50 (NumPy fundamentals)

Week 3: Exercises 51-100 (Advanced operations)

Week 4: Exercises 101-130 (Data preprocessing)

🤝 Contributing
Contributions welcome! Add exercises, improve explanations, or fix bugs.

📝 License
MIT License

Star ⭐ this repo if you find it useful!
