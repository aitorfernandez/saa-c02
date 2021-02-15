## VPC overview

- VPC as a logical datacenter in AWS

- Consist:

  - Internet gateways or Virtual Private Gateways.
  - Route Tables.
  - Network Access Control Lists.
  - Subnets.
  - Security Groups.

- 1 Subnet cannot stretched over multiple availability zones.

- Multiple subnets in the same availability zone.

- Security Groups are Stateful; Network Access Control Lists are Stateless.

- No transitive peering, just direct connection between VPCs.
