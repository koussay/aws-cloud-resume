# AWS Cloud Resume Challenge

![AWS Cloud Resume Challenge]([cloud_challenge.png](https://github.com/koussay/aws-cloud-resume/blob/main/koussay-portfolio/images/cloud_challenge.png))

Welcome to my AWS Cloud Resume Challenge project repository! This project serves as a demonstration of my AWS skills and showcases my ability to create a serverless web application hosted on AWS. Below, you'll find an overview of the project and its architecture, as well as details on how to access the deployed website.

## Project Overview

The AWS Cloud Resume Challenge is a popular initiative that provides an opportunity to create a serverless resume website hosted on AWS. This project is a reflection of my expertise in deploying web applications using AWS services. Here's what you'll find in this repository:

- **Website Content**: The website includes my professional resume, contact information, links to my social profiles, and other relevant information. It serves as a virtual representation of my qualifications and skills.

- **Serverless Visitor Tracking**: To demonstrate my serverless architecture skills, I've implemented a visitor tracking system using AWS Lambda and DynamoDB. This serverless API records visitor data, including timestamps and IP addresses, in DynamoDB. It showcases my ability to design efficient and scalable serverless solutions.

- **GitHub Actions**: I've set up GitHub Actions to automate the deployment process. This includes building the website, deploying it to an S3 bucket, and invalidating the CloudFront cache to ensure that visitors always see the latest content. This showcases my DevOps skills and knowledge of CI/CD pipelines.

## Project Architecture

The architecture of my AWS Cloud Resume Challenge project follows serverless best practices, utilizing various AWS services:

- **Amazon S3**: The S3 bucket hosts the static assets of the website, such as HTML, CSS, JavaScript, and images.

- **AWS Lambda**: Lambda functions are used to handle dynamic content generation and server-side logic.

- **Amazon API Gateway**: API Gateway enables communication between the frontend and backend components of the application.

- **AWS CloudFront**: CloudFront is employed as a Content Delivery Network (CDN) to optimize website delivery.

- **DynamoDB**: I've included an optional DynamoDB table to store and retrieve data, such as visitor count.

## Getting Started

To view my AWS Cloud Resume Challenge website and explore the project further, follow these steps:

. **Access the Website**: Visit the deployed website at the following URL:

   [AWS Cloud Resume Challenge Website](https://dcuht95goyv8f.cloudfront.net/)

. **Explore the Code**: Feel free to explore the code in this repository to see how the project is structured and configured. You can find the AWS CloudFormation templates, Lambda function code, website assets, and GitHub Actions workflows in their respective directories.


