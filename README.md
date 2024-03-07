# IBM Data Science Course SQL Exercise

This repository contains a Python notebook that demonstrates how to analyze three datasets related to Chicago using SQL queries. The datasets used are:

1. Socioeconomic Indicators in Chicago
2. Chicago Public Schools
3. Chicago Crime Data

## Introduction

In this exercise, we load the datasets into SQLite database tables and execute SQL queries to answer various assignment questions.

## Getting Started

To run the notebook, you will need to have Python installed along with the following libraries:

- pandas
- sqlite3

Additionally, the notebook utilizes the SQL magic module for Jupyter Notebook, which can be installed via:

%load_ext sql


## Files

- `SQL_Exercise.ipynb`: Jupyter Notebook containing the Python code and SQL queries for the exercise.
- `README.md`: This file.

## Instructions

1. Clone or download this repository to your local machine.
2. Open the Jupyter Notebook `SQL_Exercise.ipynb`.
3. Follow the instructions in the notebook to execute the SQL queries and solve the assignment problems.

## Problems Solved

The notebook includes SQL queries to solve the following problems:

1. Find the total number of crimes recorded.
2. List community area names and numbers with per capita income less than 11000.
3. List all case numbers for crimes involving minors.
4. List all kidnapping crimes involving a child.
5. List the kind of crimes that were recorded at schools.
6. List the type of schools along with the average safety score for each type.
7. List 5 community areas with the highest % of households below the poverty line.
8. Determine the most crime-prone community area.
9. Find the name of the community area with the highest hardship index using a sub-query.
10. Determine the Community Area Name with the most number of crimes using a sub-query.

## Note

This exercise was completed as part of the IBM Data Science Professional Certificate course. The datasets used are subsets of the original datasets available on the city of Chicago's Data Portal.

For more information on the datasets and the original sources, refer to the links provided in the notebook.

