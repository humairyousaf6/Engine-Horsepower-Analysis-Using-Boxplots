# 🚗 Analyzing Engine Horsepower by Number of Cylinders Using Boxplots

A data analysis and visualization project using Python to explore the relationship between the number of engine cylinders and engine horsepower. Using the **Auto MPG dataset** from the UCI Machine Learning Repository, this project applies exploratory data analysis (EDA), data cleaning, and boxplot visualization to understand how horsepower varies across vehicles with different engine configurations.

The analysis uses Seaborn and Matplotlib to visualize horsepower distributions, compare medians and variability, and identify potential outliers across cylinder groups.

---

## ✨ Features

- 📊 Load and explore the Auto MPG dataset
- 🧹 Clean missing and invalid horsepower values
- 🔢 Convert horsepower values into numeric format
- 📅 Process model-year data
- 🚘 Group vehicles by number of cylinders
- 📦 Visualize horsepower distributions using boxplots
- 📈 Compare median horsepower and data variability
- 🔍 Identify potential outliers
- 🐍 Perform data analysis using Python libraries

---

## 🎯 Project Objective

The main objective is to investigate how engine horsepower differs between vehicles with different numbers of cylinders.

The analysis focuses on questions such as:

- Do vehicles with more cylinders generally have higher horsepower?
- How does the median horsepower vary across cylinder groups?
- Which cylinder groups show greater variation in horsepower?
- Are there potential outliers within each group?

---

## 📊 Dataset

This project uses the **Auto MPG dataset** from the UCI Machine Learning Repository.

**Dataset source:** https://archive.ics.uci.edu/ml/machine-learning-databases/auto-mpg/auto-mpg.data

The dataset contains vehicle information, including:

- `mpg` — Miles per gallon
- `cylinders` — Number of engine cylinders
- `displacement` — Engine displacement
- `horsepower` — Engine horsepower
- `weight` — Vehicle weight
- `acceleration` — Acceleration performance
- `year` — Model year
- `origin` — Vehicle origin
- `name` — Vehicle name

---

## 🔬 Methodology

### 1. Data Loading

Load the Auto MPG dataset into a Pandas DataFrame and assign appropriate column names.

### 2. Data Cleaning

- Replace invalid horsepower values represented by `?` with missing values.
- Convert horsepower into a numeric data type.
- Convert model-year values into datetime values and extract the year.

### 3. Exploratory Data Analysis

Examine the dataset and prepare the variables required for comparison.

### 4. Boxplot Visualization

Create boxplots using Seaborn and Pandas to compare horsepower distributions across different cylinder groups.

The visualizations help examine:

- Median horsepower
- Interquartile range (IQR)
- Distribution spread
- Potential outliers

---

## 📦 Visualizations

The notebook creates two boxplot visualizations:

**1. Seaborn Boxplot**

Compares horsepower across cylinder groups using `cylinders` on the x-axis and `horsepower` on the y-axis.

**2. Pandas Grouped Boxplot**

Uses Pandas' built-in boxplot functionality to provide an additional view of horsepower distributions by cylinder count.

---

## 🛠️ Tech Stack

- **Python** — Programming language
- **Pandas** — Data manipulation and cleaning
- **NumPy** — Numerical operations
- **Matplotlib** — Data visualization
- **Seaborn** — Statistical visualization
- **Jupyter Notebook** — Interactive analysis environment

---

## 🚀 Getting Started

### Clone the Repository

```bash
git clone https://github.com/humairyousaf6/Engine-Horsepower-Analysis-Using-Boxplots.git
cd Engine-Horsepower-Analysis-Using-Boxplots
```

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Run the Notebook

Open the notebook in Jupyter:

```bash
jupyter notebook
```

Run the cells sequentially. The notebook retrieves the dataset directly from the UCI repository, so an internet connection is required.

---

## 📁 Project Structure

```text
Engine-Horsepower-Analysis-Using-Boxplots/
│
├── Analyzing_the_Behavior_of_the_Number_of_Cylinders_and_Horsepower_Using_a_Boxplot.ipynb
└── README.md
```

---

## 📌 Key Takeaway

This project demonstrates how boxplots can be used to compare numerical distributions across categories. It provides a practical introduction to data cleaning, exploratory data analysis, and statistical visualization using Python.

The actual findings about which cylinder groups have higher median horsepower or more variability should be reported after examining the generated plots.

---

## 👨‍💻 Author

**Muhammad Humair**

AI/ML & Automation Engineer

- Python
- Data Analysis
- Exploratory Data Analysis
- Data Visualization
- Machine Learning
