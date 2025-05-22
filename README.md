# School District Performance Analysis
**Creator**: Angelina Murdock  
**Date**: January 2025

## Overview 
This project analyzes district-wide standardized test results and school data to help the school board and city officials make informed decisions about budgets and educational priorities. Using **Pandas** and **Jupyter Notebook**, the analysis aggregates student performance and school characteristics to uncover trends and insights across schools, grade levels, spending categories, and more.

## Table of contents
- [Overview](#overview)
- [Installation](#installation)
- [Analysis](#analysis)
- [Resources](#resources)

## Installation
### Requirements
- Python 3.7 or later
- Jupyter Notebook
- Pandas library installed

### Setup
1. Clone or download the repository from GitHub:
    ``` bash
    git clone https://github.com/Angelinamurdock/pandas-challenge.git
    ```
2. Open the Jupyter Notebook `PyCitySchools_final.ipynb` in your preferred environment. 
3. Run the notebook cells sequentially to reproduce the analysis and visualizations.

## Analysis
This project analyzes data from 15 schools in the district, summarizing key academic performance metrics and revealing actionable insights.

**Key Metrics:**
- Total number of unique schools: 15
- Total students enrolled
- Total district budget
- Average math score: 75% passing rate
- Average reading score: 86% passing rate
- Overall passing rate (math and reading): 65%

**School-Level Summaries:**
- Created DataFrames summarizing each school's type, total students, budget, per-student budget, average math and reading scores, and passing rates.

**Top and Bottom Performing Schools:**
- Schools ranked by overall passing percentage show charter schools consistently outperforming district schools.

**Performance by School Type, Size, and Spending:**
- Charter schools have higher passing rates than district schools, indicating potentially more effective teaching methods or resource use.
- Smaller schools and those with lower per-student spending tend to have higher passing rates, possibly due to more individualized attention and efficient resource management.
- Larger schools and schools with higher spending do not necessarily perform better, suggesting spending alone is not the sole driver of success.

**Grade-Level Analysis:**
- Calculated average math and reading scores by grade (9th-12th) across schools, offering insights into performance trends across grade levels.

**Spending and Size Bins:**
- Grouped schools by spending ranges and size categories to analyze how these factors correlate with student performance. Findings indicate lower spending and smaller size often align with higher passing rates.

Overall, the analysis highlights that charter schools lead in academic achievement and that efficient resource allocation and smaller school sizes correlate with better student outcomes. These insights can guide future budget and policy decisions aimed at improving district-wide educational success.

## Resources
- **DU Bootcamp Module 4:** Used challenge files and class materials from the bootcamp.
- **ChatGPT:** Assisted with code explanations and debugging.