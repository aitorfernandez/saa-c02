## Database backups

- Two different types of backups for RDS.

  - Automated backups, recover your database to any point in time within a "retention period" (between one and 35 days). Will take a full day snapshot and will also store transaction logs.

    - Are enable by default.
    - The backup data is stored in S3 and you get free storage space equal to the size of the database.
    - Backups are taken within a defined window.

  - Snapshots are done manually. They are stored even after delete the original RDS instance (unlike automated backups).

- Restore backup will be a new RDS instance with a new DNS endpoint.

- Encryption is supported for MySQL, Oracle, SQL Server, PostgreSQL, MariaDB, and Aurora using KMS (Key Management Service).

- If the RDS instance is encrypted, all are encrypted, data, automated backups, read replicas and snapshots.

- Multi-AZ allows you to have an exact copy of your production database in another Availability Zone. AWS handles the replication.

- Multi-AZ is for Disaster Recovery only, it's not primarily used for improving performance. Multi-AZ for the folowing DBs

  - SQL Server
  - Oracle
  - MySQL Server
  - PostgreSQL
  - MariaDB

- Read Replicas is used for improving performance. Architect the EC2 instances read from different replicas, and then they only write to a single database.

- Read Replicas allow you to have a read-only copy of the production database. You can use read replicas primarily for very read-heavy database workloads.

- Read replicas

  - Can be Multi-AZ
  - Used for scaling.
  - Must have automatic backups turned on in order to deploy a read replica.
  - Up to 5 read replica copies of any database.
  - Can be read replicas of read replicas.
  - Each replica have its own DNS end point.
  - Read replicas can have Multi-AZ.
  - Can be promoted to be their own database. This breaks the replication.
  - Can be in a second region.
