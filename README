# Practical Data Engineering with Azure Synapse Analytics
This repo has the accompanying materials for the class.

## Source Data Files
In order to run the demos you need the source data files (parquet, csv, xml, json, etc) that are part of the class. This will be provided by the instructor.

## SQL Dedicated Pool
Scripts:
- D1_SQLDW_MusicService: covers reading data into the dedicated pool, table distribution, query analysis
- D2_SQLDW_Workload_Management: covers monitoring resources and working with workload groups and classifiers
- D3_SQLDW_MusicService_Cleanup: drops all the tables so the demos can be redone
- D4_SQLDW_IncrementsSchema: creates the schema (tables and sps) to go with Pipelines D11
- D4_SQLDW_IncrementsSetup: does cleanup and setup to do Pipelines D11

## SQL Serverless Pool
Scripts:
- D1_SQLOD_MusicService: covers reading and writing data with External Tables and OpenRowset with many examples
- D2_SQLOD_SparkIntegration: shows the integrated catalog in action. Run after completing Spark D1
- D3_SQLOD_CosmosLink: covers querying CosmosDb through SynapseLink (requires a separate CosmosDb account with the analytical store enabled)
- D3_SQLOD_ETL_Tables: used in conjunction with Pipelines D2, D3, D5, D7, D8, D9
- PRE_DEMOS_SQLOD_DropTables: drops the tables so the demos can be redone

## Spark Pool
Notebooks:
- D1_MusicService_Notebook: main Notebook that covers all the Spark fundamentals
- D2_MusicService_Delta_Notebook: covers open source Delta Lake
- D3_MusicService_Cleaning: example of data cleanup with Spark
- D4_MusicService_PySpark_Notebook: lots of examples on how to do things with PySpark
- D5_MusicService_SynapseConnector_Notebook: example of reading from the Synapse Dedicated Pool
- D6_MusicService_Parameterized_Notebook: example of a parameterized Notebook
- D7_MusicService_CosmosLink: covers querying CosmosDb through SynapseLink (requires a separate CosmosDb account with the analytical store enabled)
- PRE_DEMOS_MusicService_Cleanup: drops all the tables so the demos can be redone

## Pipelines
Pipelines:
- D1_Trigger_SQLOD_UserArtistPlays: pipeline triggered by a file drop
- D2_MDF_GenerateAugmentedArtistInfo: mapping data flow example
- D3_MDF_GenerateAugmentedArtistInfo_Drift: mapping data flow example with schema drift
- D4_MDF_UserArtistPlays_AntiPattern: what NOT to do when doing data flows
- D5_MDF_UserArtistPlays_Contained: all logic in the data flow
- D6_Parameter_To_Spark_Notebook: calls a notebook and passes a parameter
- D7_WDF_UserDetailsWrangled: does a wrangling data flow on user data
- D8_SQLOD_UserSignup_DeltaCopy: does a delta copy using the serverless engine (cheap!)
- D9_WDF_SQLOD_UserDetails_TimeConversion: does the WDF transformation using the serverless engine
- D10_Parameterized_DeltaCopy: example of delta copy using the dedicated pool, watermarks and logging
