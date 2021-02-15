## Direct Connect

- Establish private connectivity between AWS and you datacenter or office, which in many cases can reduce your network costs, increase bandwidth and provide a more consistent network experience.

- Useful for high throughput workloads.

- Stable and reliable secure connection.

- Steps to creating a Direct Connect:

  - Create a virtual interface in the Direct Connect console. This is a Public Virtual Interface.
  - Go to the VPC console and then to VPN connections. Create a customer Gateway.
  - Create a Virtual Private Gateway.
  - Attach the Virtual Private Gateway to the desired VPC.
  - Select VPN Connections and create new VPN Connection.
  - Select the Virtual Private Gateway and the Customer Gateway.
  - Once the VPN is available, setup the VPN on the customer gateway firewall.
