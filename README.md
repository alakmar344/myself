# Alakmar Teenwala - Portfolio

A modern, editorial-style portfolio showcasing AI architecture and full-stack development work.

## 🎨 Design Philosophy

This portfolio breaks away from typical AI-generated designs with a bold, editorial aesthetic inspired by high-end magazine layouts. Every element is carefully crafted to create a memorable, distinctive experience.

### Key Design Features

- **Editorial Typography**: Playfair Display serif headlines paired with Space Mono monospace accents
- **Warm Color Palette**: Paper-textured background with vibrant orange accents (#ff4d00)
- **Custom Cursor**: Interactive circular cursor with blend modes
- **Asymmetric Layouts**: Projects alternate between left/right with diagonal overlays
- **Micro-interactions**: Staggered animations, counter effects, and hover states

## 🚀 Features

- **Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **Smooth Animations**: Entrance animations, scroll-triggered reveals, and hover effects
- **Accessible**: Semantic HTML and proper contrast ratios
- **Performance Optimized**: Pure CSS animations, efficient JavaScript
- **No Dependencies**: Vanilla JavaScript with Google Fonts only

## 📂 Structure

```
portfolio.html
├── Hero Section
│   ├── Name & Title
│   ├── Introduction
│   ├── Key Metrics (430+ users, 120k context, 99% uptime)
│   └── CTA Buttons
├── Technical Arsenal (Section 01)
│   ├── AI & Machine Learning
│   ├── Web Development
│   └── Infrastructure & DevOps
├── Featured Work (Section 02)
│   ├── eSAMz AI - AI Chat Platform
│   └── CiboCocinar - Voice Cooking Assistant
├── Contact Section
│   ├── GitHub
│   ├── Email
│   └── Websites (esamz.site, esamz.info)
└── Footer
```

## 🛠 Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Custom properties, animations, grid, flexbox
- **JavaScript**: Vanilla JS for interactions
- **Google Fonts**: Playfair Display, Space Mono, DM Sans

## 🎯 Interactive Elements

### Custom Cursor
- Follows mouse movement
- Grows on hover over interactive elements
- Uses `mix-blend-mode: difference` for visual effect

### Scroll Animations
- Hero text slides up with staggered delays
- Expertise cards and project cards fade in on scroll
- Smooth scroll behavior for anchor links

### Counter Animations
- Stats animate from 0 to final value
- Triggered when scrolled into view
- Only animates once per session

### Hover Effects
- Sweep-through effect on expertise cards
- Button background transitions
- Link color and transform changes

## 🎨 Color Scheme

```css
--ink: #0a0a0a          /* Primary text */
--paper: #faf8f5         /* Background */
--accent: #ff4d00        /* Primary accent */
--accent-soft: #ff7a3d   /* Secondary accent */
--gray: #666666          /* Secondary text */
--light-gray: #e0ddd8    /* Borders */
--border: #d4d0ca        /* Light borders */
```

## 📱 Responsive Breakpoints

- **Desktop**: 969px and above (full experience with custom cursor)
- **Tablet/Mobile**: Below 969px (simplified layout, standard cursor)

## 🚀 Deployment

### Local Development
Simply open `portfolio.html` in a modern browser.

### Production Deployment

**Vercel** (Recommended):
```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
vercel
```

**Netlify**:
```bash
# Drag and drop portfolio.html to Netlify dashboard
# Or use Netlify CLI
netlify deploy
```

**GitHub Pages**:
```bash
# Push to GitHub
git add portfolio.html
git commit -m "Add portfolio"
git push

# Enable GitHub Pages in repository settings
```

## ✨ Customization Guide

### Update Personal Info
1. **Name**: Search for "Alakmar Teenwala" and replace
2. **Email**: Update `mailto:esamzai365@gmail.com`
3. **GitHub**: Update `https://github.com/alakmar344`
4. **Websites**: Update `esamz.site` and `esamz.info`

### Modify Projects
Edit the `.project-card` sections:
```html
<div class="project-card">
    <div class="project-content">
        <div class="project-number">PROJECT 01</div>
        <h3>Your Project Name</h3>
        <p class="project-role">Your Role · Year</p>
        <!-- ... rest of content -->
    </div>
</div>
```

### Change Colors
Update CSS custom properties in the `:root` selector:
```css
:root {
    --accent: #your-color;
    --paper: #your-background;
}
```

### Add New Sections
Follow the existing pattern:
```html
<section class="your-section">
    <div class="section-header">
        <div class="section-number">03</div>
        <div class="section-title-wrap">
            <h2>Your Title</h2>
            <p class="section-subtitle">Your subtitle</p>
        </div>
    </div>
    <!-- Your content -->
</section>
```

## 📊 Performance

- **First Contentful Paint**: < 1s
- **Time to Interactive**: < 2s
- **Lighthouse Score**: 95+ (Performance, Accessibility, Best Practices, SEO)

## 🔧 Browser Support

- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Opera 76+

## 📄 License

This portfolio design is open source and free to use. Feel free to fork, modify, and make it your own!

## 🤝 Credits

**Design & Development**: Alakmar Teenwala  
**Fonts**: Google Fonts (Playfair Display, Space Mono, DM Sans)

## 📞 Contact

- **Email**: esamzai365@gmail.com
- **GitHub**: [@alakmar344](https://github.com/alakmar344)
- **Website**: [esamz.site](https://esamz.site) · [esamz.info](https://esamz.info)

---

**Built with Intelligence & Precision** ⚡
