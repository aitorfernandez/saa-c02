## HA Elastic Load Balancers

- 4 tyes

  - Application Load Balancers, smart balancer, intelligent routing, conditions, etc.
  - Network Load Balancers, extreme performance, up to layer 4.
  - Gateway Load Balancer, deploy and manage a fleet of third-party virtual appliances that support GENEVE.
  - Classic Load Balancers, basic load balancing at the most const-effective rate.

- 504 error means the gateway has timeout. This means that application is not responding.

- X-Forwarded-For header for IPv4 address of the user.

- Instances monitored by ELB are reported as Inservice or OutofService.

- Load Balancers have their own DNS name, never given an IP address. (But you can get static IP for Network load balancer).

- https://aws.amazon.com/elasticloadbalancing/faqs/

- Sticky Sessions bind user session to a specific EC2 instance.

- Cross Zone Load Balancing can be enabled or disabled.

- Path patterns, specific paths (www.foo.com/images/) to an EC2 instances only for images for example.
