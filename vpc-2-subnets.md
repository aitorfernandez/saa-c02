## VPC and Subnets

- https://docs.aws.amazon.com/vpc/latest/userguide/VPC_Subnets.html

- Whit a new VPC a default Route Table, Network Access Control List (NACL) and a default Security Group is created.

- It won't create any subnets or a default internet gateway.

- Amazon reserve 5 IP addresses within your subnets.

- Only 1 Internet Gateway per VPC.

- Security Groups do not span VPCs.

- In a custom VPC with new subnets in each AZ, there is a route within the route table that supports communication across all subnets/AZs.
