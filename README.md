# StackOverflow 2023 Survey EDA Project
This project is an exploratory data analysis (EDA) of the StackOverflow Developer Survey 2023 data set. The data set contains the responses of over 89,184 developers who participated in the annual survey conducted by StackOverflow, the largest online community for programmers. The data set covers various aspects of the developers’ profile, such as demographics, education, skills, preferences, opinions, and careers.

### Data Cleaning and Transformation
The data set consists of 84 columns and 89,184 rows. The columns represent the questions asked in the survey, and the rows represent the individual responses. The data set contains missing values, outliers, and inconsistent formats. Therefore, some data cleaning and transformation steps are performed to make the data set suitable for analysis. These steps include:

* Dropping columns that are irrelevant to my analysis, redundant, or have too many missing values
* Imputing missing values with appropriate methods, such as mean, median, mode, or constant values
* Removing outliers using the interquartile range (IQR) method
* Converting categorical variables into dummy variables using one-hot encoding
* Renaming columns and values for clarity and consistency
* Organizing the checkbox items into lists.
* converting data types of columns to perform numerical analysis and data plots.
The cleaned and transformed data set has 31 columns and 87,973 rows.

### Data Analysis and Visualization
The data analysis and visualization are performed using Python libraries, such as pandas, numpy, matplotlib, and seaborn. The analysis and visualization aim to answer some interesting questions about the developers, such as:

* What are the developers' most common countries, languages, and platforms among the developers vs what they want to practice in the future?
* How does the experience level affect the employment status?
* What age groups prefer to learn from online courses of any type?
* What are the most popular and most loved technologies among the developers and what are the ones which they want to use in the future?
* what operating systems, languages, tech, databases, frameworks, etc are most popular or mostly used in 2023?
* Comparison of years of coding with years of professional coding with the employment status.
* What are the main challenges and motivations for the developers?
* How many percentages of people are employed with respect to the coding activity they perform in their daily lives?

The analysis and visualization results are presented in a Jupyter notebook named stackOverflowEDA2023.ipynb. The notebook contains the code, output, and explanation for each output. The notebook also contains some interactive plots that allow the user to explore the data in different ways.
