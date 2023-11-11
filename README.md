# AWS-S3-to-Azure-DataLake-ETL-Pipeline

This tutorial shows how to use the Data Factory Copy Activity to load data from Amazon Web Services S3 service into Azure Data Lake Storage Gen2.

### To implement this, we need to create the following resources:
- Create AWS s3 bucket.
- Create Azure data lake storage gen2.
- Create Azure data factory.
- Use the copy activity to create a pipeline.
- Monitor the pipeline and activity runs.

### Create a resource group with the necessary resources.
![Create a resource group with the necessary resources](https://github.com/Nkamanyi/AWS-S3-to-Azure-DataLake-ETL-Pipeline/blob/main/Create%20a%20resource%20group%20with%20the%20necessary%20resources.png)

### AWS S3 bucket with the medals.csv data.
![AWS S3 bucket with the medals.csv data](https://github.com/Nkamanyi/AWS-S3-to-Azure-DataLake-ETL-Pipeline/blob/main/AWS%20S3%20bucket%20with%20the%20medals.csv%20data.png)

### Create a data lake gen2 for incoming data.
![Create a data lake gen2 for incoming data](https://github.com/Nkamanyi/AWS-S3-to-Azure-DataLake-ETL-Pipeline/blob/main/Create%20a%20data%20lake%20gen2%20for%20incoming%20data.png)

### Create a user on AWS to get the access key and secret access key.
![Create a user on AWS to get the access key and secret access key](https://github.com/Nkamanyi/AWS-S3-to-Azure-DataLake-ETL-Pipeline/blob/main/Create%20a%20user%20on%20AWS%20to%20get%20the%20access%20key%20and%20secret%20access%20key.png)

### Data pipeline.
![Data pipeline](https://github.com/Nkamanyi/AWS-S3-to-Azure-DataLake-ETL-Pipeline/blob/main/Data%20pipeline.png)

### Monitor the pipeline.
![Monitor the pipeline](https://github.com/Nkamanyi/AWS-S3-to-Azure-DataLake-ETL-Pipeline/blob/main/Monitor%20the%20pipeline.png)

### Pipeline detail activity run.
![Pipeline detail activity run](https://github.com/Nkamanyi/AWS-S3-to-Azure-DataLake-ETL-Pipeline/blob/main/Pipeline%20detail%20activity%20run.png)

### Data stored in adls gen2.
![Data stored in adls gen2](https://github.com/Nkamanyi/AWS-S3-to-Azure-DataLake-ETL-Pipeline/blob/main/Data%20stored%20in%20adls%20gen2.png)
