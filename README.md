# splunk-aws-kinesis-logging
This repo includes the Project Trumpet CF template used for deploying Kinesis Firehose infrastructure in AWS for monitoring Chainlink, adapter, db, and virtually any other logs being sent to Cloudwatch Logs groups.  Additionally, there is a lambda function example for filtering and parsing the logs to include on the fly sourcetype assignment and different index destinations based on the CW Logs group name.


