# sf-cf-createApprovalEntry
This codebase is created to experiment with Serverless framework. I have created a sample AWS app using Serverless.

## Setup
- Setup AWS CLI (details see https://docs.aws.amazon.com/lambda/latest/dg/setup-awscli.html)
- Install NodeJS and NPM
- Setup Serverless (details see https://serverless.com/framework/docs/providers/aws/guide/quick-start/)
- Clone the repo
- Run "npm install"

## Deploy
Run the following command to deploy the whole service.

serverless deploy -v

Much faster option is to use the following command (if you have modified the function only).

serverless deploy hello -f hello

## Unit Tests
Run "npm test" to execute unit tests

## Functional Tests
TODO:
