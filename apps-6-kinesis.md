## API Kinesis

- Kinesis is a platform on AWS to send your streaming data to.

- Kinesis makes it easy to load and analyze streaming data, and also providing the ability for you to build your own custom applications for your business needs.

- 3 types

  - Kinesis Streams

    - Place to store data from different sources (users, ec2, iOT, etc.) by default persistently store the data 24 hours by default, it can store it up to seven days.
    - Kinesis Streams consist of shards, 5 transactions per second for reads, up to a maximum total data read of 2 MB per second and up to 1000 records per second for writes, up to a maximum total data write rate of 1MB per second (including partition keys).
    - The total capacity of the stream is the sum of the capacities of its shards.

  - Kinesis Firehose

    - It's not persistent storage.
    - The data needs to be analyzed as it comes in.
    - Optional to have lambda function inside.
    - Amazon Kinesis Data Firehose is the easiest way to load streaming data into data stores and analytics tools.

  - Kinesis Analytics

    - Works with Kinesis Streams and Kinesis Firehose and analyze the data on the fly inside both.
