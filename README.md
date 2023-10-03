# Modern data warehouses

**Data warehouses** – a collection of methods, techniques & tools used to support people conducting data analysis which helps with decision making processes & improves information resources. Primary purpose of a data warehouse is for BI

## Types of data warehousing
- *On-premises data warehouse*
- *Cloud data warehouse systems* – address all issues faced by traditional data warehousing 

## Data warehouse architecture
There are many different types of data warehousing solutions. One of the most common types of traditional warehouse architecture is the 3-tier architecture approach:
- *Bottom tier* – contains actual database server
- *Middle tier* – server for online analytical processing (OLAP). This server is responsible for transforming data. It can map multi-dimensional data to relational operations or leverage a multi-dimensional OLAP model, etc.
- *Top tier* – similar to UI layer. Contains tools common for data warehousing analytics such as reporting & mining.

## Data warehousing approaches
2 of the most commonly used approaches to data warehousing were created by Bill Inmon & Ralph Kimball.
#### Bill Inmon’s approach
- It’s also referred to as a top-down approach
- Data warehouse is treated as a central repository for the data
- Data marts are then created to address individual business lines
#### Ralph Kimball’s approach
- Bottom-up approach
- Data mart is the main method for data storage
- Data warehouse is then created & comprises of multiple data marts with shared analytics, reporting & BI essentials. This allows for uniform analytics jobs

## On-premises data warehouse components
- *Data analytics layer* - There is a specific layer for data analytics, data mining jobs
- *Staging area* – different sources have different formats & structures. In the staging area, data is converted into a specific structure & format
- *Data Marts* – they assist the staging area by acting as a housing for a specific line of business & are summarized for specific queries
