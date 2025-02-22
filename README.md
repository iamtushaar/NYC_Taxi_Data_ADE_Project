# NYC_Taxi_Data_ADE_Project

Developed a fully automated data pipeline for processing NTYC Taxi data leveraging Azure cloud technologies. Key project steps include:

Data Ingestion:
Utilized Azure Data Factory (ADF) to copy Green Taxi Trip Records files for 2023 from the NYC Taxi website to the ADLS raw zone. The process leveraged a single copy activity with parameterized datasets to ensure efficient and dynamic data ingestion.

Data Transformation:
Employed Azure Databricks notebooks to apply data cleansing and transformation techniques. Transformed data was then loaded into the ADLS curated zone for further processing.

Delta Table Creation:
Built Delta tables on top of the curated data layer, optimizing the dataset for high-performance querying and reliable data management.

BI Integration:
Established connectivity between Databricks and Power BI, enabling real-time data visualization and reporting by pulling data directly from the Delta tables.

Key Skills & Technologies:
Azure Data Factory, Azure Data Lake Storage, Azure Databricks, Delta Lake, Power BI, ETL Processes, Parameterized Datasets, Cloud Data Engineering.
