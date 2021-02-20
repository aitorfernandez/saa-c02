## S3 Buckets

- 3 different ways to share S3 buckets across accounts

  - Using bucket policies and IAM (applies across the entire bucket). Programmatic access only.
  - Using Bucket ACLs and IAM (individual objects). Programmatic access only.
  - Cross-account IAM roles. Programmatic and console access.

- Cross Region Replication

  - Versioning must be enabled on both the source and destination.
  - Files in an existing bucket are not replicated automatically after replica but the next files yes.
  - Delete markers are not replicated.
  - Deleting versions or delete markers will not be replicated.
