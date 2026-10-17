# Pandas-Practice 

This is a repository where I will post the practice files of the Pandas library while learning it.

A little information about Pandas (from what I have learned till now):

1. It is a python library used for data analysis and data manipulation.
2. It is built on top of NumPy.
3. Two main data structure of Pandas are : Series and DataFrame

*Series*: Series is same as 1D array of NumPy, the only difference is that it is labelled.

*DataFrame*: It is a labelled 2-Dimensional array. It looks just like a table.

*Installing Pandas on the System*
-> !pip install pandas

*Using the pandas library*
-> import pandas as pd

*Example :* 
info = { "Name" : ["Radha", "Rahul", "Amit"],
         "CGPA" : [9.00, 8.96, 8.66]
        }
df = pd.DataFrame(info)
print(df)

*Output*
  Name      CGPA
0 Radha     9.00
1 Rahul     8.96
2 Amit      8.66

[0,1,2] = These are labels of the DataFrame.

By default, these labels are started from 0, we but can change it according to our need.

SQL Tables can also be imported as a DataFrame in Pandas.

*Series :*

With love ~ Anshika Singh ❤️
