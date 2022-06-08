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

# How to load data into Snowflake

Bulk loading
![image](https://user-images.githubusercontent.com/36766101/171066726-2b77f884-7e80-4243-a195-d39202ec6393.png)

Bulk loading is used when you need to import large amounts of data relatively quickly. This method enables to load bunch of files from a local server or an external cloud storage (data lake) into Snowflake.

![image](https://user-images.githubusercontent.com/36766101/172510178-7d135098-4cfd-4c25-a7bb-ca49ba093e85.png)

Continuous loading
![image](https://user-images.githubusercontent.com/36766101/171066705-62e7650f-090f-4f34-8511-d6626686c097.png)

Continuous loading allows you to do real-time data loading. It is done using Snowflake serveless service called “Snowpipe”, which enables loading data from files as soon as they’re available in a stage.




![image](https://user-images.githubusercontent.com/36766101/171324603-625258ff-5e5d-4b52-a4fc-ece4a59263aa.png)
![image](https://user-images.githubusercontent.com/36766101/171324967-80a4a954-b314-4e98-b84a-feb946abec3c.png)
![image](https://user-images.githubusercontent.com/36766101/171337565-e2f7b4e1-5a55-44ed-9534-a28ba1fd0120.png)





For many data scientists, a typical workflow consists of using Pandas to do exploratory data analysis before moving to scikit-learn for machine learning.Numpy arrays provide fast and versatile ways to normalize data that can be used to clean and scale the data during the training of the machine learning models.Scikit-Learn’s machine learning models require the input to be a two-dimensional data structure of numeric values. No string values are allowed. 

Encoding a single string column
To start off, let’s encode a single string column, HouseStyle, which has values for the exterior of the house. Let’s output the unique counts of each string value.


Principle Component Analysis.Principal component analysis (PCA)  is a dimensionality-reduction method that is often used to reduce the dimensionality of large data sets, by transforming a large set of variables into a smaller one that still contains most of the information in the large set.



