**🛒 Shopshere - Multi-Vendor E-Commerce SaaS Platform**

📌 Table of Contents

🚀 Introduction

🧠 Features

🧰 Tech Stack

⚡ Quick Start

🔐 Advanced Authentication

🤖 Product Recommendation ML

🛠️ Folder Architecture

📸 Screenshots

📢 More
***************************************

**🚀 Introduction**

Shopshere is a real-world, full-stack multi-vendor e-commerce SaaS product, not just another store template. Built with powerful personalization, recommendation engines, real-time analytics, and advanced authentication systems.

Everyday, over 3 billion users interact with e-commerce platforms. Shopshere is designed to match that scale and sophistication.

It comes with three frontends (subdomains):

eshop.com → User site

seller.eshop.com → Seller dashboard

admin.eshop.com → Admin dashboard
**************************************


**🧠 Features**

🔐 Advanced OTP-Based Authentication
🛍️ User account registration and login

🧾 Product listing and filtering by category/subcategory

📈 Real-time analytics

📬 OTP email verification with retry limit

🔄 Resend OTP with lockout system

🤖 Custom Machine Learning product recommendation system

📦 Seller admin panel for managing products/orders

🧑‍💼 Admin panel for global control

📱 Fully responsive on all devices
******************

🧰 Tech Stack

Frontend: Next.js, React Hook Form, TailwindCSS, ShadCN UI

Backend: Node.js, Express, MongoDB

Auth & Cache: Redis, JWT, Rate-limiting

Email Service: Nodemailer, Mailtrap

Machine Learning: TensorFlow.js, custom model

DevOps: Nx Monorepo, Docker, GitHub Actions CI

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
