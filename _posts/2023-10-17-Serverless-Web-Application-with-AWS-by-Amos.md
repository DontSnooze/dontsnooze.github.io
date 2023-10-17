---
layout: post
title:  "Serverless Web Application with AWS"
date:   2023-10-17 12:00:00 -0400
categories: aws web development serverless
---

Serverless Web Application with AWS by [Amos](https://github.com/amostodman).

This is a demo project using AWS Lambda, Amazon API Gateway, AWS Amplify, Amazon DynamoDB, and Amazon Cognito to create a serverless web application.

**Overview**:

This app enables users to manage a collection of *"Projects"* each containing a name, description and an image link. The application presents users with an HTML-based user interface for adding, editing and removing projects. The application interacts with a RESTful web service on the backend to submit changes. The application also provides facilities for users to register with the service and log in before managing projects.

**Architecture**:

- Static Web Hosting: [AWS Amplify Console](https://aws.amazon.com/amplify/) provides continuous deployment and hosting of the static web resources including HTML, CSS, JavaScript, and image files which are loaded in the user's browser.
- RESTful API: JavaScript executed in the browser sends and receives data from a public backend API built using [AWS Lambda](https://aws.amazon.com/lambda/) and [Amazon API Gateway](https://aws.amazon.com/api-gateway/).
- User Management: [Amazon Cognito](https://aws.amazon.com/cognito/) provides user management and authentication functions to secure the backend API.
- Serverless Backend: [Amazon DynamoDB](https://aws.amazon.com/dynamodb/) provides a persistence layer where data can be stored by the API's Lambda function.

||
| :---: |
| <img src='https://dontsnooze.github.io/DSMedia/AWSServerlessWebApp/images/AWSServerlessProjectArchitecture.png' width='65%'> |

**Development**:

- Created using a cloud IDE from [AWS Cloud9](https://aws.amazon.com/cloud9/) which is managed by an [EC2](https://aws.amazon.com/ec2/) instance and provides terminal access to AWS.
- Code is stored using [AWS CodeCommit](https://aws.amazon.com/codecommit/) which provides highly scalable private Git repositories.

[Check it out on the web](https://master.d112v1xkvdthjg.amplifyapp.com/).

by [@amos](https://amostodman.github.io/)
