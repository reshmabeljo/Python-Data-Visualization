# Python Data Analytics– Data Visualization

## 📌 Project Overview

This project focuses on data cleaning, handling missing values, and data visualization using Python libraries. The Seaborn Taxis dataset is used to analyze New York City taxi trip information and create different types of visualizations.

The project demonstrates how Python can be used to explore datasets, identify patterns, understand relationships between variables, and present data through graphical representations.

## 🎯 Objectives

- Load and explore the Taxis dataset.
- Identify and handle missing values.
- Perform data cleaning and preprocessing.
- Create different visualizations using Matplotlib and Pandas.
- Create statistical visualizations using Seaborn.
- Understand relationships and patterns in taxi trip data.

## 🛠️ Technologies and Libraries Used

- **Python** – Programming language.
- **Pandas** – Data manipulation and analysis.
- **NumPy** – Numerical operations.
- **Matplotlib** – Data visualization.
- **Seaborn** – Statistical data visualization.
- **Jupyter Notebook** – Interactive development environment.

## 📂 Dataset

**Dataset Name:** Taxis Dataset

**Source:** Seaborn built-in dataset.

The dataset contains information about taxi trips in New York City, including:

- Pickup and drop-off timestamps
- Passenger count
- Trip distance
- Pickup and drop-off locations
- Fare amount
- Tip amount
- Tolls
- Total amount
- Payment method

### Loading the Dataset

```python
import seaborn as sns

df = sns.load_dataset("taxis")
```

## 📊 Project Tasks

### 1. Loading the Dataset
- Import the required Python libraries.
- Load the Taxis dataset using Seaborn.

### 2. Handling Missing Values
- Check for missing values in the dataset.
- Identify columns containing missing data.
- Impute numerical missing values using mean or median.
- Impute categorical missing values using mode.
- Remove rows with missing values in critical columns where imputation is not appropriate.

### 3. Data Visualization Using Matplotlib / Pandas

The following visualizations are created:

| Visualization | Description |
|---|---|
| Line Chart | Visualizes fare amounts over time using pickup timestamps. |
| Bar Chart | Shows total fare for each pickup borough. |
| Pie Chart | Displays trip distribution based on payment methods. |
| Histogram | Visualizes the distribution of taxi trip distances. |
| Box Plot | Shows the distribution of tip amounts for each pickup borough. |

### 4. Data Visualization Using Seaborn

The following statistical visualizations are created:

| Visualization | Description |
|---|---|
| Count Plot | Displays the number of trips in each pickup borough. |
| Scatter Plot | Shows the relationship between trip distance and fare, with colors representing pickup boroughs. |
| Heatmap | Visualizes correlations between numerical variables such as distance, fare, tip, tolls, and total. |
| Pair Plot | Shows pairwise relationships between distance, fare, tip, and total, categorized by pickup zone. |
| Violin Plot | Displays the distribution of fare amounts for different payment methods. |

## 📈 Key Learning Outcomes

Through this project, I learned:

- How to load datasets using Seaborn.
- How to inspect and clean data using Pandas.
- How to identify and handle missing values.
- How to create different types of charts using Matplotlib.
- How to create statistical visualizations using Seaborn.
- How to interpret correlation between numerical variables.
- How to identify patterns, trends, and relationships in datasets.

## 🏁 Conclusion

This project provides practical experience in data analysis and visualization using Python. By working with the Seaborn Taxis dataset, different data cleaning techniques and visualization methods are applied to understand taxi trip patterns, fare distributions, payment preferences, and relationships between numerical variables.

The project helped develop practical skills in Python programming, data preprocessing, exploratory data analysis, and data visualization.

---

**Project:** Python Data Analytics Assignment 2 – Data Visualization

**Tools:** Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook
