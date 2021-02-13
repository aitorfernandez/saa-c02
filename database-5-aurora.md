## Database Aurora

- It's Amazon's own proprietary database.

- It's a MySQL and PostgreSQL compatible relational database engine that combines the speed and availability of high-end commercial databases with the simplicity and cost-effectiveness of open source DBs.

- 5 times better performance than MySQL

- 3 times better performance than PostgreSQL

- Start with 10GB and scales in 10GB increments to 64TB.

- Compute resources can scale up to 32vCPUs and 244 GB of Memory.

- 2 copies of your data is contained in each availability zone with a minimum of 3 availability zones. 6 copies in total.

- Aurora storage is self-healing. Data blocks and disk are scanned for errors continuously.

- Handle the loos of up to copies of data without affecting database write availability.

- Possible take and share snapshots with other AWS accounts.

- Automated failover is only available with Aurora Replicas.

- Automated backups turned on by default.

- Aurora serverless for a simple cost-effective option for infrequent intermittent or unpredictable workloads.
