# Services Used:

AWS Amplify (Console & CLI), AWS IAM, AWS Cognito, AWS AppSync, Amazon S3, Amazon DynamoDB (GraphQL API)

<br/>

# File/Directory Details:

## React directory created via `create-react-app` to bootstrap a React application.

When in the project directory, run `npm start` in the command line.

## amplify.yml

Adds backend section to default amplify.yml

## schema.graphql

Schema for the GraphQL API used by the application

<br/>

## Amplify CLI Commands:

`npm install -g @aws-amplify/cli` to install the Amplify CLI<br/>
`amplify configure` to configure the Amplify CLI<br/>
`amplify console` to view your Amplify application via the CLI<br/>

`npm install aws-amplify @aws-amplify/ui-react` to install the UI-React library to utilize framework-specific UI components<br/>
`amplify add auth` to create an authentication service<br/>
`amplify push --y` to deploy the authentication service after it has been configured locally<br/>

`amplify add api` to add APIs to your application (GraphQL API)<br/>
`amplify console api` to view the GraphQL API

`amplify add storage` to add image storage functionality
