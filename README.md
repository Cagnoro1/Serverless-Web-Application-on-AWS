# Serverless Web Application on AWS  

## Project Description  
This project demonstrates how to build a **serverless web application** using **AWS Lambda**, **DynamoDB**, **S3**, **CloudFront**, and **Route 53**. The application enables users to perform CRUD operations (Create, Read, Update, Delete) on items stored in a DynamoDB table. The web application is fully hosted on AWS, utilizing serverless architecture for scalability and efficiency.  

## Features  
* Perform CRUD operations on a DynamoDB table.  
* Host and serve static files (HTML, CSS, JavaScript) via an S3 bucket.  
* Leverage CloudFront for low-latency content delivery.  
* Integrate Route 53 for domain management and application routing.  

## Project Architecture  





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
   Create S3 Bucket 
![Create Bucket  (1)](https://github.com/user-attachments/assets/2913fb2c-22a5-4366-bbe7-0ad872967d80)

Upload HTML, CSS, and JavaScript  files into the S3 bucket.  
![Create Bucket  (1)](https://github.com/user-attachments/assets/c24fd788-366a-4b3c-92d3-384e94d1e7ae)


3. **Configure CloudFront**: Link CloudFront with the S3 bucket for optimized content delivery.
   
4. **Setup Route 53**: Map your domain to the CloudFront distribution for easy access.

5. **Create a DynamoDB Table**: Design and create a table to store application data.
   
6. **Build a Lambda Function**: Develop Lambda functions for handling CRUD operations and integrate them with the DynamoDB table.
   

## Expected Outcome  
By completing this project, you will:  
* Gain hands-on experience with AWS services.  
* Build a fully functional serverless web application.  
* Learn to integrate AWS services (Lambda, DynamoDB, S3, CloudFront, and Route 53) to deliver a complete solution.

## Click here to try the application ⬇️⬇️
https://greeting.christelleincloud.click/  
