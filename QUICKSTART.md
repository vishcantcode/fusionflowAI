# FusionFlow AI - Quick Start Guide

## 🚀 Get Started in 5 Minutes

### Step 1: Install Dependencies

```bash
cd fusionflow-ai/frontend
npm install
```

This will install all required packages:
- React 18.2.0
- Vite (build tool)
- TailwindCSS (styling)
- Framer Motion (animations)
- React Flow (architecture graphs)
- Monaco Editor (code display)
- React Router (navigation)
- Lucide React (icons)

### Step 2: Start Development Server

```bash
npm run dev
```

The application will start at: **http://localhost:5173**

### Step 3: Experience the Demo

1. **Landing Page** - Click "Start Integration"
2. **Upload Page** - Drag & drop two ZIP files (or click to browse)
   - Frontend: React application
   - Backend: FastAPI service
3. **Dashboard** - Watch AI analyze repositories (auto-progresses)
4. **Analysis** - View architecture graph and compatibility
5. **Conflicts** - See detected integration issues
6. **Fixes** - Review AI-generated adapter code
7. **Output** - Download integration package

**Total Time:** 2-3 minutes for complete demo

---

## 📁 Project Structure

```
fusionflow-ai/
└── frontend/
    ├── src/
    │   ├── components/
    │   │   ├── common/
    │   │   │   ├── Button.jsx
    │   │   │   └── GlassCard.jsx
    │   │   └── animations/
    │   │       └── ParticleBackground.jsx
    │   ├── pages/
    │   │   ├── LandingPage.jsx
    │   │   ├── UploadPage.jsx
    │   │   ├── Dashboard.jsx
    │   │   ├── AnalysisPage.jsx
    │   │   ├── ConflictPage.jsx
    │   │   ├── FixesPage.jsx
    │   │   └── OutputPage.jsx
    │   ├── App.jsx
    │   ├── main.jsx
    │   └── index.css
    ├── package.json
    ├── tailwind.config.js
    └── vite.config.js
```

---

## 🎨 Key Features

### Visual Design
- **Glassmorphism UI** - Modern, translucent cards
- **Neon Colors** - Cyan, Purple, Green accents
- **Particle Background** - 150 animated particles
- **Smooth Animations** - Framer Motion throughout

### User Experience
- **Drag & Drop** - Easy file upload
- **Real-time Progress** - Live AI simulation
- **Interactive Graphs** - React Flow architecture
- **Code Display** - Monaco Editor with syntax highlighting

### AI Simulation
- **Repository Scanning** - 5-8 seconds
- **Conflict Detection** - 4-6 seconds
- **Fix Generation** - 6-10 seconds
- **Live Logs** - Streaming updates

---

## 🎯 Demo Tips

### For Best Results:

1. **Use Chrome/Edge** - Best performance and animations
2. **Full Screen** - Maximize visual impact
3. **Dark Room** - Neon colors pop more
4. **Smooth Narration** - Let animations complete
5. **Emphasize AI** - Highlight autonomous intelligence

### Demo Script:

**Opening:**
"Integration is painful. Different teams, different code, nothing works together."

**Solution:**
"FusionFlow AI solves this. Upload repos, AI analyzes, detects conflicts, generates fixes."

**Demo:**
[Show workflow - 2 minutes]

**Impact:**
"From weeks to minutes. This is the future."

---

## 🔧 Customization

### Change Colors

Edit `tailwind.config.js`:

```javascript
colors: {
  'neon-cyan': '#00d4ff',    // Change to your color
  'neon-purple': '#b400ff',  // Change to your color
  'neon-green': '#00ff88',   // Change to your color
}
```

### Adjust Animation Speed

Edit `src/pages/Dashboard.jsx`:

```javascript
duration: 3000,  // Change milliseconds
```

### Modify Particle Count

Edit `src/components/animations/ParticleBackground.jsx`:

```javascript
const particleCount = 150;  // Increase/decrease
```

---

## 🐛 Troubleshooting

### Port Already in Use

```bash
# Kill process on port 5173
lsof -ti:5173 | xargs kill -9

# Or use different port
npm run dev -- --port 3000
```

### Dependencies Not Installing

```bash
# Clear cache and reinstall
rm -rf node_modules package-lock.json
npm install
```

### Build Errors

```bash
# Check Node version (need 18+)
node --version

# Update if needed
nvm install 18
nvm use 18
```

---

## 📦 Production Build

```bash
# Create optimized build
npm run build

# Preview production build
npm run preview
```

Build output will be in `dist/` folder.

---

## 🎬 Recording Demo

### Recommended Tools:
- **Loom** - Easy screen recording
- **OBS Studio** - Professional recording
- **QuickTime** - Mac built-in

### Recording Tips:
1. Close unnecessary tabs
2. Hide bookmarks bar
3. Use full screen mode
4. Record at 1080p minimum
5. Add background music (optional)

---

## 🚢 Deployment

### Vercel (Recommended)

```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
cd frontend
vercel
```

### Netlify

```bash
# Build
npm run build

# Drag dist/ folder to Netlify
```

### GitHub Pages

```bash
# Add to vite.config.js
base: '/fusionflow-ai/'

# Build and deploy
npm run build
# Push dist/ to gh-pages branch
```

---

## 📊 Performance

### Lighthouse Scores (Target)
- Performance: 90+
- Accessibility: 95+
- Best Practices: 95+
- SEO: 90+

### Optimization Tips:
- Lazy load pages
- Optimize images
- Minimize bundle size
- Use code splitting

---

## 🎯 Hackathon Checklist

- [ ] Project runs without errors
- [ ] All pages load correctly
- [ ] Animations are smooth
- [ ] Demo flow is clear
- [ ] README is complete
- [ ] Code is clean
- [ ] Git history is good
- [ ] Presentation ready

---

## 💡 Next Steps

After the hackathon:

1. **Add Backend** - Implement FastAPI service
2. **Real AI** - Integrate OpenAI/Anthropic
3. **File Parsing** - Actually parse repositories
4. **Code Generation** - Real adapter creation
5. **User Auth** - Add authentication
6. **Database** - Store project history

---

## 🤝 Support

For issues or questions:
1. Check this guide
2. Review README.md
3. Check code comments
4. Open GitHub issue

---

## 🏆 Success Metrics

Your demo is ready when:
- ✅ Loads in under 3 seconds
- ✅ Animations are smooth (60fps)
- ✅ No console errors
- ✅ Works on Chrome/Firefox/Safari
- ✅ Mobile responsive
- ✅ Looks professional

---

**You're ready to win! 🚀**

Good luck with your hackathon presentation!