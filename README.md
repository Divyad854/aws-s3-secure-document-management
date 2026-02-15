# Enterprise Secure Document Management System (AWS S3)

## 📌 Overview
This project demonstrates a secure, enterprise-style document management system using Amazon S3.
The solution focuses on security, access control, and cost awareness rather than UI.

## 🏗 Architecture
User → AWS CloudShell → IAM (Least Privilege) → Private Amazon S3 Bucket  
Secure sharing via time-limited pre-signed URLs.

## 🔐 Security Features
- Private S3 bucket with public access blocked
- IAM least-privilege policy for object access
- No long-term access keys (used AWS CloudShell)
- Server-side encryption (SSE-S3)
- Object versioning enabled

## 🔧 Implementation Steps
1. Created a private S3 bucket with encryption and versioning
2. Defined a custom IAM policy with least-privilege permissions
3. Used AWS CloudShell for secure access without access keys
4. Uploaded documents using AWS CLI
5. Generated pre-signed URLs for temporary secure access

## 💰 Cost
- Built entirely under AWS Free Tier
- Zero-cost monitoring enabled
- No paid AWS services used

## 🎯 Use Case
Secure storage and controlled sharing of confidential documents such as resumes, HR files, and reports.

## 📚 Key Learnings
- AWS S3 security best practices
- IAM least privilege design
- Secure file sharing using pre-signed URLs
- Cost-aware cloud architecture
