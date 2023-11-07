# Olympics-end-to-end-data-engineering-with-Azure




# Architecture

![image](https://github.com/dreytheanalyst/Olympics-end-to-end-data-engineering-with-Azure/assets/21364205/c9d403fd-28a1-4370-9115-436feca32e41)

# Project 

For this project, I created a data Pipeline using Azure Data Factory.


📤Data Extraction:  I've used the used an Api to extract olympics data from github.

📦 Data Ingestion: Loaded the data using data factory to Azur Data Lake gen 2 

Create api registrations: In order to create a connection providing an authentication mount data bricks to ADLS using I AM authentication

🛠️Data Transformation:Transformed data inusing spark in databricks,loaded the transformed into a Azure Datagen 2 in Trasormed directory which is now suitable for analysis.


