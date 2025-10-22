# AWS Cloud Portfolio Website — Gbemileke Oyeniran

Personal portfolio hosted on **Amazon S3** and distributed globally via **Amazon CloudFront**.  
Demonstrates static site hosting, CDN configuration, and cost-efficient AWS architecture.

## Architecture
User → CloudFront (HTTPS) → S3 Static Website  
(Optional) Route 53 → Custom Domain

## Services Used
- Amazon S3 (Static Website Hosting)
- Amazon CloudFront (Content Delivery Network)
- AWS IAM (Security & Access)
- Amazon Route 53 (Optional Domain)

## Local Preview
```bash
python -m http.server 8000
