## Serverless Lambda

- Abstraction layer. Is a compute service where you can upload your code and create lambda function.

- AWS lambda takes care of provisioning and managing the servers that you use to run the code.

- Use lambda in the the following ways

  - As an event-driven compute service where AWS lambda runs your code in response the events. These events could be changes to data in a S3 or DynameDB table.
  - As a compute service to run your code in response to HTTP request using Amazon API Gateway or API calls made using AWS SDKs.

- Lambda function can triggers other lambda functions.

- Run independently two users making a request, will trigger two lambda functions. Scales instantly don't need worried about autoscaling.

- Languages

  - Node.
  - Java
  - Ruby
  - Python
  - C#
  - Go
  - Powershell

- Priced is per request, 1MM request are free, $0.20 per 1 million request.

- Duration is calculated from the time the code begins until returns. $0.00001667 for every GB-second used.

- No servers.

- Continuous scaling.

- Super cheap.

- Scales out (not up).

- AWS X-ray helps you debug your serverless applications.

- Lambda can do things globally.

- No RDS trigger.

- 'Serverless' computing is not about eliminating servers, but shifting most of the responsibility for infrastructure and operation of the infrastructure to a vendor so that you can focus more on the business services, not how to manage the infrastructure that they run on.

- ALB, Cognito, Lex, Alexa, API Gateway, CloudFront, and Kinesis Data Firehose are all valid direct (synchronous) triggers for Lambda functions. S3 is one of the valid asynchronous triggers.
