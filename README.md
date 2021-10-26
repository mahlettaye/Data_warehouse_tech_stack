# Data_warehouse_tech_stack

A stack represents a set of robust components & modular technologies that allow users to develop powerful and enterprise-grade applications. Similarly, a data analytics stack encompasses diverse technologies that let users and businesses build a robust analytics engine to aggregate, integrate, model and trahavae imnsform data from numerous data sources. A data warehouse allows users to consolidate and aggregate data from numerous data sources in a centralised location. In this project we have created an ELT pipline with the help of different data Warehouse and visualizatoion methods. The project includes MYSQL as data warehouse later it is migrated to PostgreSQL, DBT as data transformation tool, SPark for data processing and redash for visualization of dashboard. Airf low as process orchestration tool.

### Architecture 

### Repo Orgainization 
- /airflow contains airflow dag files
- /data    contains sample data set
- /dbt     contains file related to dbt
- /migration contains code for migration of DWH from MYSQL to PostgreSQL
- /redash     contains redash componets
- /schema     contains schema for DWH
- /Spark_data_Processor  contains spark data processing files
- docker compose file for runing all in one 
