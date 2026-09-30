## How to Run Your Python Tasks in Jupyter Notebook
Open Jupyter Notebook.
Open your .ipynb file.
Select the Python code cell.
Press Shift + Enter to run the cell.
The output will appear below the cell.

========================================================================================================

## Task 1 

## Project Overview
This project performs a simple data visualization analysis on student data using Python, Pandas, Matplotlib, and Seaborn.

## Technologies Used
Python
Pandas
Matplotlib
Seaborn

## Dataset
The project uses a CSV dataset named:
student_data.csv

## Objective
1. The objective of this task is to practice:
2. Reading CSV data using Pandas
3. Exploratory data visualization
4. Creating relational plots with Seaborn
5. Understanding relationships between numerical variables
6. Using categorical variables such as gender for visual comparison

## Conclusion

The scatter plot provides a visual representation of the relationship between student age and absences, with observations separated by gender. This can be used as a starting point for further exploratory data analysis.

========================================================================================================

## Task 2 – Line Plot & Facet Plot
This task uses Seaborn to visualize the relationship between age and famrel.

## Plots
1. Line Plot: Shows the relationship between age and family relationship quality.

2. Scatter-Style Line Plot: Uses markers and a dashed line.

3. Facet Scatter Plot: Compares famrel and age based on sex.

## Concepts Used
* Seaborn relplot()
* Line Plot
* Scatter Plot
* Markers & Line Styles
* Facet Plot using col
* Categorical Data Visualization

========================================================================================================

## Task 3 – Distribution Plots
This task uses Seaborn to visualize the distribution of student data, mainly focusing on age and Fedu.

## Plots
* Histogram: Shows the distribution of Fedu and age.
* KDE Plot: Displays the probability density distribution of age.
* Rug Plot: Shows individual age observations.
* Histogram + KDE: Combines frequency distribution with a density curve.

## Concepts Used
Seaborn Distribution Plots

Histogram

KDE Plot

Rug Plot

Histogram with KDE

Data Distribution Visualization

========================================================================================================

## Task 4 – Bivariate Distribution Plots
This task uses Seaborn to visualize the relationship between Medu (mother's education) and Fedu (father's education).

## Plots
Bivariate Histogram: Shows the joint distribution of Medu and Fedu.
Bivariate KDE Plot: Shows the density and relationship between the two variables.

## Concepts Used
Bivariate Distribution

Histogram

KDE Plot

Seaborn histplot()

Seaborn kdeplot()

Relationship between two variables

========================================================================================================

## Task 5 – Matrix Plot
This task uses Seaborn to create matrix-based visualizations for exploring relationships between multiple variables.

## Plots
* Pair Plot: Shows relationships between age, Medu, and Fedu.
* Heatmap: Visualizes the relationship between Fjob, freetime, and goout using a pivot table.

## Concepts Used
Pair Plot

Heatmap

Pivot Table

Matrix Visualization

Seaborn pairplot()

Seaborn heatmap()

=======================================================================================================

## Task 6 – Categorical Plots
This task uses Seaborn to visualize categorical data using different plots.

## Plots
* Bar Plot: Shows the average age based on sex.
* Box Plot: Shows the distribution of age across different genders.
* Count Plot: Shows the number of students in each Mjob category.
* Violin Plot: Shows the distribution of freetime.

## Concepts Used
Bar Plot

Box Plot

Count Plot

Violin Plot

Categorical Data Visualization

========================================================================================================

## Task 7 – Regression Plots
This task uses Seaborn to visualize relationships between numerical variables and compare data across categories.

## Plots
* Regression Plot: Shows the relationship between Medu and Fedu with a regression line.
* Scatter Plot with Hue: Shows the relationship between age and goout, differentiated by sex.

## Concepts Used
Regression Plot

Scatter Plot

Regression Line

Categorical hue

Seaborn regplot()

Seaborn scatterplot() 

========================================================================================================

## Task 8 – Multi Plots & Figure-Level Plots
This task explores Seaborn figure-level plots and multiple visualizations to create a simple data analysis dashboard.

## Plots
* FacetGrid: Creates a grid based on sex and age.
* Relplot: Shows the relationship between age and freetime using sex as hue.
* Catplot: Shows the distribution of freetime across different Mjob categories.
* Displot: Shows the distribution of age with a KDE curve.

## Concepts Used 
FacetGrid

Multi-plot Dashboard

Relplot

Catplot

Displot

Figure-level Visualization