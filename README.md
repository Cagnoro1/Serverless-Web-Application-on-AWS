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
   ![Setup AWS CloudFront](https://github.com/user-attachments/assets/0ab5bab8-3b25-4e6f-9293-dd736e511b0d)

   Attach the S3 bucket policy to allow CloudFront to access the AWS S3 bucket.
   ![Attach S3 bucket policy to the bucket to allow CloudFront can access the AWS3 bucket](https://github.com/user-attachments/assets/f4e5ff59-f7f6-4e74-9717-4a1f80d234c0)

5. **Setup Route 53**: Map your domain to the CloudFront distribution for easy access.
   ![Add existing  domain to Route53](https://github.com/user-attachments/assets/c3bb9887-9fd1-4b3f-8a5a-af01b7cda0bd)

Create DNS records 

![DNS records](https://github.com/user-attachments/assets/1534fe11-a453-46eb-bfc3-9781091c981d)

6. **Create a DynamoDB Table**: Design and create a table to store application data.
   ![Create DynamoDB](https://github.com/user-attachments/assets/1f4bdb83-7bd6-4cee-a336-5aa51c07ede4)

   
7. **Build a Lambda Function**: Develop Lambda functions for handling CRUD operations and integrate them with the DynamoDB table.
   Create a Lambda function and integrate it with the DynamoDB table.
   ![Create a Lambda function and integrate it with the DynamoDB table](https://github.com/user-attachments/assets/b8e98635-7401-4217-a35f-e83b21def947)
   ![DynamoDB table](https://github.com/user-attachments/assets/f0ea378b-4805-4eab-a25b-882045ffa3ee)

   Application views counter
   ![Setup an S3 Bucket](https://github.com/user-attachments/assets/4d8d3aea-7479-48a9-9b82-77587286fe09)

** Final display Application demo**
<img width="1439" alt="Screenshot 2025-01-12 at 10 56 40 AM" src="https://github.com/user-attachments/assets/58b625cc-81f4-4e1e-992a-24cac702c6ec" />


## Expected Outcome  
By completing this project, you will:  
* Gain hands-on experience with AWS services.  
* Build a fully functional serverless web application.  
* Learn to integrate AWS services (Lambda, DynamoDB, S3, CloudFront, and Route 53) to deliver a complete solution.

## Click here to try the application ⬇️⬇️
https://greeting.christelleincloud.click/  
