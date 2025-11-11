# -Website-Hosting-on-AWS-using-S3-CloudFront-
🌐 Deployed a sleek static website using AWS S3 &amp; CloudFront for global delivery. A fast, secure, and serverless cloud hosting setup with HTML + CSS, ensuring lightning-speed performance, HTTPS security, and worldwide access. ☁️✨

🚀 Project Overview

This project demonstrates how to host a static website on Amazon Web Services (AWS) using:

Amazon S3 – to store and serve static web files (HTML, CSS).
Amazon CloudFront – to deliver content globally with low latency.

The result is a fast, secure, and scalable web hosting setup that ensures:

⚡ Lightning-speed performance through global CDN caching.
🔒 HTTPS security using AWS Certificate Manager.
🌍 High availability and worldwide access with serverless architecture.
🧠 Key Learnings

Deploying and configuring a static website using AWS S3.
Integrating CloudFront for global content delivery and caching.
Setting up HTTPS using AWS Certificate Manager (ACM).

Understanding serverless hosting and cost optimization in the cloud.

🛠️ Tech Stack
Frontend: HTML, CSS
Cloud Services: AWS S3, AWS CloudFront, AWS Certificate Manager
⚙️ Setup Instructions

Follow these steps to deploy your own static website using AWS:

Create an S3 Bucket
Go to the AWS Management Console → S3 → Create Bucket.
Enable “Static website hosting.”

Upload your website files (HTML, CSS, JS).

Set Bucket Policy & Permissions
Make your objects publicly readable.
Configure correct bucket policy to allow CloudFront access.
Create a CloudFront Distribution
Set your S3 bucket as the origin.
Enable HTTPS (choose “Redirect HTTP to HTTPS”).
Attach an SSL certificate using AWS Certificate Manager (ACM).
Update DNS (Optional)
Use Amazon Route 53 or another DNS provider.
Point your custom domain to the CloudFront distribution URL.

Test & Verify

Open your CloudFront URL or domain name.

Ensure your website loads securely with HTTPS.

📈 Outcome

A modern static website hosted entirely on AWS with optimized performance, security, and reliability — demonstrating practical skills in cloud computing, web deployment, and AWS architecture.
