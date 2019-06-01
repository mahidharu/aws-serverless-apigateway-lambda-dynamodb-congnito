# aws-serverless-apigateway-lambda-dynamodb-congnito
This is a server less single page web application to display free and paid content only for authorized users using AWS services below
1) API Gateway - Access data from lambda to display it on the website
2) Lambda - Generate video URL's
3) DynamoDB - Store user and videos information
4) S3 -  Host Static Website and videos
5) Cloud Front - Serve website and free and paid content
6) Cognito - User sign and Login

TODO:
- Pending AWS cognito integration
- Pending Cloud Front distibution integration with lambda@edge
