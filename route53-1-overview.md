## Route53 overview

- Route 53 is Amazon's DNS Service.

- ELBs (Elastic Load Balancer) do not have pre-defined IPv4 addresses, needs resolve using DNS name.

- Never going to get an IPv4 address for an Elastic Load Balancer.

- CNAME maps a name to another name. A CNAME record can redirect DNS queries to any DNS record. CNAME maps to the host name.

- You can't create a CNAME record for example.com, but you can create an alias record for example.com that routes traffic to www.example.com.

- Alias records con only redirect queries to selected AWS resources:

  - Amazon S3 buckets.
  - CloudFront distributions.
  - Another record in the same Route 53 hosted zone.
  - Alias Records provide a Route 53–specific extension to DNS functionality.
  - An alias could be created for the ELB. Alias records provide a Route 53–specific extension to DNS functionality

- The zone apex is where the SOA and NS (and often MX) records for a DNS zone are placed.

- Common DNS Types:

  - SOA Records
  - NS Records
  - A Records
  - CNAMES
  - MX Records - Emails
  - PTR Records - Reverse A record

- You can buy domain names directly with AWS, it can take up to 3 days to register depending of the circumstances.

- With Route 53, there is a default limit of 50 domain names. However, this limit can be increased by contacting AWS support.
