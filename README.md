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

## Cloud-based data warehouses advantages
- Up-front costs
- Ongoing costs – pay as you go model
- Speed – substantially faster than on-premise options, due to the use of ETL which is not commonly used in on-premise options
- Flexibility – designed to account for the variety of formats & structures in big data
- Scalability – clouds are elastic

Earlier the focus of data warehouses was to stack data & focus on processing it for analytics. Now instead of just stacking the data, we are also focusing on storing loads of it as big data for advanced analytics. 

A traditional data warehouse can be compared to a data store & a modern data warehouse can be compared to a mega distribution store. Traditional data warehouses are focused more on data analytics & modern data warehouses focus on enterprise analytics.

**Data lake** – a repository that takes data from multiple sources & stores them in a variety of formats

## Advantages of a modern data warehouse
- User benefits
  - Less time spent on preparing & moving data
  - More time is spent on innovative analytics & new business models
  - Organizational benefits
  - Analyze new data faster
  - Reduce overall cost of ownership
  - Increased productivity
  - Technological benefits
  - 100% availability
  - Highly scalable
  - Resolve queries correctly in any schema
  - Provides real-time updates
  - Handles ETL processes
  - Supports batch & interactive workloads
  - Supports large no: of simultaneous users
Previously, the strategy used by organizations to save money was to transfer data from databases to file systems. Now, the trend is to move data from file systems to object storage. This is because cheap storage is of lower priority than data availability.