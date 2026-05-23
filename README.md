# AWS CI/CD Static Website

🌐 **Live Website:** https://d1icdf6dh9n0y6.cloudfront.net

## Tech Stack
- AWS S3 — Static website hosting
- AWS CloudFront — CDN & HTTPS
- AWS CodePipeline — Automated deployment
- AWS CodeBuild — Build & deploy automation
- GitHub — Source control

## How It Works
Every push to the `main` branch automatically triggers
CodePipeline which builds and deploys to S3 via CloudFront.
