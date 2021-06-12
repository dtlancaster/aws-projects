# Full-Stack Developer

Full-Stack development involves <b>client and server-side code</b> in addition to a full suite of technologies that make up how a website works. On the <i>client</i> side, the infrastructure that users see on a website (e.g., the layout, the positioning of text and images, colors, fonts, buttons, etc.) using, typically, HTML, CSS, and JavaScript. On the <i>server</i> side, algorithms and business logic is created to manipulate data that is received from the client side.

<br/>

## Goals of this Project:

### 1. Deploy a web app to AWS
Create and host a web app that renders "Hello World" and set it up so users can easily access it.

### 2. Build a serverless backend
Create a serverless function to trigger based on custom inputs in a text field.

### 3. Store data in a database
Store data from the custom input field and render that text up on the website.

<br/>

## Services Used:
AWS Amplify, Amazon API Gateway, AWS Identity and Access Management, AWS Lambda, Amazon DynamoDB

<br/>

# Application Architecture

![application architecture](https://user-images.githubusercontent.com/60489834/121789950-7868a400-cba8-11eb-84c6-6b3f84be2b29.png)

<br/><br/>

# File Details

## index.html
Contains the static content that is being hosted.

## HelloWorldFunction
Contains the Lambda function. I have left examples of this serverless function in both Python and JavaScript.

## inline_policy.json
Gives permissions to our Lambda function to use the DynamoDB service.

# Application Functionality

All the AWS services that are utilized in this project can securely communicate with one another. When a user clicks on a button in a web app, it makes a call to our API, which triggers our Lambda function. Our Lambda function writes to a database and returns a message to our client via API Gateway. All permissions are managed by IAM.