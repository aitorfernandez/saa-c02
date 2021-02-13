## Database DynamoDB

- Stored on SSD storage

- Spread across 3 geographically distinct data centres

- Two different types of read models

  - Eventual Consistent Read (Default, one-second rule).
  - Strongly Consistent Read (Read data after write within os less than one second).

- Primary key can be either a single-attribute or a composite partition-sort key.

- There will always be a charge for provisioning read and write capacity and the storage of data.
