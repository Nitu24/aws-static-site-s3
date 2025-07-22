# aws-static-site-s3
Host a static website on Amazon S3 using static hosting and public access.

# 🖥️ AWS Static Website Hosting on S3

This project demonstrates how to host a static website using Amazon S3.

## 📌 Overview

Amazon S3 allows you to serve static content (HTML, CSS) without needing a server. In this project, I configured an S3 bucket to host a static website, made the contents publicly accessible, and tested access using the S3 website endpoint.

## 📁 Project Structure
aws-static-site-s3/
├── index.html
├── Image
├── style.css
└── README.md

## 🚀 AWS Services Used

- Amazon S3 (Static Website Hosting)

## 🛠️ Steps Performed

1. Created S3 bucket named aws-static-site-s3
2. Disabled “Block all public access”
3. Uploaded static website files (HTML/CSS)
4. Added bucket policy for public read access
5. Enabled Static Website Hosting in bucket properties
6. Set index.html as default document

## 🧠 Key Learnings

- How to configure static hosting on S3
- How to use bucket policies for public read access
- How to deploy static content on AWS without EC2 or backend servers
