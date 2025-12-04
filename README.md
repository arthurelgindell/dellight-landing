# Dellight AI - Marketing Website

Enterprise AI infrastructure and business solutions marketing website.

## 🚀 Live Site
- Production: Via Cloudflare Pages (auto-deploy from `main` branch)
- Local Development: `python3 -m http.server 8888`

## 📄 Site Structure

### Main Pages
- **index.html** - Landing page with all products/services
- **gladiator.html** - GLADIATOR cyber defense platform detail page
- **aya-platform.html** - AYA multi-agent orchestration platform
- **solutions.html** - Business solutions (LinkedIn, YouTube, JITFM, Code Audit)

### Products & Services

**Enterprise Platforms:**
- GLADIATOR - Autonomous cyber defense (NVIDIA DGX Spark)
- AYA Platform - Multi-agent AI orchestration
- Code Audit System - Automated security analysis

**Business Solutions:**
- LinkedIn Optimization - Professional profile & content strategy
- YouTube Optimization - Channel growth & analytics
- JITFM Platform - Just-in-Time Fashion Manufacturing

## 🎨 Design System

**Color Palette:**
- Primary: Blue (#3B82F6, #60A5FA)
- Secondary: Green (#10B981, #34D399)
- Accent: Purple, Pink (minimal)
- NVIDIA: Official Green (#76B900)

**Interactive Features:**
- Custom cursor with follower effect
- 3D card tilt on hover
- Mouse-following parallax orbs
- Scroll-triggered animations
- Glassmorphism effects

## 📦 Deployment

### Cloudflare Pages Setup

1. **Connect Repository:**
   ```
   GitHub Repository: arthurelgindell/dellight-landing
   Branch: main
   ```

2. **Build Settings:**
   ```
   Build command: (none - static site)
   Build output directory: /
   Root directory: /
   ```

3. **Custom Domain (if applicable):**
   ```
   Add CNAME record pointing to Cloudflare Pages URL
   ```

### Manual Deployment
```bash
# Push to main branch triggers automatic deployment
git add .
git commit -m "Deploy updates"
git push origin main
```

## 🛠️ Development

### Local Server
```bash
python3 -m http.server 8888
# Visit: http://localhost:8888
```

### File Structure
```
dellight-landing/
├── index.html              # Landing page
├── gladiator.html          # GLADIATOR detail page
├── aya-platform.html       # AYA Platform detail page
├── solutions.html          # Business solutions page
├── gladiator-hero.png      # GLADIATOR hero image
├── index-backup.html       # Backup (original version)
├── index-n8n-v1.html       # Backup (n8n-inspired v1)
└── README.md              # This file
```

## 🔧 Technologies

- **Static HTML/CSS/JS** - No build process required
- **Vanilla JavaScript** - No framework dependencies
- **GPU-Accelerated Animations** - CSS transforms for 60fps
- **Responsive Design** - Mobile-first approach
- **SEO Optimized** - Meta tags and semantic HTML

## 📝 Content Guidelines

### Adding New Pages
1. Copy existing page structure for consistency
2. Maintain blue/green color scheme
3. Include custom cursor and interactive elements
4. Add navigation links to all pages
5. Test responsive design

### Updating Products
Edit the product cards in `index.html` starting around line 978.

## 🌐 Browser Support

- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📞 Contact

Email: hello@dellight.ai

---

© 2025 Dellight AI. All rights reserved.
