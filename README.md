**🛒 Shopshere - Multi-Vendor E-Commerce SaaS Platform**

📌 Table of Contents

🚀 Introduction

🧠 Features

🧰 Tech Stack

🔐 Advanced Authentication

🤖 Product Recommendation ML

📢 More
***************************************

**🚀 Introduction**
Shopshere is a real-world, scalable multi-vendor e-commerce SaaS platform that provides modern, production-ready features to support buyers, sellers, and admins. It’s not just a store — it's a real e-commerce system with subdomains, authentication, analytics, and machine learning-based recommendations.
It comes with three frontends (subdomains):

eshop.com → User site

seller.eshop.com → Seller dashboard

admin.eshop.com → Admin dashboard
**************************************

🔋 Features

🔐 Advanced Authentication (OTP with lockout, resend logic)

👤 Role-based Dashboards (User, Seller, Admin)

🛍 Product Listings & Wishlist

📦 Inventory Management

📝 Order Management

💬 Real-time Notifications & Email

💥 Analytics Tracking

🧠 Custom Product Recommendation Engine

🌐 Responsive Design

📤 Image Upload & Storage

🚀 CI/CD with GitHub Actions
******************

⚙️ Tech Stack

Next.js (App Router)

React Hook Form

TailwindCSS

Express.js (Nx Monorepo)

TypeScript

Redis

Kafka (Event-driven architecture)

PostgreSQL / MongoDB

Sentry for Error Monitoring

JWT for Auth

Custom Machine Learning Model (TensorFlow)

***************************



🔐 Advanced Authentication System

One of the most complex and secure OTP-based systems:

Unique OTP per signup, valid for 5 minutes

3 OTP attempts before locking the email for 30 minutes using Redis

Resend OTP feature

System similar to Facebook/Google auth throttling


**************


🤖 Product Recommendation ML

We have integrated a custom TensorFlow-based machine learning model to power:

Personalized product suggestions

Trending and similar product recommendations

Seller-wise shop recommendations
