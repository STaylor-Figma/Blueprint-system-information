# Blueprint Design System - Interactive Explainer

An interactive presentation explaining the Blueprint Design System's "Building Blocks, Not Buildings" philosophy.

## 🚀 Quick Deploy to GitHub Pages

### Option 1: Direct Upload (Easiest)

1. Create a new GitHub repository
2. Upload the `index.html` file to the repository
3. Go to **Settings** → **Pages**
4. Under "Source", select **Deploy from a branch**
5. Select **main** branch and **/ (root)** folder
6. Click **Save**
7. Wait ~1 minute, then visit `https://yourusername.github.io/repo-name`

### Option 2: Using Git

```bash
# Clone your new empty repo
git clone https://github.com/yourusername/blueprint-explainer.git
cd blueprint-explainer

# Copy the index.html file into the repo
# (or just add it manually)

# Push to GitHub
git add index.html
git commit -m "Add Blueprint explainer"
git push origin main

# Then enable GitHub Pages in repo settings
```

## 🎮 Features

- **9 interactive slides** covering the design system philosophy
- **Keyboard navigation** - Use ← → arrow keys or spacebar
- **Auto-play mode** - 5-second intervals for hands-off presentations
- **Interactive LEGO demo** - Click the arrow to see components assemble
- **Responsive design** - Works on desktop and mobile
- **No build step required** - Pure HTML with CDN dependencies

## 🎨 Customization

The presentation uses these Blueprint brand colors:
- Primary: `#005A78` (teal/blue)
- Accent: `#ED7800` (orange)
- Success: `#2E7D32` (green)
- Error: `#C62828` (red)

To customize, edit the CSS variables or Tailwind classes in `index.html`.

## 📦 Dependencies (loaded via CDN)

- React 18
- ReactDOM 18
- Tailwind CSS
- Babel (for JSX transformation)

No npm install required!

## 🔗 Related Materials

This interactive explainer is part of a documentation package that includes:
- PowerPoint presentation (11 slides)
- Video script (3-minute narrated version)
- Word documents (full guide + one-pager)

---

**Created by:** Blueprint Design System Team  
**Company:** ConstructConnect
