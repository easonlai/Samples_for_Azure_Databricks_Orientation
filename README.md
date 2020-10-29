# Samples for Azure Databricks Orientation

This is samples code repository (Python) for [Azure Databricks](https://docs.microsoft.com/en-us/azure/databricks/scenarios/what-is-azure-databricks) Orientation. It's covered various useful usage scenario from beginner to intermediate level.

**Section 1**
* Mounting ADLS ([Azure Data Lake Store Gen 2](https://docs.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-introduction))
* Exploring sample data (csv) in ADLS with [Pandas](https://pandas.pydata.org/)
* Plotting column value count by [Matplotlib](https://matplotlib.org/) & [Seaborn](https://seaborn.pydata.org/)
* Plotting data distribution by [Matplotlib](https://matplotlib.org/) & [Seaborn](https://seaborn.pydata.org/)
* Plotting columns relationship by [Seaborn](https://seaborn.pydata.org/)
* Plotting [Pair Plots](https://seaborn.pydata.org/generated/seaborn.pairplot.html) to understand the best set of features to explain a relationship between two variables or to form the most separated clusters by [Seaborn](https://seaborn.pydata.org/)
* Plotting columns/features correlation in-between by [Matplotlib](https://matplotlib.org/) & [Seaborn](https://seaborn.pydata.org/)

**Section 2**
* Mount [Azure Blob Storage](https://docs.microsoft.com/en-us/azure/storage/blobs/storage-blobs-introduction)
* Exploring sample data (json) in Azure Blob Storage with [Json](https://docs.python.org/3/library/json.html) and [Pandas](https://pandas.pydata.org/)
* Flatten first level of nested columns data
* Flatten second level of nested columns data
* Plotting columns relationship by [Seaborn](https://seaborn.pydata.org/)

**Section 3**
* Connect to [Azure SQL Database](https://docs.microsoft.com/en-us/azure/azure-sql/database/sql-database-paas-overview) to read data source via [Spark JDBC driver](https://docs.microsoft.com/en-us/azure/databricks/data/data-sources/sql-databases#python-example)
* Making SQL query to [Azure SQL Database](https://docs.microsoft.com/en-us/azure/azure-sql/database/sql-database-paas-overview) via [Spark JDBC driver](https://docs.microsoft.com/en-us/azure/databricks/data/data-sources/sql-databases#python-example)
* Installing [msodbcsql17 with pyodbc](https://docs.microsoft.com/en-us/sql/connect/python/pyodbc/python-sql-driver-pyodbc?view=sql-server-ver15)
* Connect to [Azure SQL Database](https://docs.microsoft.com/en-us/azure/azure-sql/database/sql-database-paas-overview) to read data source via [Pandas pyodbc driver](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.read_sql.html)
* Making subset of data from ADLS dataframe
* Making subset of data from SQL (pyodbc) dataframe
* Append two subset of dataframe into one
* Plotting column value count by [Matplotlib](https://matplotlib.org/) & [Seaborn](https://seaborn.pydata.org/)

**List of Files**
* data/ > sample source data directory
* data/pima-indians-diabetes-data.csv > Pima Indians Diabetes Database in csv
* data/pima-indians-diabetes-data-2.csv > Pima Indians Diabetes Database in csv with column header
* data/raw_nyc_phil.json > New York Philharmonic Performance History in json
* Samples_for_Orientation_MASKED.ipynb > Exported Notebook from Azure Databricks
* Samples_for_Orientation_MASKED.html > Exported HTML (with result and visual) from Azure Databricks

![capture1](https://github.com/easonlai/Samples_for_Azure_Databricks_Orientation/blob/main/git-images/capture1.PNG)






