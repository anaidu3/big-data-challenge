# Unit 22 Homework: Big Data

## Background
In this assignment, you will put your ETL skills to the test. Many of Amazon's shoppers depend on product reviews to make a purchase. Amazon makes these datasets publicly available. They are quite large and can exceed the capacity of local machines. One dataset alone contains over 1.5 million rows; with over 40 datasets, data analysis can be very demanding on the average local computer. Your first goal for this assignment will be to perform the ETL process completely in the cloud and upload a DataFrame to an RDS instance. The second goal will be to use PySpark or SQL to perform a statistical analysis of selected data.

Create DataFrames to match production-ready tables from two big Amazon customer review datasets.
https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt

* Amazon review sets chosen:
  * Musical Instruments (amazon_reviews_us_Musical_Instruments_v1_00.tsv.gz)
  * Toys (amazon_reviews_us_Toys_v1_00.tsv.gz)

*Used AWS to set up cloud connection for the two datasets.

* Created two Google Colab notebooks and extracted the Musical Instrument and Toys datasets.

* Counted the number of records (rows) in the dataset
  * Musical Instrument Notebook: 904765
  * Toys Notebook: 4864249

* Transformed the dataset to fit the tables in the appropriate schema.

* Loaded appropriate schema into SQL

* Loaded the DataFrames that correspond to tables into an RDS instance.
  
* Created tables in the RDS database.

File Repository: Within the level-1 folder, there are several documents. 

Datasets: 
  * Musical Instruments (amazon_reviews_us_Musical_Instruments_v1_00.tsv.gz)
  * Toys (amazon_reviews_us_Toys_v1_00.tsv.gz)

Jupyter Notebooks Downloaded from Google Colab files:
  * musical_instruments.ipynb
  * toys.ipnyb

SQL Files
Musical Instrument Notebook Files:
  * music_instruments_review_id_table.sql
  * music_instruments_products.sql
  * music_instruments_customers.sql
  * music_instruments_vine_table.sql

Toy Notebook Files:
  * toy_review_id_table.sql
  * toy_products.sql
  * toy_customers.sql
  * toy_vine_table.sql