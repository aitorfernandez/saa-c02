## VPC PrivateLink

- Sharing Applications Across VPCs

  - Open the VPC up to the internet
    - Security considerations.
    - A lot more to manage.

  - VPC peering
    - Create and manage many different peering relationships.
    - The whole network will be accessible.

  - PrivateLink
    - The best way to expose a service VPC to tens, hundreds or thousands of customers VPCs.
    - Doesn't require VPC peering; no route tables, NAT IGWs, etc.
    - Require a Network Load Balancer on the service VPC and an Elastic Network Interface (ENI) on the customer VPC.
