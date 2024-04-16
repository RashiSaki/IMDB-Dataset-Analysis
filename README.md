# Analyzing IMDB Datasets
This project under coursework Big Data Technologies, conducted a comprehensive analysis of IMDb datasets. Utilizing four TSV-formated datasets from Kaggle, the study parsed movie, tv series and shows related information such as ratings, genres, release dates, and actors details.

The study utilized the AWS Elastic Map Reduce (EMR) ecosystem, employing a Spark Cluster on AWS EMR linked to a Jupyter Notebook for executing Python queries. Running Spark through AWS EMR service enabled us to provision a Spark cluster of machines and run jobs on Big Data. Data from IMDb was accessed via a public S3 bucket. PySpark facilitated the analysis of extensive datasets that exceed in-memory processing capacities. The use of Pandas and Matplotlib libraries enabled data manipulation and visualization, respectively, with the primary data structure being a PySpark DataFrame.

The steps to complete the project are:
• Creating an IAM user for EMR use
• Creating a cluster on EMR
• Creating a new Studio
• Creating a new workspace
• Running Spark cluster tasks via Jupyter Notebook
  o Installing and importing necessary dependencies (pandas and matplotlib) 
  o Loading data from S3 into a Spark dataframe object
  o Performing the basic task of reviewing columns and number of rows
  o Analyzing Genres by denormalizing them in the dataset
  o Creating vertical and horizontal bar charts using matplotlib 
  o Answering questions

Key analyses included genre, ratings, prevalent job categories, and trends in character naming across different movie genres. This investigation provided a deeper understanding of the interaction between technology and film industry trends.