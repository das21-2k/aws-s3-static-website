# aws-s3-static-website

Static portfolio website hosted on AWS S3, demonstrating foundational cloud skills

**Live Site:** [https://darrell-portfolio-2026.s3.us-east-2.amazonaws.com/aws-website/index.html] (https://darrell-portfolio-2026.s3.us-east-2.amazonaws.com/aws-website/index.html)

## Project Overview

This project involved deploying a static HTML website to Amazon S3 using the static website hosting feature. It demonstrates core cloud concepts including object storage, bucket policies, and a public access configuration. 

## AWS Services Used

- **Amazon S3** — Object storage and static website hosting
- **IAM** — Created a dedicated user with least-privilege permissions (no root account usage)
- **Bucket Policies** — Configured public read access for website content

## What I Learned

- How S3 static website hosting works
- The difference between object URLs and website endpoints
- How Block Public Access and bucket policies interact
- Why using IAM users instead of root is a security best practice

## Screenshots
<img width="1550" height="888" alt="Screenshot 2026-09-29 143727" src="https://github.com/user-attachments/assets/5d56e8fe-52ee-4f39-8d81-576df21bc032" />


## Next Steps

- Add a custom domain using Route 53
- Put CloudFront in front of the bucket for HTTPS and caching
- Expand the site with CSS styling
