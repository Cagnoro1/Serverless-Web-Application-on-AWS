# Serverless Web Application on AWS  

## Project Description  
This project demonstrates how to build a **serverless web application** using **AWS Lambda**, **DynamoDB**, **S3**, **CloudFront**, and **Route 53**. The application enables users to perform CRUD operations (Create, Read, Update, Delete) on items stored in a DynamoDB table. The web application is fully hosted on AWS, utilizing serverless architecture for scalability and efficiency.  

## Features  
* Perform CRUD operations on a DynamoDB table.  
* Host and serve static files (HTML, CSS, JavaScript) via an S3 bucket.  
* Leverage CloudFront for low-latency content delivery.  
* Integrate Route 53 for domain management and application routing.  

## Project Architecture  

![P1_ Serverless Web Application on AWS](https://github.com/user-attachments/assets/c8258431-983c-4022-ad3b-7a2e1092ffb4)





### AWS Cloud Services Used  
* **S3 Bucket**: To store and host static files.  
* **CloudFront**: For efficient and low-latency content delivery.  
* **Route 53**: For domain name system (DNS) management.  
* **DynamoDB**: To store and manage application data.  
* **Lambda**: To handle backend logic and CRUD operations.  

### Programming Languages Used  
* **HTML**  
* **CSS**  
* **JavaScript**  

## Steps to Build the Project  
1. **Setup an S3 Bucket**: Upload and configure static files (HTML, CSS, JavaScript).  
2. **Configure CloudFront**: Link CloudFront with the S3 bucket for optimized content delivery.  
3. **Setup Route 53**: Map your domain to the CloudFront distribution for easy access.  
4. **Create a DynamoDB Table**: Design and create a table to store application data.  
5. **Build a Lambda Function**: Develop Lambda functions for handling CRUD operations and integrate them with the DynamoDB table.  

## Expected Outcome  
By completing this project, you will:  
* Gain hands-on experience with AWS services.  
* Build a fully functional serverless web application.  
* Learn to integrate AWS services (Lambda, DynamoDB, S3, CloudFront, and Route 53) to deliver a complete solution.  
