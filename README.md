# Exploratory Data Analysis (EDA)
EDA helps identify most relevant features among the existing ones and it helps determine next steps to perform before applying any type of machine learning algorithm.
Next steps could be related to data transformation (aggregation, log transformation, normalisation etc.), or it could be related to increasing the size of input data set via exploring new data sources.
Briefly, EDA helps data scientists decide what they need to get the required answers and make it easy to discover patterns, trends, anomalies etc. 

In our Jupyter notebook we had accomplished the next steps, respectively : 
- Import the required libraries
- Data reading
- Data exploration
    -  More information: `.info()`
    -  Data frame shape: `.shape`
    -  Columns names : useful for filtering data with columns values or selecting a subset of data `.names`
    -  Statistical summary : `.describe()`
    -  Values Count
    -  Data sampling
    -  Data Grouping using `groupby` 
    -  Data filtering : using & (and), |(or) operators
-  Data analysis
     - Univariate Analysis : distplot and histplot
     - Bivariate Analysis
     - Multivariate Analysis
       - Correlation matrix and heatmap
-  Data visualization
