# python7.py
# Analyzing Data with Pandas and Visualizing Results with Matplotlib
📊 Analyzing Data with Pandas and Visualizing Results with Matplotlib
📌 Objective

The goal of this assignment is to:

Load and explore a dataset using Pandas.

Perform basic data analysis such as summary statistics and groupings.

Create visualizations with Matplotlib and Seaborn to better understand the data.

📂 Files

analysis.ipynb – Jupyter Notebook containing the full solution.

analysis.py – Python script version of the solution.

README.md – Documentation of the project.

🗂 Dataset

The Iris dataset (a classic dataset in machine learning) is used.
It consists of 150 samples of iris flowers, with the following features:

Sepal length (cm)

Sepal width (cm)

Petal length (cm)

Petal width (cm)

Species (setosa, versicolor, virginica)

The dataset was loaded using sklearn.datasets.load_iris() and converted into a Pandas DataFrame.

⚙️ Steps Performed
Task 1: Load and Explore

Loaded dataset into a Pandas DataFrame.

Displayed first rows with .head().

Checked data types and missing values with .info() and .isnull().sum().

No missing values found; dataset is clean.

Task 2: Basic Analysis

Computed summary statistics with .describe().

Grouped by species to compute mean values.

Identified patterns (e.g., Iris-virginica has the largest petals).

Task 3: Visualizations

Created four different plots:

Line Chart – Sepal vs Petal length over index.

Bar Chart – Average petal length per species.

Histogram – Distribution of sepal length.

Scatter Plot – Sepal length vs Petal length (color-coded by species).

All plots include titles, labels, and legends for clarity.

🔎 Findings

Iris-setosa has the smallest petals but relatively wider sepals.

Iris-virginica shows the largest petal dimensions, making it easily distinguishable.

Sepal lengths cluster around 5–6 cm.

Scatter plot clearly shows separation of species by petal and sepal measurements.

▶️ How to Run

Install required libraries:

pip install pandas matplotlib seaborn scikit-learn


Run the Jupyter Notebook:

jupyter notebook analysis.ipynb


Or execute the Python script:

python analysis.py

✅ Requirements

Python 3.7+

Pandas

Matplotlib

Seaborn

scikit-learn
