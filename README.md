# Data Science Internship Task 1: Visualizing Distribution of Ages and Genders

## Overview

This repository contains an analysis of the `adult.csv` dataset, focusing on visualizing the distribution of ages and genders within the population. The goal of this task is to perform exploratory data analysis (EDA) by creating visual representations that help in understanding the demographic composition of the dataset.

## Dataset

The dataset used for this analysis is `adult.csv`. It contains demographic information about individuals, including their ages and genders.

## Task Description

The primary objectives of this task are:

1. **Visualizing the Distribution of Genders:**
   - Create a bar chart to display the count of each gender category.
   - Customize the plot with a selected color palette (`['cyan', 'purple']`).

2. **Visualizing the Distribution of Ages:**
   - Generate a histogram to illustrate the frequency distribution of ages.
   - Use `bins=30` to segment age groups and include a kernel density estimate (`kde=True`) for a smoothed visual representation.

## Steps Implemented

The analysis is performed using the following steps:

1. **Loading the Dataset:**
   - The dataset is loaded into a Pandas DataFrame using `pd.read_csv('adult.csv')`.

2. **Exploratory Analysis:**
   - Basic statistics and information about the dataset are displayed to understand its structure and the key features (age and gender).

3. **Data Visualization:**

   - **Bar Plot for Gender Distribution:**
     - Created a bar chart using Seaborn (`sns.barplot()`) to visualize the count of each gender category.
     - Customized the plot with a color palette (`['cyan', 'purple']`).

   - **Histogram for Age Distribution:**
     - Generated a histogram using Seaborn (`sns.histplot()`) to display the frequency distribution of ages.
     - Utilized `bins=30` to group ages into 30 bins for clarity and included a kernel density estimate (`kde=True`) for a smoothed representation of the distribution.

## Results

- **Gender Distribution:**
  - The bar chart visually differentiates between genders using the selected color palette, showing the count of each gender category.

- **Age Distribution:**
  - The histogram provides a visual representation of age distribution across the population, with the kernel density estimate showing the smoothed distribution.

## Libraries Used

- Pandas
- Matplotlib
- Seaborn
