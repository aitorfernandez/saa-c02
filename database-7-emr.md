## Database EMR (Elastic Map Reduce)

- Cloud big data platform for processing vast amounts of data using open-source tools such as Apache Spark, Apache Hive, Apache HBase, Apache Flink, Apache Hudi and Presto.

- Less than half the cost of traditional on-premises solutions.

- The central component of Amazon EMR is the cluster. A cluster is a collection of Amazon Elastic Compute Cloud instances. Each instance in the cluster is called a node. Each node has a role within the cluster, referred to as the node type.

- Nodes

  - Master node, manages the cluster.
  - Core node, runs tasks and stores data.
  - Task node, only runs tasks and does not store data in HDFS.

- To persist the log in master node (/mnt/var/log) move your log data over the S3. Archives the log files at five-minute interval and only possible set this up when creating the cluster.
