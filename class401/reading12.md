# Class 12

[Back to home page](../README.md)

## Pandas

Q. Explain the purpose and basic functionality of the Pandas library. What are some common operations that can be performed on data using Pandas, and how do they contribute to data analysis and manipulation?

- Pandas is a library for python that specialises in data analysis. Easy and flexible to use, it specialises in relational data. An example of what you can do in pandas is making a dataframe of values, tuples, lists etc. This is practically used to take in data and analyse is to make algorithms and machine learning techniques.

Q. What are the primary data structures in Pandas, and how do they differ in terms of use cases?

- Series and dataframe, the primary difference between the 2 is series are used more for simple variables like ints and strings that are associated with an index, while dataframes are used for much more complex data analysation using rows and columns. Pretty much one dimensional data for series, and two dimensional data for dataframes.

Q. Describe the process of loading a dataset into a Pandas DataFrame. What are some common file formats that can be used, and which Pandas functions are utilized to read these formats?

- First off, import pandas like so...

import pandas as pd

- You then want to find the file path of the document the dataset is stored in, this could be a json, csv or even SQL database.

- Use the right function to read the data. Here is an example...

df = pd.read_csv('file_path/dataset.csv')

- you can now manipulate the dataset with other functions.

## Bookmark and review

- [master pandas](https://towardsdatascience.com/be-a-more-efficient-data-scientist-today-master-pandas-with-this-guide-ea362d27386)

## Things I want to know more about

- how often is pandas used in the industry? Are there more librarys like numpy that work well with pandas?
