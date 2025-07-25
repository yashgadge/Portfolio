# 🚀 Deployment Guide

## Quick Deploy to GitHub Pages

### 1. Create GitHub Repository
1. Go to [GitHub.com](https://github.com)
2. Click "New repository"
3. Name it `portfolio` (must be exactly this name)
4. Make it **Public**
5. Don't initialize with README (we already have one)

### 2. Initialize Git and Push Code
```bash
# In your project directory
git init
git add .
git commit -m "Initial commit - Robotics Portfolio"
git branch -M main
git remote add origin https://github.com/yash1gadge/portfolio.git
git push -u origin main
```

### 3. Automatic Deployment
The GitHub Actions workflow will automatically deploy your site when you push to main branch.

### 4. Manual Deployment (Alternative)
```bash
# Build and deploy manually
npm run deploy
```

## 📍 Your Site Will Be Available At:
**https://yash1gadge.github.io/portfolio**

## 🔧 Troubleshooting

### If deployment fails:
1. Check that your repository is named exactly `portfolio`
2. Ensure the repository is public
3. Verify GitHub Pages is enabled in repository settings
4. Check Actions tab for any build errors

### To update your site:
```bash
# Make changes
git add .
git commit -m "Update portfolio"
git push origin main
```

The site will automatically update within 1-2 minutes.

## 📋 Pre-deployment Checklist
- [ ] Repository created as `portfolio`
- [ ] Repository is public
- [ ] All changes committed
- [ ] Build successful (`npm run build`)
- [ ] GitHub Pages enabled in repository settings
