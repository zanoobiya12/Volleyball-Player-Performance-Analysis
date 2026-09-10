# Volleyball Player Performance Analysis

## Project Overview

This project analyzes volleyball player performance data using Python and data analysis libraries. The dataset contains information about **131 volleyball players** from different countries, including their age, playing position, and performance metrics.

The analysis focuses on exploring the dataset, checking data quality, understanding player performance statistics, and identifying relationships between different performance metrics.

## Technologies Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook

## Dataset

The dataset contains **131 rows and 10 columns**:

* Player
* Country
* Age
* Attack
* Block
* Serve
* Set
* Dig
* Receive
* Position

## Analysis Performed

### 1. Data Loading

* Loaded the volleyball player dataset using Pandas.
* Examined the structure and sample records of the dataset.

### 2. Data Exploration

* Checked the number of rows and columns.
* Generated statistical summaries using `df.describe()`.
* Examined player performance metrics such as Attack, Block, Serve, Set, Dig, and Receive.

### 3. Data Cleaning

* Checked for missing values.
* Checked for duplicate records.
* The dataset contained **no missing values and no duplicate records**.

### 4. Correlation Analysis

* Calculated correlations between numerical performance metrics.
* Used correlation analysis to understand relationships between different volleyball player performance metrics.

## Key Findings

* **Attack and Serve** showed a strong positive correlation.
* **Dig and Receive** showed a positive correlation.
* **Attack and Block** showed a moderate positive relationship.
* The analysis helped identify patterns between different player performance metrics.

## Project Structure

```text
Volleyball-Player-Performance-Analysis/
│
├── python project.ipynb
├── archive.zip
└── README.md
```
## Purpose of the Project

This project was created to practice **data cleaning, exploratory data analysis, statistical analysis, and data visualization using Python**.

It demonstrates the use of Pandas for data analysis and Matplotlib/Seaborn for understanding and visualizing data.

