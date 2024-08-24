Objective: To analyze bike sales data to understand the relationship between customer demographics (income, commute distance, age) and bike purchase behavior.

Data Cleaning steps

1)Remove Duplicates.Check for and eliminate duplicate rows in the raw data to avoid redundancy.

2)Handle Missing Values.Identify any missing values in the dataset. Decide whether to impute these missing values (e.g., with the mean or median) or remove the rows/columns with missing 
values if they are excessive.

3)Correct Data Types.Ensure that data is in the correct format. For instance, verify that numeric fields are treated as numbers, dates are in date format, and categorical data is properly encoded.

4)Fix Inconsistencies.Standardize inconsistent data entries. For example, ensure that values in columns like “Distance” or “Age Brackets” are consistent in format (e.g., "10 miles" vs. "10 miles plus").

5)Address Outliers.Identify and review outliers in the data, such as unusually high or low values in income or commute distances. Decide if they should be adjusted or removed based on their relevance.

6)Remove Irrelevant Data.Eliminate any columns or rows that do not contribute to the analysis or visualization, focusing only on relevant data.

Pivot Table Creation

1)Average Income: Analyzed by gender and bike purchase status to determine income disparities.
2)Commute Distance: Assessed to understand the distribution of bike purchases based on how far customers commute.
3)Age Brackets: Evaluated to explore the correlation between age and bike purchase frequency.


Key Insights:

Income Analysis: Individuals who purchased bikes generally had higher average incomes compared to those who did not. Male buyers tended to have higher incomes than female buyers.
Commute Distance: The data showed variations in bike purchases based on commute distance, with certain ranges being more prevalent.
Age Brackets: People aged 31-54 showed higher bike purchase rates compared to younger or older age groups.
