# GitHub Pages Deployment & DNS Guide

## 1. DNS Apex (@) Configuration
Create four **A records** pointing your root domain (`kamalbramwell.com`) to GitHub's IP addresses:
- `185.199.108.153`
- `185.199.109.153`
- `185.199.110.153`
- `185.199.111.153`

## 2. Subdomain (www) Configuration
Create a **CNAME record** for the `www` subdomain to route traffic correctly:
- **Name**: `www`
- **Target**: `kdbramwell.github.io`

## 3. GitHub Repository Settings
1. Navigate to your repository on GitHub.
2. Go to **Settings** → **Pages**.
3. Under **Build and deployment**, set the **Source** to **Deploy from a branch**.
4. Select the **Branch** as `main` and the **Folder** as `/ (root)`.
5. Under **Custom domain**, enter `kamalbramwell.com` and save.
6. Once the DNS check completes successfully, check the box to **Enforce HTTPS**.
