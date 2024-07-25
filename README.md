# Data Science Internship Task 1: Visualizing Distribution of Ages and Genders

## Objective
Implement data visualization techniques to analyze the distribution of ages and genders within a population dataset (`adult.csv`). This task serves as an introduction to exploratory data analysis (EDA) and visualization in data science.


### Problem Statement

1. **Visualizing the Distribution of Genders**:
   - Create a bar chart to display the count of each gender category (`'gender'` column) in the dataset.
   - Customize the plot to differentiate genders using a selected color palette (`['cyan', 'purple']`).

2. **Visualizing the Distribution of Ages**:
   - Generate a histogram to illustrate the frequency distribution of ages (`'age'` column) across the population.
   - Utilize `bins=30` to segment age groups and include a kernel density estimate (`kde=True`) for a smoothed visual representation.

## Steps Implemented

### Data Loading and Exploration

- **Loaded Dataset**: The dataset (`adult.csv`) was loaded using `pandas` (`pd.read_csv('adult.csv')`) to understand its structure and contents.
- **Exploratory Analysis**: Key features such as age and gender were inspected to grasp the demographic composition of the dataset.

### Visualization Techniques

1. **Bar Plot for Gender Distribution**

   Created a bar chart using `seaborn` (`sns.barplot()`) to visualize the count of each gender category. The plot was customized with a chosen color palette (`['cyan', 'purple']`) to distinguish between genders.

2. **Histogram for Age Distribution**

   Generated a histogram using `seaborn` (`sns.histplot()`) to display the frequency distribution of ages. `bins=30` were used to group ages into 30 bins for clarity, and a kernel density estimate (`kde=True`) was included for a smoothed representation of the distribution.

### Code Details
- Implemented using Python with libraries such as `matplotlib` and `seaborn` for data visualization.
- Ensured plots are informative with appropriate titles, axis labels, and plot sizes (`figsize`).
