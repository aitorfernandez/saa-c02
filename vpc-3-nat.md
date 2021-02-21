## VPC NAT

- NAT instance or NAT gateway is used to provide internet traffic to EC2 instances in a private subnets.

- NAT instances:

  - NAT instance is a single EC2 instance. When creating disable source/destination check on.
  - NAT instances must be in a public subnet.
  - There must be a route out of the private subnet to the NAT instance in order for this to work.
  - The amount of traffic depends on the instance size.
  - Not behind a Security group, exists on its own.

- NAT gateway is a highly available gateway allow you yo have your private subnets communicate out to the internet.

  - Redundant inside the Availability Zone.
  - 1 Nat gateway inside on AZ.
  - Starts at 5Gbps and scales to 45Gbps.
  - Not associated with security groups.
  - Automatically assigned a public ip address.
  - Remember to update your route tables.
  - No need to disable Source/Destination checks.

- NAT gateway in each AZ to avoid lose internet access if one AZ is down.
