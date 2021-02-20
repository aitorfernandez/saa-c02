## S3 Classes

- In cost order

  - S3 Standard

    - 99.99% availability.
    - 99.999999999% durability.
    - Stored redundantly across multiple decides in multiple facilities.
    - Designed to sustain the loss of 2 facilities concurrently.

  - S3-IA

    - For data that is accessed less frequently, but requires rapid access when needed. Lower fee than S3, but you are charged a retrieval fee.

  - S3 One Zone - IA

    - For where you want a lower-cost option for infrequently accessed data but doesn't require the multiple AZ data resilience.
    - No for crucial data.

  - S3 Intelligent Tiering

    - Designed to optimize costs by automatically moving data to the most cost-effective access tier without performance impact or operational overhead.

  - S3 Glacier

    - Secure, durable and low-cost storage class for data archiving. Retrieval times configurable from minutes to hours.

  - S3 Glacier Deep Archive

    - S3 Glacier Deep Archive is Amazon S3's lowest-cost storage class where a retrieval time of 12 hours is acceptable.
