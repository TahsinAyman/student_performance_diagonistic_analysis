# 🌄 Student Performance Correlation Analysis

- [Overview](#-overview)
- [Tools Used](#-tools-used)
- [Files](#️-files)
- [Correlation Analysis](#-correlation-analysis)
- [How to Run](#how-to-run-)

## 🚀 Overview

This project involves analyzing the correlation between student grades and the hours they studied. The analysis is performed using Python, with a focus on data manipulation and visualization using libraries such as Pandas and Jupyter Notebook. The primary goal is to identify patterns and correlations within the data that can inform educational strategies and interventions. The project includes steps for data cleaning, exploratory data analysis, and correlation analysis to understand the relationships between study hours and academic performance.

## 💼 Tools Used

![badge](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![badge](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![badge](https://img.shields.io/badge/windows-%230078D6.svg?style=for-the-badge&logo=windows&logoColor=white)
![badge](https://img.shields.io/badge/vscode-%23007ACC.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![badge](https://img.shields.io/badge/python-%233776AB.svg?style=for-the-badge&logo=python&logoColor=white)
![badge](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![badge](https://img.shields.io/badge/jupyter-%23F37626.svg?style=for-the-badge&logo=jupyter&logoColor=white)

### 🛰️ Files

- [`data.csv`](./data/data.csv) - used as primary source of data
- [`main.ipynb`](./src/main.ipynb) - used for analysis

### 🔥 Correlation Analysis

Correlation analysis is a statistical technique used to measure and describe the strength and direction of a linear relationship between two quantitative variables. In other words, it helps answer the question, "How closely are two variables related?"

Key points about correlation analysis:

- **Pearson’s Correlation Coefficient (r):**
    
    The most common measure, Pearson’s r, ranges from –1 to +1.
    
    - **+1:** Perfect positive linear relationship (as one variable increases, so does the other).
    - **–1:** Perfect negative linear relationship (as one variable increases, the other decreases).
    - **0:** No linear relationship exists.
- **Interpretation:**
    - **Calculation:**
        
        It is computed using the formula:
        
        $$
        r = \frac{\sum (x_i - \overline{x})(y_i - \overline{y})}{\sqrt{\sum (x_i-\overline{x})^2 \cdot \sum (y_i-\overline{y})^2}}
        $$
        
        Here, $x_i$ and $y_i$  are the individual data points, while $\overline{x}$ and  $\overline{y}$ represent the means of the x and y datasets respectively.
        
    
    The sign of r indicates the direction of the relationship (positive or negative), and the magnitude (absolute value) indicates the strength of the linear association.

### How to Run 👈
- Clone the repository using 
    ```bash
    git clone https://github.com/TahsinAyman/student_performance_diagonistic_analysis.git
    ```
- Under a stable `Jupyter` environment open [`main.ipynb`](./src/main.ipynb) file
