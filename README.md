# Data-Analysis
E-Commerce Product Review Analysis using PySpark and Power BI

#Project Overview
This project focuses on analyzing large-scale e-commerce product review datasets using Apache Spark (PySpark) and Power BI. The system performs data preprocessing, exploratory data analysis (EDA), sentiment analysis, and dashboard visualization to generate meaningful business insights from customer reviews.

The project helps organizations understand customer behavior, product performance, customer satisfaction, and review trends using scalable big data technologies.

#Objectives
To analyze large-scale e-commerce product review datasets.
To perform data preprocessing and cleaning using PySpark.
To identify customer sentiment from review ratings.
To generate meaningful business insights from customer reviews.
To create interactive dashboards using Power BI.

#Technologies Used
Python
Apache Spark
PySpark
Google Colab
Power BI
Pandas
NumPy
Matplotlib

#Dataset contains:

ProductId
UserId
ProfileName
HelpfulnessNumerator
HelpfulnessDenominator
Score
Time
Summary
Text

#Project Workflow
Dataset Collection
        ↓
Data Loading using PySpark
        ↓
Data Cleaning and Preprocessing
        ↓
Exploratory Data Analysis (EDA)
        ↓
Sentiment Analysis
        ↓
Result Generation
        ↓
Export Processed Data
        ↓
Power BI Dashboard Visualization
        ↓
Business Insights and Reporting

#Modules of the Project

1. Data Collection Module
Collection of e-commerce review dataset.
Importing CSV dataset into PySpark environment.
2. Data Preprocessing Module
Removing null values
Removing duplicate records
Data type conversion
Cleaning review text
3. Exploratory Data Analysis (EDA)
Rating distribution analysis
Product review analysis
Review count analysis
Statistical analysis
4. Sentiment Analysis Module
Customer reviews are classified into:
Positive
Neutral
Negative

#Classification Logic:
Score > 3 → Positive
Score = 3 → Neutral
Score < 3 → Negative

5. Visualization Module
Interactive Power BI dashboard containing:
Sentiment charts
Product analysis
Rating distribution
KPI cards
Review trend analysis

#References
Apache Spark

Apache Spark Documentation

PySpark Documentation

PySpark API Documentation

Power BI Documentation

Power BI Documentation

Google Colab

Google Colab
