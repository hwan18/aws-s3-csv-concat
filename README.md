# aws-s3-csv-concat
AWS services such as Amazon Forecast, Sagemaker Autopilot, etc. produces prediction outputs in divided CSV files for memory optimization and performance.

This is a simple easy to use code to join the divided files in to one CSV file.

Before using, your Sagemaker Notebook Instance must have IAM Role access to all S3 buckets if you want to pull data from S3 buckets not directly connected to your Sagemaker domain.
