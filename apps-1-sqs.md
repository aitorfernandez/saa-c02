## Applications SQS

- Web service that gives you access to a message queue that can be used to store messages while waiting for a computer to process them.

- Distributed queue system that enables web service applications to quickly and reliable queue messages that one component in the application generates to be consumed.

- A queue is a temporary repo for messages that are waiting processing.

- Using Amazon SQS, you can decouple the components of an application so they run independently.

- SQS is message-orientated API.

- Up to 256 kilobytes of text. More size will be stored on S3.

- Messages can be kept in the queue from 1 minute to 14 days, default period 4 days.

- SQS is pull-based, not pushed-based, need EC2 instance pulling the messages.

- Standard SQS (order is not guaranteed and messages can be delivered more than once) and FIFO SQS (order strictly maintained and messages are delivered only once).

- Visibility timeout is the amount of time that the message is invisible in the SQS queue after a reader picks up the message. The message can be delivery twice if the visibility time is not long enough.

- Visibility timeout maximum is 12 hours.

- SQS guarantees that the messages will be processed at least once.

- Amazon SQS long polling is a way to retrieve messages from your Amazon SQS queues. While the regulator short polling returns immediately (even if the message queue being polled is empty), long polling doesn't return a response until a message arrives in the message queue, or the long poll time out.

- Long polling essentially won't return a response until a message arrives in the queue. Prevent a EC2 instance be asking to the queue all the time without messages.

- You need implement your own application-level tracking, especially if the app uses multiple queues.
