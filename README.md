# Data Analysis with Python

### Pandas Module:

Its a high performance, high efficient and high level data analysis library. We can work with dataframes i.e csv files with pandas library. 

You can easily load in, and output out in the xls or xlsx format quickly, so, even if your boss wants to view things the old way, they can. Pandas is also compatible with text files, csv, hdf files, xml, html, and more with its incredibly powerful IO.

Dataframe can take multiple forms, but generally it needs to be a dataset that can form to rows and columns. So maybe a **dictionary** like this:

```python
web_stats = {'Day':[1,2,3,4,5,6],
             'Visitors':[43,34,65,56,29,76],
             'Bounce Rate':[65,67,78,65,45,52]}
```

We can turn this dictionary to a data frame by doing the following:

```python
import pandas as pd

web_stats = {'Day':[1,2,3,4,5,6],
             'Visitors':[43,34,65,56,29,76],
             'Bounce Rate':[65,67,78,65,45,52]}

df = pd.DataFrame(web_stats)
```