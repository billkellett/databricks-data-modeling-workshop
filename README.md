# databricks-delta-workshop

This repository contains assets for a half-day Workshop on Data Modeling with Delta Lake.

The notebooks can be imported from https://github.com/billkellett/databricks-data-modeling-workshop/blob/master/notebooks/Delta_Data_Modeling_Workshop.dbc

The notebook above automatically downloads all data needed for the workshop.  If your Databricks workspace is not able to access the internet, you can use the "firewalled" version of the workshop:

- First, download and unzip https://github.com/billkellett/databricks-data-modeling-workshop/blob/master/data/data-modeling-workshop-all-data.zip
- Next, use the Databricks workspace to upload all of the unzipped files to dbfs:/FileStore/tables/dmwkshp/ --- You do not need to "Create Tables" --- just upload the files
- You can then import and run this version of the notebooks: https://github.com/billkellett/databricks-data-modeling-workshop/blob/master/notebooks/Delta_Data_Modeling_Workshop_Firewalled.dbc
