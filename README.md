# Welcome my DBT materials

![dbt](https://user-images.githubusercontent.com/45530179/219306194-66901a00-b886-4211-8d22-dfa69c9ec1a9.png)

## What is DBT? What is ELT?

DBT (data build tool) is a tool that makes Extract-load-transform (ELT) easier. 

ELT has several advantages over Extract-transform-load (ETL), such as:
* It can transform the data using only SQL (Python, Spark are not needed).
* Staging area is not required, hence reducing the cost of data pipeline maintenance

However, source control and versioning, and data quality testing are issues for ELT. Therefore, DBT is invented to solve the pain point of ELT.


