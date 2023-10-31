# Web-Scraping with Microsoft-Fabric-

Reading dynamic data from any website and store that data along with time intelligence in our lakehouse as a delta table. Once the table is built we can add the notebook into a pipeline with scheduled refreshes so as to allow data to be tracked and logged continuously. We build datasets and reports on top of this table and hence when we refresh reports at a later point in time our updated data is reflected automatically. Using Fabric Data Activator we can also receive notifications when thresholds are met and exceeded. 
