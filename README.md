# analytics-cloud-combine-data
Examples on how to combine data in the Salesforce Analytics Cloud

Sales Data Generator.xlsx - generates random sales data from the specified account and product over the given period and between a set of prices

Sales Data.csv - sample sales data file that can be loaded into Analytics Cloud as a dataset

Sales Data Append.csv - sample sales data file that can be loaded with an Append External Data API operation to add additional months of data to Sales Data.csv

Sales Data Identity.csv - sample sales data for 2014 & 2015 with an identity that can be used for upsert/delete External Data API operations

Sales Data Identity Upsert.csv - sample sales data to modify one period in 2015 and add data for 2016.  Used in conjuntion with Saled Data Identity.csv

Sales Data.json - metadata file associated with creating the Sales Data dataset

Sales Data Identity.json - metadata file assocaited with Sales Data Identity and Sales Data Identity Upsert that includes a unique identifier designation.

SalesEdgeEltWorkflow.json - dataflow json that extracts accounts from Salesforce and combines with the external sales data from the csv file
