# Q-Skill Internship Projects

This repository contains the Python Development internship projects completed for **QSkill** (Slab 1). All tasks are built and optimized as self-contained Google Colab notebooks using standard data science, mathematical calculation, and machine learning libraries.

---

## 📁 Projects Overview

### 1. Basic Data Analysis & Visualization
* **Core Focus:** Exploratory Data Analysis (EDA) & Data Visualization
* **Libraries Used:** Pandas, NumPy, Matplotlib, Seaborn
* **Key Features:**
    * Automated generation of a 550-record student performance dataset.
    * Descriptive statistical breakdowns and departmental average aggregates.
    * A multi-cell visual dashboard featuring a final score distribution histogram, a categorical departmental performance boxplot, a study hours regression trendline plot, and a correlation spectrum heatmap.

### 2. House Price Predictor
* **Core Focus:** Supervised Machine Learning (Linear Regression)
* **Libraries Used:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
* **Key Features:**
    * Algorithmic generation of a residential housing market dataset tracking size, rooms, location distance, neighborhood ratings, and age attributes.
    * Complete data preprocessing pipeline incorporating an 80/20 train-test split and feature scaling via `StandardScaler`.
    * Model training using `LinearRegression` with standard performance evaluations ($MAE$, $RMSE$, and $R^2$ scores).
    * Visual diagnostics tracking Actual vs. Predicted valuations alongside a feature importance weight chart.
    * An end-to-end single-sample test predictor to calculate immediate pricing forecasts for brand-new custom inputs.

### 3. Matrix Operations Tool
* **Core Focus:** Linear Algebra & Core Scripting Logic
* **Libraries Used:** NumPy
* **Key Features:**
    * Modular algorithmic functions computing matrix addition, subtraction, matrix multiplication, transposition, and determinant values.
    * Built-in dimensional validation blocks to prevent shape-mismatch calculation faults.
    * A completely unified, interactive terminal interface that prompts users to dynamically select an operation, input matrix rows/columns, and render structural mathematical results in real-time.

---

## 🚀 How to Run the Notebooks

1. Select any of the project notebooks inside the repository directory.
2. Open the notebook files directly using **Google Colab**.
3. Run the cells sequentially from top to bottom (`Ctrl + F9`) to generate datasets, calculate metrics, render graphics, and use the interactive prompt loops.
