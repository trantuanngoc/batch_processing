# US-immigration data engineering : ETL pipeline, data modeling and warehousing of US-immigration data 


## 1. Data
Data is collected from sources:

- [US immigration data](https://www.trade.gov/national-travel-and-tourism-office) this dataset is about immigrations to US reported by National Travel and Tourism Office (NTTO) 
- [US City Demographic Data:](https://public.opendatasoft.com/explore/dataset/us-cities-demographics/export/) this dataset is about  demographics of US cities, came from Opensoft
- [Airport Code Data:](https://datahub.io/core/airport-codes#data) this dataset is about airport information
- [World Temperature Data](https://www.kaggle.com/datasets/berkeleyearth/climate-change-earth-surface-temperature-data) this dataset is about temperature all over the world, it came from Kaggle

## 2. Scope
We design and implement an automated end to end data pipeline on cloud to combine  data from multiple sources. It can help analyse immigration trends at US destination cities and origin of the travelers 
## 3. Tech Stack
 Python, Airflow, Spark, AWS services: S3 (Data Lake), Redshift (data warehouse), EMR (Spark cluster), Terraform, Docker

## 4. Architecture 
<img src = assets/architecture.png alt = "Airflow conceptual view" width="600">

## 5. Data modeling
- Data model (star schema) for data warehouse:
<img src=assets/datawarehouse_design.png alt="Star schema" width="600" height="500">

<!-- <br> <br>
- Airflow workflow:
<img src=assets/airflow_workflow.png alt="Star schema" width="600"> -->
 
<!-- ## 5. Result visualization
- Revenue by month:
<img src=assets/revenue_by_month.png alt="Revenue by month" width="600">

<br> <br>
- Brand popularity:
<img src=assets/brand_popularity.png alt="Brand popularity" width="600"> -->
  
  



  

