# AWS S3 Portfolio Website

A static portfolio website hosted entirely on AWS S3 — no servers required.

## 🏗️ Architecture
- **Storage:** AWS S3 (Simple Storage Service)
- **Hosting:** S3 Static Website Hosting
- **Region:** us-east-1 (N. Virginia)
- **Access:** Public via S3 website endpoint

## 📋 What I Built
- Created an S3 bucket with public access enabled
- Configured static website hosting on the bucket
- Wrote a custom HTML/CSS portfolio page
- Applied a bucket policy to allow public read access
- Deployed a live website accessible from any browser

## 🛠️ AWS Services Used
- **S3** — object storage and static website hosting
- **Bucket Policy** — IAM policy for public read access

## 🌐 Live URL
http://seb-aws-website-2026.s3-website-us-east-1.amazonaws.com

## 📚 What I Learned
- How S3 buckets work and how to configure them
- Static website hosting configuration on S3
- Bucket policies and public access settings
- Deploying a website without any servers

## 🚀 Steps to Reproduce
1. Create an S3 bucket with public access enabled
2. Upload index.html
3. Enable static website hosting in bucket Properties
4. Set index document to index.html
5. Add bucket policy allowing public s3:GetObject
6. Visit the S3 website endpoint URL

## 📅 Date Completed
May 19, 2026

## 🏅 Part of
[AWS Cloud Engineering Roadmap](https://github.com/sebastianbouharb)
