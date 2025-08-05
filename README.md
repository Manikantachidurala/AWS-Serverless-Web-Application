# AWS-Serverless-Web-Application
# 🚀 AWS Serverless Web Application Architecture

This project demonstrates how to deploy a fully serverless web application using AWS services. It includes a static frontend, REST APIs, backend logic, and a NoSQL database — all built using scalable and cost-effective serverless components.

---

 📚 Overview

This application includes:

1. **Amazon S3** – Hosts static web content (HTML, CSS, JavaScript)
2. **Amazon CloudFront** – Delivers content securely over HTTPS
3. **Amazon API Gateway** – Provides REST API endpoints (GET and POST)
4. **AWS Lambda (Python)** – Handles backend logic
5. **Amazon DynamoDB** – Stores and retrieves application data
6. **IAM Roles** – Controls access securely between services

---

<img width="877" height="391" alt="aws" src="https://github.com/user-attachments/assets/879efb54-9259-49ff-bab4-7ecf87a4dfc5" />

---

## 🔧 Setup Instructions

1. Create an **S3 bucket**, upload your frontend files, and enable static website hosting.
2. Create a **CloudFront distribution** with your S3 bucket as the origin.
3. Set up **API Gateway** endpoints for `/get` and `/post`.
4. Write **Lambda functions** in Python to handle API calls.
5. Create a **DynamoDB table** with a suitable key schema.
6. Attach appropriate **IAM roles** to your Lambda functions for DynamoDB access.
7. Connect all components and test the application.

---

## ✅ Project Outcome

- Static web content served securely and quickly using CloudFront + S3
- API calls handled by Lambda via API Gateway
- Data operations (read/write) done in DynamoDB
- Serverless, scalable, and cost-effective architecture

---
## ✅ Project Outcome Images


<img width="1912" height="866" alt="aws2" src="https://github.com/user-attachments/assets/2a5e728d-ad89-4eab-b8a8-69bf6f57058c" />


<img width="946" height="302" alt="aws3" src="https://github.com/user-attachments/assets/cfed85e3-092a-45c1-a981-4c3cb055ecd2" />

<img width="1920" height="1020" alt="aws4" src="https://github.com/user-attachments/assets/727ef80e-ed4f-44d9-bdc3-afff100956a5" />


---<img width="1920" height="1020" alt="aws5" src="https://github.com/user-attachments/assets/0e94615a-0d77-47f8-9c03-d996a33e869e" />
<img width="1920" height="1020" alt="aws6" src="https://github.com/user-attachments/assets/52992aa6-7653-4f92-aee6-e5217755d9c9" />

 
