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

📥 Clone the Repository

git clone https://github.com/Amar9nani/BHaratFD_Backend-Project.git
cd BHaratFD_Backend-Project

## 📦 Install Backend Dependencies

Move into the backend directory and install necessary packages:
''' Bash
cd backend
npm install
'''

## 🔧 Configure Environment Variables

Ensure you set up the required environment variables for seamless operation:

export MONGODB_URI="your-mongodb-uri"
export REDIS_URL="redis://your-elasticache-endpoint:6379"
export GOOGLE_CLOUD_PROJECT_ID="your-google-cloud-project-id"
export GOOGLE_CLOUD_CREDENTIALS_PATH="path-to-your-google-cloud-credentials.json"

(Tip: To persist these variables, add them to .bashrc or .bash_profile)

## 🚦 Start the Backend Server (PM2 Recommended)

To run the backend efficiently in the background, use PM2:

pm install -g pm2
pm2 start src/app.js --name "faq-backend"
pm2 startup
pm2 save

## 🎨 Frontend Deployment (AWS Amplify)

The frontend is powered by AWS Amplify and is accessible at:

## 🌐 Live Frontend URL

## 🏠 Key Pages

Home Page: Displays FAQs in the default language, with an option to switch languages.

URL: /

Admin Panel: Manage FAQs efficiently (Admin access required).

URL: /admin

## 🔍 Testing the Application

# ✅ Frontend Testing

To explore the multilingual FAQ system, visit:

🔗 Frontend URL

🔧 Backend API Testing

The backend is securely hosted on AWS EC2 with HTTPS enabled via DuckDNS:

🔗 Base API URL: https://myfaq.duckdns.org

## 📌 API Endpoints:

Fetch FAQs (English default):

curl https://myfaq.duckdns.org/api/faqs/

Fetch FAQs in Hindi:

curl https://myfaq.duckdns.org/api/faqs/?lang=hi

Create a New FAQ:

curl -X POST https://myfaq.duckdns.org/api/faqs \  
     -H "Content-Type: application/json" \  
     -d '{"question": "Sample Question", "answer": "Sample Answer"}'

Update an Existing FAQ (Replace :id with actual ID):

curl -X PUT https://myfaq.duckdns.org/admin/faqs/:id \  
     -H "Content-Type: application/json" \  
     -d '{"question": "Updated Question", "answer": "Updated Answer"}'

Delete an FAQ (Replace :id with actual ID):

curl -X DELETE https://myfaq.duckdns.org/admin/faqs/:id

☁️ AWS Infrastructure & Services

🌍 AWS EC2 (Backend Hosting)

The backend is deployed on AWS EC2 (t2.micro - Free Tier)

API Base URL: https://myfaq.duckdns.org

⚡ AWS ElastiCache (Redis Caching)

Boosts performance by caching frequently accessed FAQ data.

📂 AWS S3 (Static File Storage)

Hosts static frontend files (HTML, CSS, JavaScript)

S3 URL: [https://your-bucket-name.s3-website-region.amazonaws.com](https://faq-app-frontend.s3-website.ap-south-1.amazonaws.com/)

🔐 AWS Route 53 & ACM (Custom Domain + SSL)

Manages the custom domain https://myfaq.duckdns.org

Ensures secure HTTPS access via AWS Certificate Manager

## 📌 Summary

The Multilingual FAQ System is a scalable and cloud-native solution for managing FAQs across multiple languages. With AWS EC2 (backend), AWS Amplify (frontend), and Redis caching, the system ensures high performance, security, and availability. 🚀

## 🎯 Features:

🏆 Multilingual Support: Dynamic FAQ translations.

⚡ Optimized Performance: Redis caching for faster responses.

🔒 Secure API: HTTPS-enabled backend.

🏗️ Scalable Architecture: Hosted on AWS with robust infrastructure.

🖥️ Admin Panel: Easy management of FAQs.

Enjoy exploring and contributing! 🚀🔥

