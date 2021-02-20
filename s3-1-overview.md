## S3

- Object-base, allows you to upload files.

- 0 bytes to 5 TB.

- There is unlimited storage

- Files are stored in Buckets.

- S3 is a universal namespace, names must be unique.

- Not suitable to install an operating system on.

- S3 responds with HTTP 200 status code for successful.

- By default buckets are PRIVATE.

- Setup access control to the buckets using

  - Bucket policies.
  - Access control lists.

- Setup access control can go down to the individual files.

- S3 buckets can be configure to create access log which log all request made to the S3 bucket. This can be sent to another bucket and even another bucket in another account.

- Key fundamentals of S3

  - Key (name of the object).
  - Value (the data and is made up of a sequence of bytes).
  - Version ID.
  - Metadata (Data about data you are storing, tags, etc.)
  - Subresources

    - Access Control Lists.
    - Torrent.

- Consistent model

  - Read after write consistency for PUTS of new objects.
  - Eventual Consistency for overwrite PUTS and DELETES (can take some time to propagate).
