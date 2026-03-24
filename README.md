**NAME: ANSH PRATAP SINGH**

**PRN: 25070123143**

**AIM: To analyze categorical data from a dataset using Python and the Pandas library, and to determine the count and percentage distribution of different categories**

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**THEORY**

Data analysis is the process of examining and interpreting data to obtain useful information. In this experiment, categorical data from a dataset is analyzed using Python and the Pandas library, which is widely used for data manipulation and analysis.

The dataset contains information such as grades and gender of students. Pandas stores data in a DataFrame, a two-dimensional table consisting of rows and columns. Various functions are used to explore and summarize the dataset.

The value_counts() function is used to count the frequency of each category in a column. It helps determine how many times each value appears in the dataset. Percentage distribution can also be calculated to understand the proportion of each category relative to the total data.

Using these methods, categorical data can be easily summarized and interpreted, helping in better understanding of the dataset.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**FUNCTIONS USED**

1. df.head()

This function is used to display the first five rows of the dataset. It helps in quickly viewing the structure and contents of the data.

2. df.tail()

This function displays the last five rows of the dataset. It is useful to check the data at the end of the dataset.

3. print(df.columns)

This function prints the names of all the columns present in the dataset. It helps in identifying the variables available for analysis.

4. df.sample(5)

This function returns 5 random rows from the dataset. It is useful for viewing random data points and checking the dataset more broadly.

5. df.isnull().sum()

This function checks for missing (null) values in each column and returns the total number of missing values present in the dataset.

6. df.duplicated().sum()

This function counts the number of duplicate rows in the dataset. It helps in identifying repeated data entries.

7. df.nunique()

This function returns the number of unique values in each column. It helps in understanding how many distinct categories exist in the dataset.

8. value_counts(normalize=True)

This function returns the relative frequency (percentage/proportion) of each unique value in a column instead of the raw count. It helps in understanding the distribution of categories in percentage form.

9. pd.crosstab()

This function is used to create a cross-tabulation table that shows the relationship between two categorical variables. It helps in analyzing how one category is distributed across another category.

10. df.groupby()

This function is used to group data based on one or more columns and perform operations such as counting, summing, or averaging on each group. It is useful for analyzing patterns or comparisons between different categories.

11. value_counts()

This function counts the frequency of each unique value in a column. It is commonly used to analyze categorical data such as grades or gender.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**CONCLUSION**

In this experiment, categorical data from the dataset was analyzed using Python and the Pandas library. Various functions such as value_counts(), value_counts(normalize=True), pd.crosstab(), and groupby() were used to study the frequency and distribution of different categories. This analysis helped in understanding the dataset more clearly and demonstrated how Python can be effectively used for basic data analysis and interpretation.
