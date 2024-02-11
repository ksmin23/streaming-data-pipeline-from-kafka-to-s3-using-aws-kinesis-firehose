# Managed Data Delivery from Apache Kafka to Amazon S3 using Kinesis Data Firehose

This repository contains a set of example projects to continuously load data from an Amazon Managed Streaming for Apache Kafka (Amazon MSK) to Amazon Simple Storage Service (Amazon S3).
We use Amazon Kinesis Data Firehose—an extract, transform, and load (ETL) service—to read data from a Kafka topic, transform the records, and write them to an Amazon S3 destination.

| Example | Architecture |
|---------|--------------|
| [msk-firehose-s3-stack](./msk-firehose-s3-stack/) | ![msk-firehose-s3-arch](./msk-firehose-s3-stack/msk-firehose-s3-arch.svg) |
| [msk-serverless-firehose-s3-stack](./msk-serverless-firehose-s3-stack/) | ![msk-serverless-firehose-s3-arch](./msk-serverless-firehose-s3-stack/msk-serverless-firehose-s3-arch.svg) |

Enjoy!


## References

 * [Amazon MSK Introduces Managed Data Delivery from Apache Kafka to Your Data Lake (2023-09-27)](https://aws.amazon.com/blogs/aws/amazon-msk-introduces-managed-data-delivery-from-apache-kafka-to-your-data-lake/)
   ![amazon-msk-managed-delivery-to-s3](https://d2908q01vomqb2.cloudfront.net/da4b9237bacccdf19c0760cab7aec4a8359010b0/2023/09/14/diagram-msk-v1.png)
