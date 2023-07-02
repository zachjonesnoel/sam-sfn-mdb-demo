# AWS SAM app to demonstrate Step Function and EventBridge with MongoDB API destination

This demonstrates the usage of orchestration and choreography patterns in AWS Serverless.

### Prerequisites 

- AWS Account
- AWS SAM CLI
- [MongoDB Data API](https://www.mongodb.com/docs/atlas/api/data-api-resources/)

### How to test

Clone this project and use [AWS SAM CLI](https://aws.amazon.com/serverless/sam/) (Installation steps available in the link)

Build the project with AWS SAM
```
sam build
```

Deploy with AWS SAM
```
sam deploy -g
```
