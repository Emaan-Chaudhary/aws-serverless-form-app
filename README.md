# Serverless Form Web Application on AWS

A fully serverless web application handling user form submissions, storing data in DynamoDB, and scaling automatically. Demonstrates modern AWS serverless architecture and event-driven design.

---

## Architecture Overview

**Flow:** `API Gateway → Lambda → DynamoDB`  

This design provides a fully serverless, scalable, and pay-per-use application without any server management.

---

## Tech Stack

- **AWS Lambda (Python)**  
- **API Gateway**  
- **DynamoDB**  
- **IAM Roles for secure access**  

---


### 1️⃣ Architecture Diagram
![Architecture Diagram](path/to/architecture-diagram.png)  
*Serverless architecture using API Gateway, Lambda, and DynamoDB.*

### 2️⃣ API Gateway Methods (GET + POST)
![API Gateway Methods](path/to/api-gateway.png)  
*REST API methods with Lambda Proxy Integration enabled.*

### 3️⃣ Lambda Function Handler
![Lambda Code](path/to/lambda-handler.png)  
*Core backend logic handling form submissions.*

### 4️⃣ Frontend Form Page
![Frontend Form](path/to/frontend-form.png)  
*Browser view of the live form connected to API Gateway.*

### 5️⃣ DynamoDB Table Data
![DynamoDB Data](path/to/dynamodb-data.png)  
*Inserted user data with partition key (email) visible.*

*(Optional: Lambda Test / Logs – for GitHub only.)*

---

## Usage

1. Open the frontend URL served via API Gateway.  
2. Fill and submit the form.  
3. Data is stored automatically in DynamoDB.  
4. API Gateway + Lambda handle requests and scale as needed.  

---

## Notes

- Inspired by Harish Shetty; implemented independently.  
- Fully serverless; no servers to manage.  
- Ideal for portfolios, resumes, or interview demos.

---

## LinkedIn / Portfolio Caption

> Serverless web application on AWS demonstrating form submission handling and data storage with DynamoDB. Architecture: API Gateway → Lambda (Python) → DynamoDB. Fully serverless, scalable, and event-driven.  

---

## License

MIT
