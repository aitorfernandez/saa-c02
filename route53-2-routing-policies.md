## Route53 Routing Policies

- Simple Routing.

  - One Record with multiple IP addresses. With multiple values in a record, Route53 returns all values to the user in a random order.

- Weighted Routing

  - Send the traffic to different regions around the world based on the weights that we supply.

- Latency-based Routing

  - Allows you to route your traffic on the lowest network latency, give them the fastest response time.
  - Routing data based on whether the resource is healthy or whether one set of resources is more performant than another.

- Failover Routing

  - Are used when you want to create an active/passive set up. For example primary site to be in EU-WEST-1 and your secondary in AP-SOUT-2. Or 404 page in S3.
  - Routing data based on whether the resource is healthy or whether one set of resources is more performant than another.

- Geolocation Routing

  - Let's you choose where your traffic will be sent based on the geographic location of your users. May the servers have the local language of the country customers.

- Geoproximity Routing (Traffic Flow Only)

  - Lets Amazon Route53 route traffic to your resources based on the geographic location of the users.
  - Geoproximity routing must be with Route53 traffic flow diagrams.

- Multivalue Answer Routing

  - return multiple values, such as IP addresses for your web servers, in response to DNS queries.
  - Similar to simple routing but it allows to put health checks on each record.
  - Random and best resiliency
