# AWS S3 Portfolio Website

A static portfolio website hosted entirely on AWS S3 and delivered globally via CloudFront CDN.

## 🏗️ Architecture
- **Storage:** AWS S3 (Simple Storage Service)
- **CDN:** AWS CLoudFront (400+ global edge locations)
- **Region:** us-east-1 (N. Virginia)
- **Protocol:** HTTPS via CloudFront

## 📋 What I Built
- Created an S3 bucket with public access enabled
- Configured static website hosting on the bucket
- Wrote a custom HTML/CSS portfolio page
- Applied a bucket policy to allow public read access
- Created a CloudFront distribution connected to S3
- Website now served globally via HTTPS

## 🛠️ AWS Services Used
- **S3** — object storage and static website hosting
- **CloudFront** - global content delivery network (CDN)
- **Bucket Policy** — IAM policy for public read access

## 🌐 Live URL
CloudFront: https://d3e40bywgpjgy2.cloudfront.net
S3 Origin: http://seb-aws-website-2026.s3-website-us-east-1.amazonaws.com

## 📚 What I Learned
- How S3 buckets work and how to configure them
- Static website hosting configuration on S3
- Bucket policies and public access settings
- How CloudFront CDN works and how to connect it to S3
- Benefits of CDN: faster global delivery, HTTPS, DDoS protection
## 🚀 Steps to Reproduce
1. Create an S3 bucket with public access enabled
2. Upload index.html
3. Enable static website hosting in bucket Properties
4. Add bucket policy allowing public s3:GetObject
5. Create CloudFront distribution pointing to S3 website endpoint
6. Use recommended cache and origin settings
7. Wait 5-10 minutes for deployment
8. Visit CloudFront domain name with https://

## 📅 Date Completed
May 20, 2026

## 🏅 Part of
[AWS Cloud Engineering Roadmap](https://github.com/sebastianbouharb)
