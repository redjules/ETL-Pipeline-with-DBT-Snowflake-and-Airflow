# ETL Pipeline with DBT Snowflake and Airflow

# Business Overview

DBT (Data Build Tool) is a popular open-source command-line tool used in the data transformation and modeling process. It is widely used in data warehousing and business intelligence projects for building data pipelines, transforming data, and building data models.

DBT is designed to help data analysts and engineers create, maintain, and test modular SQL scripts that can be run sequentially to extract data from various sources, transform it into a structured format, and load it into a target system. It uses the concept of "models" to organize and define SQL queries that transform data from source to target. You can define dependencies between models and run tests to ensure the accuracy of the transformed data.

DBT (Data Build Tool) and Snowflake are two powerful tools that can be used together for data transformation and modeling. Snowflake is a cloud-based data warehousing platform that allows users to store, manage, and analyze large amounts of data. DBT, on the other hand, is an open-source tool that helps users transform and model data using SQL. DBT and Snowflake can be integrated seamlessly, with DBT providing the necessary data transformation and modeling capabilities to enhance Snowflake's functionality. DBT is specifically designed to work with data warehouses like Snowflake, making it easy to create data pipelines and perform transformations on Snowflake data. Additionally, DBT's built-in testing and documentation features can help ensure the accuracy of Snowflake data pipelines and maintain documentation for future reference.

 

# Goals

The main objective of this project series is to offer a complete comprehension of the Data Build Tool (DBT). In the first project of the series, we focused on explaining the fundamental elements of DBT, such as the tool's significance and its role within the Extract, Transform, Load (ETL) process. Additionally, we delved into key aspects like data modeling and logging, which play vital roles in DBT.

Moving on to the second part of the series, our objective is to construct an ETL pipeline utilizing various technologies such as dbt, Snowflake, and Airflow. By integrating these tools, we aim to create a seamless flow for extracting, transforming, and loading data. Furthermore, to ensure efficient monitoring of each pipeline run, we will incorporate Slack and email notifications using SNS (Simple Notification Service).

Overall, this project series is designed to provide a comprehensive understanding of DBT, covering its essential concepts and practical implementation through the development of an ETL pipeline that leverages the capabilities of dbt, Snowflake, Airflow, Slack, and email notifications via SNS.

 

# Tech Stack

Language: Python, SQL

Tool: DBT

Database: Snowflake

Services: AWS EC2, Airflow, AWS SNS

 

# Architecture Diagram

![3](https://github.com/redjules/ETL-Pipeline-with-DBT-Snowflake-and-Airflow/assets/106017493/787dc183-8fb8-4bbc-975c-3db23d34f2fe)


 
