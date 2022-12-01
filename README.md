# US Census Findings:
- This repository contains all the code used in Project 3 of Revature's 2022 Big Data cohort. 
This project scrapes US Census data and uses Apache Spark to answer questions based 
on the data. Questions we ask include:
  - What was the total population of each state in 2000, 2010, and 2020?
  - Which region has the highest population?
  - Which region is growing the fastest?
  - Are there any states with a decreasing population?
  - What are the populations of different ethnicities and races?
  - How does the predicted population of 2020 compare to the actual population in 2020?
  - How did each states population change throughout the decades?
  - Which states are growing the fastest?
  - What predictions about the future population can we make based on this data?

## What's in this Repository?
- [OutputCSV2](https://github.com/Revature-William-T-1377/US-Census-Findings/tree/staging/OutputCSV2)
Data storage for ETL operations.
- [resultCsv](https://github.com/Revature-William-T-1377/US-Census-Findings/tree/staging/resultCsv)
Query results stored as CSV files.
- [src/main/scala/etl](https://github.com/Revature-William-T-1377/US-Census-Findings/tree/testing/src/main/scala/etl)
Contains the code for data scraping and ETL operations.
- [src/main/scala/queries](https://github.com/Revature-William-T-1377/US-Census-Findings/tree/testing/src/main/scala/queries)
Contains the queries.
- [src/main/scala/sparkConnector](https://github.com/Revature-William-T-1377/US-Census-Findings/tree/testing/src/main/scala/sparkConnector)
Contains code used to create a spark connection as well as scraping and ETL operations.
- [src/main/scala/Main.scala](https://github.com/Revature-William-T-1377/US-Census-Findings/blob/testing/src/main/scala/Main.scala)
Scala program to run queries and output the results.
- [tableFiles](https://github.com/Revature-William-T-1377/US-Census-Findings/tree/staging/tableFiles)
Contains extra files from the US Census that were used in ETL operations.
