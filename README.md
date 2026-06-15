## Intro

Data Analyst focused on Business Intelligence, with a background in Business Administration and a Specialization in Visual Analytics and Big Data. Experienced in Power BI, SQL, Python, and ETL pipelines designed to analyze sales, profitability, and customer behavior. I actively integrate Generative AI to automate reporting and accelerate the delivery of actionable insights. My approach combines technical capability with a sharp commercial vision, transforming complex metrics into high-impact business decisions.

## Technical Skills

•	Programming Languages
    Python, DAX, M/Power Query
•	Databases
    SQL (PostgreSQL, MySQL, SQL Server)
•	Data Visualization
    Power BI, Matplotlib, Seaborn
•	Data Analysis
    Statistical Analysis, A/B Testing, Conversion Funnels, KPIs, Dashboards
•	Data Engineering & Big Data
    ETL/ELT, Apache Kafka, Hadoop, PySpark, Jupyter Notebooks

1️⃣ Project 1

*Title:*  Urban Mobility

*Problem:* Identify which Latin American cities should prioritize investment in transport infrastructure, by crossing traffic congestion data with economic indicators to pinpoint where mobility issues most severely impact productivity.

*What I did:* Cleaned and merged real-world data from TomTom Traffic Index and OECD Cities (2024) using Python and Pandas: standardized column names, fixed data types, aggregated traffic metrics per city, and performed an INNER JOIN between both sources. Built visualizations (boxplot, histogram, bar chart) to analyze the relationship between congestion and GDP per capita.

*Result / Learning:* Found an inverse relationship between congestion and economic development — cities with lower GDP per capita concentrate the worst traffic indexes. Bogotá and Lima emerged as investment priorities due to their combination of high congestion, long travel times, and relatively lower economic capacity.

*Skills:* Python | Pandas | NumPy | Matplotlib | Seaborn.


2️⃣ Project 2

*Title:* Flight Delay Prediction

*Problem:* Process and analyze flight data with missing values and incorrect data types, predict whether a flight will arrive late, and monitor average delay per airport continuously as new data streams in.

*What I did:* Cleaned and transformed a 162,000-flight dataset using PySpark, built a Machine Learning pipeline with a Decision Tree classifier for binary delay classification, and integrated Apache Kafka with Spark Structured Streaming to update aggregations in real time from a JSON message topic.

*Result / Learning:* Implemented an end-to-end workflow spanning from batch data cleaning to streaming event ingestion, reusing the same business logic (retrasoMedio) in both static and real-time modes on distributed infrastructure (HDFS + Kafka + Spark).

*skills:* PySpark, Apache Kafka, Spark MLlib, Spark SQL, HDFS, Python, JupyterLab, Ubuntu Server 22.04.
