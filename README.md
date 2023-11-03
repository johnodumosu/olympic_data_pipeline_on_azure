
# Building Data Pipelines in Azure with Azure Synapse Analytics

## Business Overview

Data engineering is the profession of creating and constructing systems for gathering, storing, and analyzing large amounts of data. It is a vast field with applications in almost every sector. In this project, I will build a pipeline in Azure using Azure Synapse Analytics, Azure Storage and Azure Synapse SQL pool to perform data analysis on the 2021 Olympics dataset.

## Data Description:
    For this project, I used the 2021 Olympics dataset. This includes the information on more than 11,000 athletes competing in 47 sports for 743 Teams in the Tokyo Olympics in 2021. This dataset includes information on the participating Teams, Athletes, Coaches, and Entries by gender. It includes their names, nationalities, sports they compete in, and name of coaches. The dataset contains 5 files as follows:

    1. Athletes file (Details about Athletes):
    * Name
    * NOC
    * Discipline

    2. Coaches file (Details about coaches, countries and disciplines along with event):
    * Name
    * NOC
    * Discipline
    * Event

    3. EntriesGender file (Details about the Discipline and the number of females and males participating):
    * Discipline
    * Male
    * Female
    * Total

    4. Medals file (Contains the Medals and Scoreboard of countries that participated in Olympics):
    * Rank
    * Team/NOC
    * Gold
    * Silver
    * Bronze
    * Total
    * Rank by Total

    5. Teams file (Details about the Teams, discipline, Name of Country and the event):
    * Name
    * Discipline
    * NOC
    * Event

## Tech Stack

    Language: SQL
    Services: Azure Synapse Analytics, Azure Storage, Azure Synapse SQL Pool, Power BI

## Azure Synapse Analytics:
    Azure Synapse is an unlimited analytics service that combines enterprise data warehousing and big data analytics. It gives you the freedom to query data on your terms, using serverless resources or being provisioned  at scale. Azure Synapse brings these two worlds together with a unified experience to ingest, prepare, manage, and deliver data for  BI and machine learning needs right out of the box.

## Azure Storage:
    The Azure Storage platform is Microsoft's cloud storage solution for modern data storage scenarios. Azure Storage provides highly available, highly scalable, durable, and secure storage for a wide variety of data objects in the cloud.

## Azure Synapse SQL Pool:
    Azure Synapse Analytics is an analytics service that unifies enterprise data warehouses and big data analytics. Dedicated SQL pool refers to the enterprise data warehousing feature available in Azure Synapse Analytics. A dedicated SQL pool represents a collection of analytics resources provided when using Synapse SQL. The size of the dedicated SQL pool is determined by the data warehousing unit. Once a dedicated SQL pool is created, you can use simple PolyBase-T-SQL queries to import big data  and leverage the power of the distributed query engine to perform high performance analytics.

## Approach
    1. Create an azure storage account and upload data files in a container.
    2. Create an azure synapse analytics workspace.
    3. Create a SQL pool in azure synapse workspace.
    4. Create table structure in SQL pool.
    5. Create a data pipeline to ingest data from azure storage into SQL pool tables.
    6. Load data from SQL pool tables into Power BI.
    7. Prepare dashboard in Power BI.
    8. Publish Power BI dashboard in Azure synapse workspace.
    

## Architecture Diagram:
![Logo](https://project-architecture0102.s3.eu-west-2.amazonaws.com/Build_Data_Pipeline_using_Azure_Stream_Analytics_architecture.jpg)










    




