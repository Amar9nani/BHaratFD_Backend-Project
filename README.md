## 🌍 Multilingual FAQ System

Welcome to the Multilingual FAQ System – an intelligent and scalable solution for delivering frequently asked questions (FAQs) in multiple languages. This project is built for seamless multilingual support, leveraging a powerful cloud infrastructure for performance and reliability. 🚀

## 🛠️ Tech Stack

Frontend: HTML, CSS, JavaScript (Hosted on AWS Amplify)

Backend: Node.js, Express.js, Redis (AWS ElastiCache), MongoDB (Optional)

Cloud Hosting:

Backend: AWS EC2 🖥️

Static Files: AWS S3 📂

CI/CD: AWS CodePipeline (Optional)

Security: HTTPS enabled via Let’s Encrypt 🔒

## 🚀 Getting Started

## 👅 Clone the Repository

GitHub Repository:

Multilingual FAQ System
```bash
git clone https://github.com/Amar9nani/BHaratFD_Backend-Project.git
cd BHaratFD_Backend-Project
```

## 👖 Backend Deployment

Backend API Base URL:

Backend API

## 🔧 Admin Panel

Admin Panel:

Admin Dashboard

## 🏠 Frontend Deployment (AWS Amplify)

The frontend is powered by AWS Amplify and is accessible at:

## 🌐 Live Frontend URL: https://staging.d2ekmhrt6u8pl0.amplifyapp.com/

Frontend Hosted on AWS Amplify

## 🛠️ API Endpoints

🔗 Base API URL:

https://myfaq.duckdns.org

Fetch FAQs (English default):[GET] https://myfaq.duckdns.org/api/faqs/

Fetch FAQs in Hindi:[GET] https://myfaq.duckdns.org/api/faqs/?lang=hi

Create a New FAQ:[POST] https://myfaq.duckdns.org/api/faqs

Update an Existing FAQ (Replace :id with the actual FAQ ID):[PUT] https://myfaq.duckdns.org/admin/faqs/:id

Delete an FAQ (Replace :id with the actual FAQ ID):[DELETE] https://myfaq.duckdns.org/admin/faqs/:id

☁️ AWS Infrastructure & Services

🌍 AWS EC2 (Backend Hosting)

The backend is deployed on AWS EC2 (t2.micro - Free Tier)

API Base URL: https://myfaq.duckdns.org

⚡ AWS ElastiCache (Redis Caching)

Boosts performance by caching frequently accessed FAQ data.

📂 AWS S3 (Static File Storage)

Hosts static frontend files (HTML, CSS, JavaScript)

S3 URL:https://faq-app-frontend.s3-website.ap-south-1.amazonaws.com/

🔐 AWS Route 53 & ACM (Custom Domain + SSL)

Manages the custom domain https://myfaq.duckdns.org

Ensures secure HTTPS access via AWS Certificate Manager

## 📌 Summary

The Multilingual FAQ System is a scalable and cloud-native solution for managing FAQs across multiple languages. With AWS EC2 (backend), AWS Amplify (frontend), and Redis caching, the system ensures high performance, security, and availability. 🚀

🎯 Features:

🏆 Multilingual Support: Dynamic FAQ translations.

⚡ Optimized Performance: Redis caching for faster responses.

🔒 Secure API: HTTPS-enabled backend.

🏗️ Scalable Architecture: Hosted on AWS with robust infrastructure.

🖥️ Admin Panel: Easy management of FAQs.

Enjoy exploring and contributing! 🚀🔥
