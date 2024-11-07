# API REST with AWS Lambda

This project demonstrates how to create a REST API using AWS Lambda and the Go programming language. The API is built using the Fiber framework and deployed using the AWS Serverless Application Model (SAM).

## Prerequisites

- AWS CLI configured with appropriate permissions
- AWS SAM CLI
- Go programming language installed

## Project Structure

- `main.go`: The main application code.
- `template.yaml`: The SAM template for deploying the application.
- `.env`: Environment file to configure the application.

## Running Locally

To run the project locally, ensure that the `.env` file is properly configured with `LAMBDA_ENABLED=false`. Then, use the following command:

## Building and Deploying
To build the project, use the following command:

```bash
sam build --template template.yaml
```

To deploy the project, use the following command:
```bash
sam deploy --guided
```
