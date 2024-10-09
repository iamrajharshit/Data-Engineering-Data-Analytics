# Data-Engineering-Data-Analytics
## Project Overview
- Launching a data driven campaign
- Main advertising channel: YouTube
- Initial questions:
  - "how to categories videos, based on their comments and statistics"
  - "what factors affect, how popular a YouTube video will be"
## Why YouTube?
YouTube ranks #1 in the world's top 50 websites.
- Monthly visites is around 34.6 Billion users. 

## Methodology 
- Data Ingestion: (Data from various sources) Ingest data, one-offs and incrementally.
- Design ETL pipeline: Pipeline to Extract, Transform and Load data efficiently.
- Data Lake: To organize the data, will build a new Data Lake architecture, keeping the data architecture efficient and scalable.
- AWS Cloud: Will use AWS cloud as cloud service provider.
- Amazon QuickSight: Will perform reporting, building a Business Intelligence tier, including Dashboard.

## Learnings
- Will learn how to build a data lake from the scratch in Amazon S3.
  - Joining semi-structure and structure data
- WIll design Lake House architecture, keeping cost and performance in mind.
- Will understand the difference between Data Lake and Data Warehouse.
- Will learn how to design different Data Lake layers and perform partition.
  - Like Landing, Cleansed as SSOT, reporing for BI users.
  - WORM (Write Once Read Many) model
- Will use Glue for Data Cateloguing.
- ETL in AWS Glue Spark jobs
- Amazon SNS for alerting
- SQL using AMazon Athena and Spark SQL
  - impact of querying the optimized data layers
- Scripts to ingest data incrementally
- BI Dashboards in Amazon QuickSight
## Basic Concepts

- Big Data: It is a term for massive datasets with varied and complex structures.
  - It contains sturctured data like csv file and also data in form of audio, video and images.
- Data and Time:  Last minute data is actionable data high valued (App based data: realtime) > Reactive data (Used by Data Scientist to get insights) > Histrical Data: (BI tools) (Notebook data) (Least valued)

## Dataset
Trending YouTube Video Statistics dataset from [Kaggle](https://www.kaggle.com/datasets/datasnaek/youtube-new).
- What is trending?
  - YouTube uses factors, including users interactions like views, shares comments and likes.
  - Not the most-viewed videos overall for the calender year
- Source: [Kaggle](https://www.kaggle.com/datasets/datasnaek/youtube-new). Data collected using YouTube API.
  

