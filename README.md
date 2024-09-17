# Python Data Cleaning Project (FIFA21 Dataset)

### Introduction

This repository includes the code and documentation for the data cleaning procedures applied to the FIFA21 dataset. The objective of this project is to refine and improve the dataset, which contains details about players from the widely-known FIFA21 video game.

### Dataset Source and Overview

The FIFA 21 dataset utilized in this project was sourced from a data cleaning challenge on Twitter. It encompasses player attributes, statistics, and other pertinent information.

The dataset originally includes over 18,000 records, with each record representing a distinct player. It features various attributes such as player name, age, nationality, club, overall rating, and more.


### Issues found in the data

During the initial exploration and analysis of the FIFA21 dataset, several issues were identified:

- **Missing Values**: Columns such as Hits and Loan Date End contained missing values that needed to be addressed through careful handling and computation.
- **Inconsistent Formatting**: Various columns exhibited inconsistent formatting, necessitating data standardization for uniformity. Specifically, the Heights and Weights columns had values recorded in different units.

### Tools Used

For the data cleaning project, the following tools and libraries were used:

1. **Python** for data cleaning tasks.
2. **Pandas** was instrumental in data manipulation, cleaning and handling missing values.
3. **NumPy** was utilized for mathematical operations and array handling during the cleaning process.
4. **Jupyter Notebooks** provided an interactive environment for code development, exploration and documentation.

### Data Cleaning Process

The data cleaning process comprised the following steps:

1. **Data Understanding**: The dataset was carefully examined to comprehend its structure, columns, and their meanings. Since there was no data dictionary provided, I created one using online resources to clarify what each column represented.

2. **Data Exploration**: Exploratory Data Analysis (EDA) was conducted to gain insights into the dataset, identify patterns, and uncover anomalies.

3. **Handling Missing Values**: During EDA, it became evident why certain values were missing. The Hits column, which tracks the number of times a player was searched in the FIFA database, had blanks for players who were never searched. The Loan Date End column, indicating when loan contracts expired, had missing entries for players who were either free agents or under contract, not on loan.

4. **Standardizing Formatting**: Inconsistent formatting issues, such as varying units in the Heights and Weights columns, were addressed through transformations, lambda functions, and data normalization techniques.

5. **Validation and Quality Checks**: The cleaned dataset was subjected to rigorous validation to ensure its quality, accuracy, and integrity.





### Documentation

For detailed information about the data cleaning process, please refer to the Jupyter notebook (FIFA21_Python_Data_Cleaning_Jupiter NoteBook_Solution) provided in the repository.
