# Big Data Processing and Analytics using Apache Spark 

Themes and Data Sources: 
  - Scientific publications [data](https://www.aminer.org/citation) from Aminer. 5,354,309 papers and 48,227,950 citation relationships. 2021
  - Airline Delay and Cancellations [data](https://www.kaggle.com/yuanyuwendymu/airline-delay-and-cancellation-data-2009-2018/data). 2009–2018

Authors:
  - J. Rodrigo Flores & Marta Napa

-----

Projects Overview

All projects were developed using Apache Spark as the distributed processing engine and PySpark as the API to Apache Spark.

- Data Warehouse
  - Processing of scientific publications dataset in JSON format in order to populate a Data Warehouse (Kimball schema)
  - Use of Spark Dataframes and Delta Tables  
  - Issuing of SQL-based analytic queries  

- Knowledge Graph
  - Building of a knowledge graph for the scientific publications data set using Spark Graph Frames
  - Running graph-based queries

- Airline Data Analysis
  - Processing of flights dataset using PySpark Dataframes
  - Prediction models using SparkML
    - logistic regression, decision tree classifier, random forest, and gradient boosted trees

- Clustering Pipeline
  - Pre-processing, feature engineering and K-Means clustering
  - Use of UDFs and custom transformers
  - Use of tokenizing, [word2vec](https://spark.apache.org/docs/3.1.1/api/python/reference/api/pyspark.ml.feature.Word2Vec.html) and [TF-IDF](https://spark.apache.org/docs/latest/ml-features.html) for feature engineering
  - Implementation of a search engine based on cosine similarity
