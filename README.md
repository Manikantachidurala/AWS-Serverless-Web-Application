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



---
 
