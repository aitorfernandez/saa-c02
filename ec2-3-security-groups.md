## EC2 Security Groups

- All inbound traffic is block by default.

- All outbound traffic is allowed.

- Changes to security groups take effect immediately.

- You can have any number of EC2 instances within a security group.

- You can have multiple security groups attached to EC2 instances.

- Security groups stateful. If open port, it will be open for both inbound and outbound.

- Network ACLs are stateless. Need open in both. inbound and outbound.

- You cannot block specific IP addresses using security groups, you need network ACLs.

- Specify allow rules but not deny rules.
