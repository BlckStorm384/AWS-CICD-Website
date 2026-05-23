# ☁️ AWS CI/CD Static Website Pipeline

A fully automated cloud deployment pipeline that hosts a personal portfolio website using AWS services.

## 🌐 Live URL (when active)
https://d1icdf6dh9n0y6.cloudfront.net

## 📸 Demo

### ✅ Pipeline Success
<img width="1121" height="540" alt="pipeline showing a three green stages" src="https://github.com/user-attachments/assets/096ced71-ee28-4e97-81f1-5f0b192ff4c9" />

### 🌐 Live Website
<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/575a0d8f-fc2a-4eb3-8ee1-e68a396929f7" />

<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/4267f4cd-c940-41b1-b197-69c7755b76ef" />

## ⚙️ AWS Services Used
| Service | Purpose |
|---|---|
| S3 | Static website hosting |
| CloudFront | CDN and HTTPS delivery |
| CodePipeline | Automated CI/CD pipeline |
| CodeBuild | Build and deploy automation |
| IAM | Roles and permissions |
| CloudWatch | Build logs and monitoring |

## 🚀 How It Works
1. Code is pushed to GitHub main branch
2. CodePipeline automatically detects the change
3. CodeBuild runs the buildspec.yml and syncs files to S3
4. CloudFront serves the updated website globally via HTTPS
5. Changes are live within minutes — fully automated!

## 🏗️ Architecture
GitHub Push → CodePipeline → CodeBuild → S3 → CloudFront → Live Website

## 🛠️ Tech Stack
- HTML, CSS
- AWS S3, CloudFront, CodePipeline, CodeBuild, IAM, CloudWatch
- GitHub for source control

## 🔴 Note
AWS services are currently paused to manage costs.
The pipeline was fully functional as shown in the screenshots above.
