## Database Redshift

- Its used for business intelligence, Amazon's data-warehouse solution.

- Available in only 1 Availability Zone.

- Single node (160GB) or Multi-Node (up to 128 Nodes).

- The most suitable for online analytics processing (OLAP).

- Backups

  - Backup enabled by default with a 1 day retention period.
  - Maximum retention period is 35 days.
  - Redshift always attempts to maintain at least three copies of your data (The original, the replica and a backup in S3)
  - Redshift can also asynchronously replicate the snapshots to S3 in another region for disaster recovery.
