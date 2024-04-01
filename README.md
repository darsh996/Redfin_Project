# Redfin_Project
In this project, I built a data pipeline using various AWS services and other tools to extract, transform, and load (ETL) data from Redfin.
Redfin is a leading real estate brokerage company that provides a wide range of services to homebuyers and sellers. 
I would like to thank them for providing the data used in this project.https://www.redfin.com/news/data-center/

The data pipeline consists of the following components:

Data Extraction: I extracted data from Redfin and prepared it for further processing. The raw data was stored in an S3 bucket on AWS.

Data Transformation: I transformed the raw data into a more structured format using Apache Airflow.
I created an EC2 instance on AWS, installed necessary dependencies, and then installed Airflow.
I used Airflow to orchestrate the data transformation process.

Data Loading: I loaded the transformed data into Snowflake, a cloud-based data warehousing platform.
I created a Snowpipe to automatically load the data into Snowflake whenever new data is available in the S3 bucket.

Data Visualization: I connected Snowflake to Power BI, a business analytics tool, to visualize the data.

Overall, this project demonstrates how to build a robust and scalable data pipeline using AWS services and other tools. The data pipeline can be easily modified to handle different data sources and destinations.




![Screenshot 2024-04-01 at 4 44 00 PM](https://github.com/darsh996/Redfin_Project-AWS-Airflow-Snowflake-PowerBI/assets/97582053/d4589397-b7ea-4219-a8dc-43721fd391fa)

![homesoldbyyear](https://github.com/darsh996/Redfin_Project-AWS-Airflow-Snowflake-PowerBI/assets/97582053/14dacffa-b48f-4993-8a9e-ad5fe69c5c4a)


![homesoldperyearbypropertytyp![monthlysalebypropertytype](https://github.com/darsh996/Redfin_Project-AWS-Airflow-Snowflake-PowerBI/assets/97582053/1b84a317-6fea-432e-869a-009e6a4e2c3d)


![monthlysalebypropertytype](https://github.com/darsh996/Redfin_Project-AWS-Airflow-Snowflake-PowerBI/assets/97582053/3c5e5728-6e86-415e-b8ab-737bc3fabc96)


![salepriceforallcities](https://github.com/darsh996/Redfin_Project-AWS-Airflow-Snowflake-PowerBI/assets/97582053/f27ba039-4ae0-47f1-9efe-315c482af8fc)


![suminv1](https://github.com/darsh996/Redfin_Project-AWS-Airflow-Snowflake-PowerBI/assets/97582053/9cbf77e3-71e4-4939-9252-a96e30588711)


![suminv2](https://github.com/darsh996/Redfin_Project-AWS-Airflow-Snowflake-PowerBI/assets/97582053/b4c6ee4a-ecad-489d-92d8-fed1f5fd8695)
