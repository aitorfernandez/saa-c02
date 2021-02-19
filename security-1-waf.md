## WAF

- Web app firewall that lets you monitor HTTP(s) request to CloudFront, ALB, or API Gateway.

- Control access to content with filtering rules to allow/deny traffic

  - IP addresses.
  - Query string parameters.
  - SQL query injection.

- Blocked traffic returns 403 Forbidden.

- Allow all request, except the ones you specify.

- Block all request, except the ones you specify.

- Count the request that match the properties you specify.

- Request properties

  - Originating IP address.
  - Originating country.
  - Request size.
  - Values in request headers.
  - String in request matching regular expressions patterns.
  - SQL code (injection)
  - XSS Cross-site scripting.

- AWS Firewall Manager centrally configure and manage firewall rules across and AWS Organization.

- WAF rules

  - ALB.
  - API Gateway.
  - CloudFront fistributions.

- AWS Shield Advanced protections

  - ALB.
  - ELB Classic.
  - EIP.
  - CloudFront distributions.

- Enable security groups for EC2 and ENIs.

- AWS WAF, Amazon firewall operates on layer 7 and expect that level of traffic useful for block common exploits like SQL injection or cross-site.

- Block IPs or range IPs use NACL which operates on layer 4.

- Possible attach WAF to CloudFront distribution.

- With an attack from a particular country, CloudFront can use geo match feature to block that country's traffic.

- Networks Access control lists (NACL) to allow or deny certain IPs or range of IPs.
