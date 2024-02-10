
 
  Project Title: Extract, Transform and Loading of UK Grocery Retailer Sales and Pricing

A.  Data Source: Data Lake
	  File Format: csv


B.  Target Details: 
	  Storage Resource: Fabric Data Warehouse
	  File Format: delta	

C.  Business requirments:
    Client needed to extract source data from data lake, clean and transform the data to 
    suit data analysis purpose, and then load it into fabric warehouse for future analysis  
	

D.  Solution Steps: 
   	 -establish a reference link to data lake gen2 from fabric lakehouse using shortcut method
   	 -extract data into pyspark notebook 
   	 -clean and transform data
   	 -write the transformed data into fabric warehouse


E.  Services used: 
   	 -Azure Data Lake Gen2
	 -Fabric Synapse Notebook   
	 -Fabric Lakehouse
   	 -Fabric Warehouse
