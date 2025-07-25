# Robotics Portfolio

A modern 3D portfolio showcasing robotics, Arduino, and computer vision projects built with React, Three.js, and Framer Motion.

## 🚀 Features

- **3D Interactive Experience** - Immersive 3D elements and animations
- **Robotics Projects Showcase** - Highlighting Arduino, OpenCV, and IoT projects
- **Responsive Design** - Works perfectly on all devices
- **Animated Illustrations** - Unique animations for each project instead of photos
- **Real-time 3D Models** - Interactive 3D computer and planet models

## 🛠️ Tech Stack

- **Frontend**: React 18, TypeScript
- **3D Graphics**: Three.js, React Three Fiber
- **Animations**: Framer Motion
- **Styling**: Tailwind CSS
- **Build Tool**: Vite

## 🚀 Quick Start

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn

### Installation
```bash
# Clone the repository
git clone https://github.com/yash1gadge/portfolio.git

# Navigate to project directory
cd portfolio

# Install dependencies
npm install

# Start development server
npm run dev
```

### Building for Production
```bash
# Build the project
npm run build

# Preview the build
npm run preview
```

## 🌐 Deployment to GitHub Pages

### Automatic Deployment
```bash
# Deploy to GitHub Pages
npm run deploy
```

### Manual Deployment Steps
1. **Create GitHub Repository**
   - Go to [GitHub](https://github.com)
   - Create a new repository named `portfolio`
   - Make it public

2. **Push Code to GitHub**
   ```bash
   git init
   git add .
   git commit -m "Initial commit - Robotics Portfolio"
   git branch -M main
   git remote add origin https://github.com/yash1gadge/portfolio.git
   git push -u origin main
   ```

3. **Deploy to GitHub Pages**
   ```bash
   npm run deploy
   ```

4. **Enable GitHub Pages**
   - Go to repository Settings → Pages
   - Select "Deploy from a branch"
   - Choose "gh-pages" branch
   - Your site will be available at: `https://yash1gadge.github.io/portfolio`

## 📁 Project Structure

```
portfolio/
├── public/              # Static assets
├── src/
│   ├── components/      # React components
│   ├── constants/       # Configuration and data
│   ├── assets/          # Images and icons
│   └── utils/           # Utility functions
├── dist/               # Build output
└── package.json
```

## 🎯 Customization

### Update Personal Information
- Edit `src/constants/config.ts` for personal details
- Update `src/constants/index.ts` for projects and experience

### Add New Projects
- Add project details in `src/constants/index.ts`
- Create unique animations in `src/components/sections/AnimatedProjectCard.tsx`

## 📞 Contact

For any questions or collaboration opportunities, please reach out through the contact form on the portfolio or email at yashgadge@gmail.com.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
