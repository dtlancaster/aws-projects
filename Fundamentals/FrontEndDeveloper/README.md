# Front-End Developer

Front-end or mobile development involves building feature-rich web and mobile applications. Using popular front-end web or mobile frameworks including React, React Native, Vue, Angular, Iconic or iOS/Android, you can build the presentation layer of your app (e.g., the layout, the positioning of text and images, colors, fonts, buttons, etc.). You also work with backend APIs and services to add interactivity to your web or mobile application.

Using Amplify, you can use your existing front-end skillset to add cloud functionality into your application such as auth, data, analytics, push notifications, and more.

<br/>

# Goals for this Project:

## 1. Host Web or Mobile Application

Build and host a web or mobile application on the AWS Global content delivery network (CDN).

## 2. Add Authentication

Add authentication to the application to enable sign-in and sign-out.

## 3. Add Database and Storage

Add a GraphQL API, database, and storage solution to the application.

<br/>

# Services Used:

AWS Amplify (Console & CLI), AWS IAM, AWS Cognito, AWS AppSync, Amazon S3, Amazon DynamoDB (GraphQL API)

<br/>

# File/Directory Details:

## amplifyapp 

Directory created via `create-react-app` to bootstrap a React application.
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
