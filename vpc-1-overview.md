## VPC (Virtual Private Cloud) overview

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

- AWS customers are welcome to carry out security assessments or penetration tests against their AWS infrastructure without prior approval for 8 services only. You should request authorization for other simulated events.

- When you create a custom VPC, a default Security Group, network access control list (ACL), and route table are created automatically. You must create your own subnets, internet gateway, and NAT gateway (if you need one).

- AWS releases your instance's public IP address when it is stopped, hibernated, or terminated. Your stopped or hibernated instance receives a new public IP address when it is started.

- You can have up to five Amazon VPCs per AWS account per AWS Region.

- Security groups control access at the instance-level, they support "allow" rules only, and they evaluate all rules before deciding whether to allow traffic into the instance(s).

- Security groups operate at the instance level, they support "allow" rules only, and they evaluate all rules before deciding whether to allow traffic.
