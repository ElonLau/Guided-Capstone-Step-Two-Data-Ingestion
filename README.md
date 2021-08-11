# Guided-Capstone-Step-Two-Data-Ingestion

# Introduction

<br/>
After you have created the data structure diagram, you can start the build process. For a data
processing system, the first step is to ingest the data sources. Your Spring Capital data sources
come from stock exchange daily submissions files in a semi-structured text format. This means
the records follow a certain formatting convention like JSON, but don’t obey a tabular structure
formatted for a relational database. The data ingestion process parses the semi-structured data
out so it can be loaded into Spark.
<br/>
<br/>

# Learning Objectives

<br/>
<br/>

● Learn to parse CSV and JSON files <br/>
● Create a Spark DataFrame with defined schema <br/>
● Persist the Spark DataFrame into file system using partitioning <br/>
