# Chatbot
Customer support chatbot for sorting out the regular FAQs

# 🤖 AWS Chatbot with Amazon Lex

An intelligent chatbot built using **Amazon Lex**, **AWS Lambda**, and **DynamoDB**.  
This project demonstrates **serverless architecture, natural language processing, and secure authentication** with AWS Cognito—all within the AWS Free Tier.

---

## 📐 Architecture Diagram



**Flow:**
1. User interacts with chatbot (Web UI hosted on S3).
2. Amazon Lex processes the query and identifies intent.
3. AWS Lambda executes backend logic.
4. DynamoDB stores FAQs, session data, or order records.
5. Cognito manages authentication.
6. CloudWatch monitors logs and metrics.

---

## 🚀 Features
- Natural language understanding with **Amazon Lex**
- Serverless backend logic using **AWS Lambda**
- Persistent data storage with **DynamoDB**
- Secure authentication via **Amazon Cognito**
- Monitoring and logging with **CloudWatch**
- Web-based chatbot UI hosted on **S3**

---

## 🛠️ Tech Stack
- **Amazon Lex** – Chatbot engine
- **AWS Lambda (Python/Node.js)** – Business logic
- **Amazon DynamoDB** – NoSQL database
- **Amazon Cognito** – Authentication
- **Amazon S3** – Static web hosting
- **Amazon CloudWatch** – Monitoring

---

## ⚙️ Setup Instructions

### 1. Clone Repository
```bash
git clone https://github.com/yourusername/aws-lex-chatbot.git
cd aws-lex-chatbot

