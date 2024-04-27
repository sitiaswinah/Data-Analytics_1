# Data-Analytics_1
What is Data? Data refers to specific information collected and interpreted for a particular purpose. If data is not presented in a particular format, it is not useful for either computers or humans. Data refers to specific information collected and interpreted for a particular purpose. The basic structures used in data analysis include rows and columns.

**Data Basic**

Type of Data Variable

**1) Category**
A data type that can be stored and identified based on the name or label given to the data.

- Nominal
With this data, it's impossible to establish a specific order or determine superiority, as the data doesn't allow for any calculative comparisons. Example: country column is nominal data because we cannot determine which one can be put in the first/last order and which one is better.
- Ordinal
Ordinal data measures data that is non-numeric and the interval value is unknown. Example: Rating column is ordinal data because this data uses a certain order to rank and is effective for data that requires order when evaluating. for example, PG (Parental Guidance) where movies with this rating can be watched by children with parental supervision. and other ratings

**2) Numeric**
Data used a constant variable, to store a value in the form of a number.

- Discrete
A discrete value is taken from a particular data set, a data set that has a finite number of values. Can take on possible values hat can be listed out.
note:
because in the netflix.csv dataset, i didn't find any example of continues data, so I replaced it with airbnb.csv Example: Bedrooms column is an integer, where integers are included in discrete data and can take on possible values hat can be listed out.

- Continues
A data that can be retrieved but has an unlimited number of values and of course the value is not fixed. Can possible values cannot be counted and only be described using interval on the real number line. Example: guest_satisfaction_overall column is a measurements, possible values cannot be counted and can only be described using intervals

**3) Boolean**
This data type is usually used to represent true and false values in data Example: The boolean data is room_shared column, room_private column, host_is_superhost column

# Type of Data Categories
1) Data Structures
- Structures data
Structured data example are name, dates, stock information, person capacity, bedrooms, etc
- Unstructures data
Unstructured data example are audio, image, video, natural language, document

2) Data Categories
- Quatitantive
Quantitative data are collected using instruments such as rulers, scales, beakers, and thermometers. The example below using df.describe() is a quantitative calculation because there is mean, min, max, etc.
- Qualitative
Qualitative data involve using your senses to observe and interpret the results. An example is room_type, where there are several options.

3) Meta Data
Metadata in data analytics refers to the descriptive or structural information about a dataset. It provides context about the data, helping analysts understand and interpret the data better. Example:

4) Big Data
Big data refers to extremely large datasets that are too complex and massive to be processed using traditional data processing applications. These datasets typically consist of structured, semi-structured, and unstructured data from various sources, including social media, sensors, online transactions, and more.

# Data Cleansing
Data cleansing, also known as data cleaning, is the process of fixing inconsistencies and errors within a dataset to prepare it for analysis. Jupyter Notebook is a popular interactive environment for working with Python that's well-suited for data cleaning tasks due to its ability to combine code, visualizations, and text explanations.

# Imputation and Distribution
Imputation refers to the technique of filling in missing values within a dataset. Missing data can arise from various reasons, like sensor malfunctions, human error during data entry, or surveys with non-responses. Unaddressed missing values can lead to inaccurate analysis and biased results. Distribution, on the other hand, refers to the way data points are spread out for a particular variable. Understanding the distribution helps you identify potential issues and choose appropriate imputation methods.

# Missing Value
Missing values, also known as null values, are a common challenge in data cleansing. They occur when data points are absent from a dataset, leaving blank cells or entries represented by special characters like NaN (Not a Number) in Python.

Imputation by mode
Imputation with mode is usually carried out when finding missing values ​​with categorical values

Perform data manipulation
It is not intended to change the value of data but to make the data easier to read by machines

**Relationships between columns**
Example : relationship between the room_type column and person_capacity

# Data Manipulation
**Aggregate data**
In the world of pandas DataFrames, data aggregation involves summarizing and combining data points to create a more concise and informative representation.

**1. Pivoting**
Pivoting involves restructuring data from a format where each observation has multiple rows (long format) to a format where summary statistics for different categories are displayed in columns (wide format). This transformation makes it possible to condense large data sets and highlight important insights more effectively.

**2. Grouping**
Grouping is a fundamental operation in pandas that allows organizing and analyzing data based on shared characteristics. This involves segmenting the DataFrame rows into different groups based on the values in one or more columns.

**3. Crosstab**
Crosstab is a data aggregation technique that summarizes data from a long format (multiple rows per observation) into a more concise and informative wide format (summary statistics displayed in rows and columns). It is a valuable tool for data exploration and analysis, particularly when dealing with categorical data.

**4. Concatenation**
Concatenation (Concat) combines DataFrames along a specific axis (0 for rows, 1 for columns). It stacks DataFrames on top of each other (axis 0) or side-by-side (axis 1) to create a larger DataFrame.

**5. Merging**
Merging combines data from two separate DataFrames based on a common column or index. It allows to create a new DataFrame that includes columns from both original DataFrames while establishing a specific relationship between the corresponding rows.

# Organize data
Data organization refers to the process of structuring and arranging data within pandas DataFrames to facilitate analysis and interpretation.

**1. Sorting**
In the context of organized data, particularly within pandas DataFrames, Sorting refers to the process of rearranging rows based on the values in one or more columns. The goal is to create a specific order that facilitates data exploration, analysis, and interpretation.

**2. Get dummies**
The get_dummies function from the pandas library performs one-hot encoding on categorical data. It takes a DataFrame with categorical columns and returns a new DataFrame with new binary columns representing each unique category.

**3. Renaming**
Renaming columns or rows in a pandas DataFrame is considered a data organization technique. It falls under the category of data wrangling, which involves cleaning, transforming, and preparing data for analysis. Renaming helps you create more meaningful and descriptive column and row names, making it easier to understand and interpret your data.

