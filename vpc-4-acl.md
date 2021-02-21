## VPC Network Access Control Lists (ACL) vs Security Groups

- VPC automatically comes with a default network ACL and by default it allows all outbound and inbound traffic.

- After create a custom new network ACL all rules inbound and outbound deny everything by default.

- Network ACLs always act first before security groups.

- Each network in the VPC must be associated with a network ACL. If don't explicitly associate with a network ACL the subnet is automatically associated with the default network ACL.

- You can block IP addresses using network ACLs, you can't with security groups.

- You can associate a network ACL with multiple subnets; however a subnet can be associated with only one network ACL at a time. When you associate a network ACL with a subnet, the previous association is removed.

- Network ACLs contains a numbered list of rules that is evaluated in order starting with the lowest number.

- Network ACLs have a separate inbound and outbound rules, and each rule can either allow or deny traffic.

- Network ACLs are stateless; responses to allowed inbound traffic are subject to the rules for outbound traffic (and vice versa).
