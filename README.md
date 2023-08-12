
# Euro2012 Statistics Analysis

This project involves the analysis of Euro2012 statistics using Python and the Pandas library. The dataset is obtained from [this source](https://raw.githubusercontent.com/guipsamora/pandas_exercises/master/02_Filtering_%26_Sorting/Euro12/Euro_2012_stats_TEAM.csv), and it contains information about various statistics related to Euro2012 soccer teams.

## Project Overview

This repository contains Python code for analyzing Euro2012 statistics using the Pandas library. The analysis includes steps to load the dataset, filter and sort data, and answer questions related to team performance and attributes. The primary goals of this project are:

- Load the Euro2012 statistics dataset using Pandas.
- Filter and sort data to answer specific questions about the dataset.
- Calculate mean values and extract specific columns from selected teams.

## Steps in the Analysis

1. Import necessary libraries, including Pandas and NumPy.
2. Import the Euro2012 statistics dataset from the provided source.
3. Assign the dataset to a variable called `euro12`.
4. Select only the 'Goal' column.
5. Determine the number of teams participating in Euro2012.
6. Determine the number of columns in the dataset.
7. Create a DataFrame named `discipline` with selected columns.
8. Sort the teams in `discipline` by 'Red Cards' and 'Yellow Cards'.
9. Calculate the mean 'Yellow Cards' given per team.
10. Filter teams that scored more than 6 goals.
11. Select teams that start with the letter 'G'.
12. Select the first 7 columns of the dataset.
13. Select all columns except the last 3 columns.
14. Present the 'Shooting Accuracy' from selected teams.

## Repository Structure

```
Euro2012-Statistics-Analysis/
│
├── euro2012_stats.ipynb           # Jupyter Notebook with analysis code
├── Euro_2012_stats_TEAM.csv       # Dataset file
└── readme.md                      # Project summary
```

## Usage

1. Clone the repository using: `git clone https://github.com/your-username/Euro2012-Statistics-Analysis.git`
2. Navigate to the repository: `cd Euro2012-Statistics-Analysis`
3. Open the `euro2012_stats.ipynb` notebook to see the detailed analysis steps and results.

## Acknowledgments

- The dataset is sourced from [guipsamora](https://github.com/guipsamora) on GitHub.
- Special thanks to the contributors of the Pandas and NumPy libraries for providing the tools for data analysis.

