# Serverless DynamoDB CRUD API

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/YourUsername/serverless-dynamodb-crud-api/blob/main/LICENSE)

This project showcases a Serverless Framework application that implements a simple HTTP API using Node.js, running on AWS Lambda and API Gateway. The API enables CRUD (Create, Read, Update, Delete) operations on a DynamoDB table.

## Usage

### Deployment

1. Make sure you have the Serverless Framework installed. If not, you can install it globally by running:

  ```shell
  npm install -g serverless

2. Clone this repository:
  ```shell
  git clone https://github.com/Adigun-Mubaraq/serverless-dynamodb-crud-api.git

3. Navigate to the project directory:
  ```shell
  cd serverless-dynamodb-crud-api

4. Install the required dependencies:
  ```shell
  npm install

5. Deploy the application to your AWS account:
  ```shell
  serverless deploy

6. After deployment, you will receive the API endpoint URL and the deployed function details.

## API Endpoints
  GET /customer: Retrieves all customers from the DynamoDB table.
  POST /customer: Creates a new customer record in the DynamoDB table.

Note: This project includes basic endpoints for demonstration purposes. You can extend it to include additional CRUD operations and modify the DynamoDB table structure as needed.
