# ☁️ Serverless Visitor Counter

A serverless web application that tracks website visitors in real time using AWS cloud services.

## 📖 Project Overview

The **Serverless Visitor Counter** is a cloud-based web application that counts the number of visitors to a website in real time. It is built using a serverless architecture on AWS, eliminating the need to manage servers.

When a user visits the website, a request is sent to **Amazon API Gateway**, which triggers an **AWS Lambda** function. The Lambda function updates the visitor count stored in **Amazon DynamoDB** and returns the latest count to the website hosted on **Amazon S3**.

This project helped me gain hands-on experience with AWS serverless services, REST APIs, cloud databases, and deploying static websites.

## ✨ Features

- Displays the total number of website visitors in real time.
- Uses a serverless architecture with no server management required.
- Automatically updates the visitor count on every page visit.
- Stores visitor data in Amazon DynamoDB.
- Integrates the frontend with backend services using Amazon API Gateway.
- Hosts the static website on Amazon S3.
- Lightweight, scalable, and cost-effective cloud solution.

- ## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript
- AWS Lambda
- Amazon API Gateway
- Amazon DynamoDB
- Amazon S3

  ## 🏗️ Architecture

  The following diagram illustrates the serverless architecture used in this      project.

  ![(2) Architecture]((2)%20architecture.png)

  ## 📸 Project Screenshots

### 🖥️ Website Interface

The homepage displays the current visitor count and interacts with the AWS backend to fetch the latest value.

![Website]((1)%20website.png)

---

### ⚡ AWS Lambda Overview

This screenshot shows the Lambda function configuration and its API Gateway trigger.

![Lambda Overview]((3)%20Lambda-overview.png)

---

### 💻 AWS Lambda Code

The Lambda function processes API requests, updates the visitor count in DynamoDB, and returns the latest count.

![Lambda Code]((4)%20Lambda-code.png)

---

### 🌐 Amazon API Gateway

API Gateway exposes the REST API endpoint that connects the frontend with the Lambda function.

![API Gateway]((5)%20API.png)

---

### 🗄️ Amazon DynamoDB - Table Overview

This screenshot shows the DynamoDB table used to store the visitor count.

![DynamoDB Table]((6)%20dynamoDB1.png)

---

### 📊 Amazon DynamoDB - Stored Data

This screenshot shows the visitor count record stored in DynamoDB.

![DynamoDB Data]((7)%20dynamoDB2.png)

---

### 🪣 Amazon S3 Bucket

The static website is hosted using an Amazon S3 bucket configured for website hosting.

![Amazon S3]((8)%20S3.png)

## 🚀 Future Improvements

- Add CloudFront for faster content delivery.
- Configure a custom domain using Route 53.
- Implement CI/CD using GitHub Actions.
- Improve the website UI and responsiveness.
- Add monitoring using Amazon CloudWatch.

## 👨‍💻 Author

**Jaswan Kumar**

Second-Year B.Tech Information Technology Student

Interested in Cloud Computing, AWS, and Software Development.

## ⭐ Project Status

✅ Completed and Successfully Deployed on AWS
