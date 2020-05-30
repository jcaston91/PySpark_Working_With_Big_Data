# PySpark_Working_With_Big_Data

Jontavius Caston
March 10, 2020

For this part of the exercise we will load a comma-separated value (CSV) file into Spark as a text file (e.g., df_text = spark.read.text["baby-names.csv"]). We will use the file baby-names.csv found in the baby-names directory of the data for this course.

Spark's Online Documentation will be helpful for the programming exercises in this exercise. In particular, the Apache Spark Quick Start Guide and Spark SQL, DataFrames and Datasets Guide will be helpful in completing this exercise.

a. Load Data and Show Schema
Load the baby-names.csv file into Spark dataframe as a text file. Print the dataframe’s schema using the printSchema method.

b. Filtering and Counting
First, count the number of rows in the dataframe. Second, filter the dataframe so that it only contains rows that contain John. Count the number of rows in the filtered dataframe.

Working with DataFrames
In the previous part of the exercise we loaded the data into the dataframe as a text file. As a consequence, Spark treated each line as a record with a single field. While this is useful for some applications (processing raw text), it is not useful when our original data contains structure. In this part of the exercise, load baby-names.csv as a CSV file instead of a text file.

a. Load Data and Show Schema
Load the baby-names.csv file as a CSV file instead of a text file. Print the schema for this dataframe. In addition to printing the dataframe’s schema, show the first 20 rows of data using the show method.

b. Filtering and Counting
Filter the dataframe so that it only contains rows that contain the name John. Count the number of rows in the filtered dataframe.

c. Sorting and Limits
For this step, filter the dataframe to include only males (sex=‘M’) born in Nebraska (state=‘NE’) in 1980 (year=‘1980’). Sort the dataframe by descending values of count and show the first ten rows. The result should be the top ten most popular boy’s names for 1980 in Nebraska.
