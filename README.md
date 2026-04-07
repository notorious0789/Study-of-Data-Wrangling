**Experiment-12**

**Name: Apoorba Chatterjee**

**PRN: 25070123020**

**Batch: ENTC A1**

**Title**

**Implementation of Data Wrangling Techniques in Python**

**Aim**

To study and implement data wrangling processes to clean, transform, and prepare datasets for analysis using the Pandas and NumPy libraries.

**Objectives**
- To understand the importance of data wrangling in the data science pipeline.
- To handle missing values and inconsistent data within a dataset.
- To perform data transformation and feature scaling.
- To merge and concatenate multiple datasets for unified analysis.
- To apply grouping and aggregation for summarizing data.

**Theory on Data Wrangling**

Data Wrangling, often called data munging, is the process of transforming and mapping data from one "raw" data form into another format with the intent of making it more appropriate and valuable for a variety of downstream purposes such as analytics.

**Key Components of Data Wrangling**
- Data Cleaning: Identifying and fixing errors, such as handling missing values (NaN) or removing duplicate records.
- Data Transformation: Converting data from one format or structure into another (e.g., converting strings to integers or scaling numerical values).
- Data Integration: Combining data from different sources (CSV files, databases, or dictionaries) into a single cohesive structure.
- Data Aggregation: Summarizing data to find trends, such as calculating the mean, median, or frequency of specific categories.

**Data Wrangling Operations**

Based on the implemented logic in the laboratory sessions, the following wrangling techniques were applied:

1. Handling Missing Data

In real-world datasets, such as the Cars93 or Student Database, missing information is common. Techniques used include:

Identification: Using methods like info() to spot non-null counts.

Action: Dropping rows with missing values or filling them with statistical measures like the mean or median.

2. Data Modification and Cleaning

Renaming and Dropping: Removing unnecessary columns (like 'Gender' or 'Grade' in specific tasks) to focus on relevant features.

Value Updating: Correcting specific entries in the DataFrame using coordinate-based indexing (loc or iloc).

3. Transformation and Grouping

Type Conversion: Ensuring columns have the correct data type (e.g., ensuring 'CGPA' is a float) for accurate mathematical computation.

Grouping: Using groupby() to segment the data by categories (like 'Department') and applying aggregate functions to summarize performance.

**Applications of Data Wrangling**

Preprocessing for Machine Learning: Ensuring data is clean and scaled before training models.

Financial Auditing: Reconciling different transaction records and removing duplicate entries.

Academic Analytics: Preparing student records by aggregating grades across various departments.

Market Research: Merging customer feedback from different regions into a unified dataset.

**Conclusion**

The experiment demonstrates that data wrangling is a critical prerequisite for any meaningful data analysis. By effectively cleaning missing values, transforming data types, and aggregating results, we can convert raw, "messy" data into a structured format that reveals clear insights and trends. Mastery of these Pandas and NumPy techniques ensures data integrity and reliability in real-world applications.
