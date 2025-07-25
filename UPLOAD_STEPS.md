# 🚀 Upload Steps for GitHub Web Interface

## Method 1: GitHub Web Upload (Recommended)

1. **Go to your repository**: https://github.com/yashgadge/Portfolio

2. **Upload files**:
   - Click "Upload files" button
   - Drag and drop ALL files from `h:/reactjs18-3d-portfolio` folder
   - Make sure to include:
     - All `.js`, `.ts`, `.tsx` files
     - `package.json`
     - `vite.config.js`
     - `.github/workflows/` folder
     - `README.md`
     - `public/` folder
     - `src/` folder
     - All other files

3. **Commit the files**:
   - Add commit message: "Initial upload - Robotics Portfolio with updated timeline and animations"
   - Click "Commit changes"

## Method 2: GitHub Desktop (Alternative)

1. **Download GitHub Desktop**: https://desktop.github.com/
2. **Clone your repository** to local folder
3. **Copy all files** from `h:/reactjs18-3d-portfolio` to the cloned folder
4. **Commit and push** using GitHub Desktop

## Method 3: Personal Access Token (Advanced)

1. **Create Personal Access Token**:
   - Go to GitHub → Settings → Developer settings → Personal access tokens
   - Generate new token with `repo` permissions
   - Copy the token

2. **Use HTTPS with token**:
   ```bash
   git remote set-url origin https://YOUR_TOKEN@github.com/yashgadge/Portfolio.git
   git push -u origin main
   ```

## 🎯 After Upload
- Your site will be live at: https://yashgadge.github.io/Portfolio
- GitHub Actions will automatically build and deploy
- Check the Actions tab in your repository for build status
