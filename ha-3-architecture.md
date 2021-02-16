## HA Architecture

- Always Design for failure

- Use Multiple AZ's and Multiple Regions where ever you can.

- Difference between Multi-AZ (disaster recovery) and Read Replicas (performance) for RDS.

- Difference between scaling out (Auto Scaling groups and add additional EC2 instances) and scaling up (Increase resources inside our EC2 instances, for example from t2.micro to a 6X extra large, RAM or CPU, etc.).

- Difference S3 storage classes.

  - Standard S3 and Standard S3 infrequently access are still highly available.
  - Redundancy storage or single S3 AZ is not highly available.
  - S3 Standard-IA provides rapid access to files and is resilient against events that impact an entire Availability Zone, while offering the same 11 9's of durability as all other storage classes.

- Consider the const element.
