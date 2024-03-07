# PRODIGY_DS_02
# Titanic Dataset Analysis and Visualization

## Overview
This project focuses on conducting a thorough analysis and visualization of the Titanic dataset to gain insights into various aspects of the passengers onboard. The Titanic dataset, a well-known dataset, provides information about passengers aboard the Titanic, including demographics and survival outcomes.

## Objective
The primary objective is to utilize Python and popular data analysis libraries such as pandas, matplotlib, and seaborn to perform data cleaning, exploratory data analysis (EDA), and visualization. The analysis includes loading, inspecting, cleaning, and visualizing the data to uncover patterns and trends.

## Methodology
### 1. Data Loading and Inspection:
- Load the Titanic dataset using the pandas library.
- Display the first few rows to understand the dataset's structure.
- Generate summary statistics for numerical columns for an overview.
- Examine dataset information, including data types and missing values.
- Identify missing values in each column for potential data cleaning steps.

### 2. Data Cleaning:
- Drop rows with missing values in the "Embarked" column, representing a small portion of the dataset.
- Fill missing values in the "Cabin" column with "Unknown" due to a large number of missing values.
- Fill missing values in the "Age" column with the mean age of passengers to maintain data integrity.

### 3. Data Visualization:
#### Box Plot of Passenger Ages:
- Create a box plot to visualize the distribution of passenger ages.
- Display key statistical measures like median, quartiles, and outliers.

#### Histogram of Passenger Ages:
- Plot a histogram to illustrate the frequency distribution of passenger ages.
- Add Kernel Density Estimation (KDE) for a smoother representation of the distribution.
- Apply customized settings for aesthetics, including color, grid lines, and tick marks.

#### Survival by Gender:
- Generate a count plot to visualize survival outcomes based on gender.
- Gain insights into the proportion of male and female passengers who survived or did not survive.
- Apply customizations for enhanced readability, such as changing the palette and adjusting tick marks.

#### Scatter Plot of Age vs Fare:
- Create a scatter plot to explore the relationship between passenger age and fare paid.
- Distinguish between passengers who survived and those who did not survive using different colors.
- Make customizations for improved visual clarity, including adjusting figure size, adding a legend, and modifying axis labels.

## Conclusion
The project concludes by summarizing the insights gained from the analysis and visualizations. Further analysis or modeling could be explored to deepen the understanding of the dataset.

## Usage
To replicate the analysis:
1. Ensure Python is installed on your system.
2. Clone or download the repository containing the Titanic dataset and Python scripts.
3. Execute the Python scripts using Jupyter Notebook, Google Colab, or any Python IDE.
4. Analyze the generated visualizations and draw conclusions based on the insights.

## Dependencies
- pandas: Data manipulation and analysis library.
- matplotlib: Plotting library for creating visualizations.
- seaborn: Statistical data visualization library.

## Conclusion
This project serves as a comprehensive analysis of the Titanic dataset, showcasing the power of data visualization in uncovering insights from complex datasets. Leveraging Python and data analysis libraries, researchers and enthusiasts can gain valuable insights into historical events like the Titanic disaster and understand the factors influencing survival outcomes.
