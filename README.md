# N5 Now Challege
***

For do this challenge, I created a Docker container using **jupyter/all-spark-notebook** image.

Files in repository:

- [**pyspark.ipynb**](/pyspark.ipynb): Jupyter notebook to charge Kaggle covid data to parquet using Spark
- [**python.ipynb**](/python.ipynb): Jupyter notebook to charge Kaggle covid data to parquet using Pandas
- [**corona-virus-parquet-pandas**](/corona-virus-parquet-pandas): Folder where pandas notebook save parquet outputs
- [**corona-virus-parquet-pyspark**](/corona-virus-parquet-pyspark): Folder where spark notebook save parquet outputs
- [**corona-virus-report**](/corona-virus-report): Folder where download Kaggle covid data
- [**DER_Diagram**](/DER_Diagram): Folder that has all files about DER Diagram like .drawio

## DER Diagram

This tables cant be realationated, but I create two dimensions **Date** and **Place**, for related this tables, and use **full_grouped** table as Fact Table and is possible add new columns based in the others tables.

Tables:

- *country_wise_latest*
- *covid_19_clean_complete*
- *day_wise*
- *full_grouped*
- *usa_county_wise*
- *worldometer_data*
- *Date*
- *Place*

![DER Diagram](/DER_Diagram/DER.jpg)