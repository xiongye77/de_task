# DE_task
Data engineer related

![image](https://user-images.githubusercontent.com/36766101/170895929-bbc3419f-8fd8-4469-812c-0bf64dce8d17.png)
![image](https://user-images.githubusercontent.com/36766101/170895936-d8ad011e-5e29-4387-a7e8-fcbf5f414162.png)

![image](https://user-images.githubusercontent.com/36766101/170897818-8809247b-9cbf-439b-a149-3c2b81b00f6c.png)


To deal with Big Data, we look into Data Lake, which is an architecture approach where all structured, semi-structured and unstructured data are stored at any scale, typically over cheap & scalable low-cost commodity hardware for storage.

# One of the key differences between Data Lake and Data Warehouse is at which point database schema is needed:

Data Warehouse follows schema-on-write approach, where the data that lands on the Warehouse is well structured and are optimised for queries


Data Lake follows schema-on-read approach, where the data is typically ingested raw (otherwise known as true-to-source). Schema is then worked out at the time of 
when the data needs to be consumed depending on the use case

![image](https://user-images.githubusercontent.com/36766101/170898071-73b19db6-2ef9-4c8a-b7bd-3ac10e961d3a.png)


Another service for data wrangling is called AWS Data Wrangler that extends the power of Pandas library to AWS services connecting data coming from different sources.

As much as 80% of time is spent on task associated with data preparation: extraction & loading, cleaning & normalization, orchestrating data preparation in workflows. AWS Glue DataBrew is a visual data preparation tool that enables users to clean and normalize data without writing any code. It helps to reduce the time needed to prepare data for analytics and Machine Learning (ML). 

The last service showed was SageMaker Data Wrangler, the fastest and easiest way to prepare data for Machine Learning. With SageMaker Data Wrangler, you can simplify the process of data preparation and feature engineering, and complete each step of the data preparation workflow, including data selection, cleansing, exploration, and visualization from a single visual interface.


# What is a Snowflake task?

A Snowflake task in simple terms is a scheduler that can help you to schedule a single SQL or a stored procedure.

A task can be very useful when combined with streams to make an end-to-end data pipeline. 
