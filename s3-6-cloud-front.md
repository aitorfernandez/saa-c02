## S3 CloudFront

- Edge Location. This is the location where the content will be cached. This is separated to and AWS Region/AZ.

- Origin. This is the origin of all files that the CDN will distribute. This can be either and S3 bucket, an EC2 instance, an Elastic Load Balancer or Route53.

- Distribution. This is the name given to the CDN which consists of a collection of Edge Locations.

- Web Distribution. Typically used for websites.

- RTMP. Media stream.

- Edge location are not just READ only, you can write to them too.

- Objects are cached for the life of the TTL (Time to Live).

- You can clear cached objects, but you will be charged.
