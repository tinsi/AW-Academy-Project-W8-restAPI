# AW-Academy-Project-W8-restAPI

*Week 8 project for AW Academy's AWS Developer Programme*

## Requirements and the goal of the project
- use the following AWS Serverless resources: Lambda, API Gateway, DynamoDB/Aurora
  - and at least one of the following: SNS, SQS, SES, S3, EventBridge, Kinesis
- use some kind of open data source or REST APIs
- the target of this project is to use and process data from open API and offer the essential part of the data to user via self-made API.
- ADDITIONAL TARGET: resources can be launched with some kind of IaC template

## Result

As a result, we combined multiple rest API:s to one API Gateway, using Lambda functions and Serverless. An email of the combined data was sent via AWS SNS once a day.
