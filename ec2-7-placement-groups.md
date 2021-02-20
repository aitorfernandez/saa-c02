## EC2 Placement Groups

- Three types

  - Clustered Placement group. Low Network Latency / High Network
  - Spread Placement group. Individual Critical EC2 instances.
  - Partitioned. Multiple EC2 instances HDBS, HBase, and Cassandra.

- A clustered placement group can't span multiple AZs, spread and partitioned can.

- The placement group name must be unique in your AWS account.

- AWS recommend homogenous instances within clustered placement groups.

- AWS now allows you to move an existing instance into a placement group.
