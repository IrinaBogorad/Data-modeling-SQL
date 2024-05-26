# Data-modeling-SQL
Python, PostgresSQL / Data modeling -snowflake

We have dataset Sorenson_firm.csv. It`s presents product sales of companies by locations, years and intagrations.  
To build a model we are going to use Kimball data modeling
1. Define the data process
2. Declare the grain
3. Identify the dimension
4. Identify the facts

   Our goal is to built a model to analize sales metrics. Therefore our main table is-
   - workstation_sales
   And from this point we are making others tables
  -years
  -integrations
  -product_offerings
  -companies
  -compustat
  -ceos
  -locations
To make queries work faster we use MD5 hashes, we build primary keys as MD5 indexes
