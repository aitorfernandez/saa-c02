## VPN CloudHub

- If you have multiple sites, each with its own VPN connection, you can use AWS VPN CloudHub to connect those sites together.

- Hub-and-spoke model.

- Low cost; easy to manage.

- It operates over the public internet, but all traffic between the customer gateway and the AWS VPN Cloud is encrypted.

- A customer gateway is a resource that is installed on the customer side and provides a customer gateway inside a VPC.

- A Virtual Private Gateway sits at the edge of your VPC and is a key component when using a VPN. It's responsible for site-to-site connection from on-premises to a VPC.

- It is likely that if you choose to run your VPN through a Direct Connect from your datacenter to the AWS network that your VPN connection will be both faster, and more secure. However data charges are still incurred whilst using Direct Connect.
