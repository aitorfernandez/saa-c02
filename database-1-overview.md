## AWS Database overview

- RDS (OLTP Online transaction processing) comes in six different flavors

  - SQL Server
  - MySQL
  - PostgreSQL
  - Oracle
  - Aurora
  - MariaDB

- RDS runs on virtual machines (cannot ssh in to these VM, no operating system level access)

- RDS is not Serverless

- Aurora and DynamoDB are Serverless

- DynamoDB is Amazon's no SQL solution.

- Redshift is Amazon's data warehousing solution (online analytics processing, BI (Business Intelligence or Data Warehousing).

- Elasticcache comes in two different flavors, Memcached and Redis. Speed up performance of existing databases (frequent identical queries).

- RDS is most suitable for OLTP workloads

- Amazon RDS for SQL Server database instances with up to 16TB of storage.

- Automated backups are enabled by default with new RDS DB instances.

- Don't need to specify a destination port number when you create DB security group rules for RDS instances.

- Reserved DB instance benefits apply for both Multi-AZ and Single-AZ configurations.

- When you create a DB instance, you can choose an Availability Zone or have AWS choose one for you.

- The easiest way to find out if an error occurred is to look for an Error node in the response from the Amazon RDS API.
