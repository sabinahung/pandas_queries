# pandas_queries
 
In this assignment, we're asked to complete two notebooks to familiarize ourselves with the basics of pandas.

The [first notebook](/01-Animals.ipynb) requires us to extract data from a csv file with a small dataset that contains names, type, length of six animals. The [second notebook](/02-Billionaires.ipynb) extracts data from an excel spreadsheet that contains 1653 rows × 30 columns all about the billionaires in 2014.

## What I've learned:
1. `df.query()` and `df[colname]` are similar when you're using conditions
2. `normalize=True` helps convert to percentage
3. `df.colname.isin(['A', 'B'])` and `(df.colname == 'A') | (df.colname == 'B')` could also be used to describe conditions
4. `df[['name','age']].age.sort_values()` and `df[['name','age']].sort_values('age')` produce different outputs
