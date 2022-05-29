# de_task
Data engineer related

![image](https://user-images.githubusercontent.com/36766101/170895929-bbc3419f-8fd8-4469-812c-0bf64dce8d17.png)
![image](https://user-images.githubusercontent.com/36766101/170895936-d8ad011e-5e29-4387-a7e8-fcbf5f414162.png)

To deal with Big Data, we look into Data Lake, which is an architecture approach where all structured, semi-structured and unstructured data are stored at any scale, typically over cheap & scalable low-cost commodity hardware for storage.

# One of the key differences between Data Lake and Data Warehouse is at which point database schema is needed:

Data Warehouse follows schema-on-write approach, where the data that lands on the Warehouse is well structured and are optimised for queries


Data Lake follows schema-on-read approach, where the data is typically ingested raw (otherwise known as true-to-source). Schema is then worked out at the time of 
when the data needs to be consumed depending on the use case
