# Analyzing IMDB Datasets
This project under coursework Big Data Technologies, conducted a comprehensive analysis of IMDb datasets. UAlizing four TSV-formaFed datasets from Kaggle, the study parsed movie, tv series and shows related informaAon such as raAngs, genres, release dates, and actors details.

The study uAlized the AWS ElasAc Map Reduce (EMR) ecosystem, employing a Spark Cluster on AWS EMR linked to a Jupyter Notebook for execuAng Python queries. Running Spark through AWS EMR service enabled us to provision a Spark cluster of machines and run jobs on Big Data. Data from IMDb was accessed via a public S3 bucket. PySpark facilitated the analysis of extensive datasets that exceed in-memory processing capaciAes. The use of Pandas and Matplotlib libraries enabled data manipulaAon and visualizaAon, respecAvely, with the primary data structure being a PySpark DataFrame.

The steps to complete the project are:
• Creating an IAM user for EMR use
• Creating a cluster on EMR
• Creating a new Studio
• Creating a new workspace
• Running Spark cluster tasks via Jupyter Notebook
  o Installing and importing necessary dependencies (pandas and matplotlib) 
  o Loading data from S3 into a Spark dataframe object
  o Performingthebasictaskofreviewingcolumnsandnumberofrows
  o AnalyzingGenresbydenormalizingtheminthedataset
  o CreaAngverAcalandhorizontalbarchartsusingmatplotlib o AnsweringquesAons

Key analyses included genre, raAngs, prevalent job categories, and trends in character naming across different movie genres. This invesAgaAon provided a deeper understanding of the interacAon between technology and film industry trends.
