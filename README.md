# Akshay Shirude - Developer Portfolio
Portfolio website - https://a-shirude.github.io/

Modern, tech-focused portfolio website for a Senior Software Engineer specializing in distributed systems, Go, and Python.

## 🎨 Design Philosophy

- **Tech Aesthetic**: Dark theme with cyan accents, monospace typography, grid background
- **Developer-First**: Inspired by best portfolios (Brittany Chiang, Lee Robinson style)
- **Minimal & Compact**: Information-dense without clutter
- **Performance**: Pure HTML/CSS/JS, no frameworks, optimized animations

## ✨ Features

### Visual Design
- Dark/light theme toggle with persistent preference
- Animated grid background with parallax effect
- Custom scrollbar styling
- Smooth fade-in animations on scroll
- Hover effects with glow accents

### Sections
1. **Hero**: High-impact intro with key metrics inline
2. **About**: Focus areas with compact stats grid
3. **Experience**: Tab-based interface for 5 companies
4. **Skills**: Icon-based categories + Education card
5. **Contact**: CTA with social links

### Technical
- Fully responsive (mobile-first approach)
- Intersection Observer for performance
- CSS custom properties for theming
- Semantic HTML5
- Accessible (ARIA labels, keyboard navigation)


## 🛠️ Tech Stack

```
HTML5 + CSS3 + Vanilla JavaScript
├── Fonts: Inter (sans), JetBrains Mono (monospace)
├── Icons: Custom SVG
└── No dependencies or build process
```

## 🚀 Setup

```bash
# Clone or download
git clone <repo>

# Open in browser
open index.html

# Or use any static server
python -m http.server 8000
npx serve
```

## 🎨 Customization

### Colors (CSS Variables)
```css
:root {
    --primary: #64ffda;        /* Cyan accent */
    --bg-primary: #0a192f;     /* Navy background */
    --text-primary: #ccd6f6;   /* Light text */
    /* ... see styles.css for all variables */
}
```

### Content
- **Hero**: Update name, tagline, stats in `index.html`
- **Experience**: Add/edit company panels in Experience section
- **Skills**: Modify skill categories and lists
- **Education**: Update degree, school, years

## 📱 Responsive Breakpoints

- Desktop: > 768px (full layout)
- Tablet: 481-768px (adjusted grid)
- Mobile: ≤ 480px (stacked layout)

## ⚡ Performance

- Lazy loading via Intersection Observer
- CSS transitions with GPU acceleration
- Optimized repaints and reflows
- Small bundle size (~60KB total)

## 🌐 Deployment

Works on any static host:
```bash
# GitHub Pages
gh-pages -d .

# Netlify
netlify deploy --prod

# Vercel
vercel --prod

# Traditional
rsync -avz . user@server:/var/www/html/
```

## 📄 License

© 2026 Akshay Shirude. Feel free to fork and customize for your own portfolio.

---

**Built for consulting & mentoring | akshayshirude1@gmail.com**
