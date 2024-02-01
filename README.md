# R-Code-Practice

### Simple R Code that covers basic R programming topics such as: operations, data types, data frames, lists, functions, datasets, vectors, matrices, built-in functions, and visualizations.

*This code is practice from a class assignment.*

The script is organized into sections with explanations and examples for each topic. It includes installation and loading of necessary packages such as 'datasets' and 'tidyverse'. The script then proceeds to demonstrate operations, creating data frames and lists, defining functions, utilizing built-in datasets, working with vectors and matrices, using built-in functions, and generating visualizations like bar charts.

1. Install and load packages:
   - install.packages("datasets"): Installs the "datasets" package if it's not already installed.
   - install.packages("tidyverse"): Installs the "tidyverse" package if it's not already installed.
   - library(datasets): Loads the "datasets" package into the current R session.
   - library(tidyverse): Loads the "tidyverse" package into the current R session. The tidyverse package is a collection of packages designed for data science, including dplyr, ggplot2, tidyr, and others.

2. Operations and Data Types:
   - Defines variables a and b, assigns them values, calculates their sum, and prints the result.

3. Data Frames and Lists:
   - Creates a data frame df containing columns for Name, Age, and Grade.
   - Creates a list my_list containing two elements: Numbers and Colors.

4. Functions:
   - Defines a function square that calculates the square of a number.
   - Calls the square function with an argument and prints the result.

5. Datasets:
   - Uses a built-in dataset women from the datasets package.
   - Prints the first few rows of the women dataset using the head() function.

6. Vectors and Matrices:
   - Creates a vector my_vector and a matrix my_matrix with predefined values.

7. Built-in Functions:
   - Calculates the mean of my_vector using the mean() function and prints the result.

8. Visualizations:
   - Plots a simple bar chart using the barplot() function with my_vector as the data, and customizing labels and colors.
