# Razor Security Website

High-tech cybersecurity website for **razorsecurity.net** - showcasing AI security, LLM protection, network defense, and asset protection services.

## 🎨 Design Features

- **Dark Cyber Aesthetic**: Razor-sharp design with red/cyan accent colors and animated grid background
- **Custom Typography**: Orbitron (headings) + JetBrains Mono (body) for a distinctive tech feel
- **Advanced Animations**: Floating orbs, grid scrolling, scanline effects, and hover interactions
- **Fully Responsive**: Adapts seamlessly to all screen sizes
- **Performance Optimized**: Pure HTML/CSS with minimal dependencies

## 🚀 Quick Start

### Option 1: GitHub Pages (Recommended)

1. Create a new repository on GitHub
2. Upload `index.html` to the repository
3. Go to Settings → Pages
4. Select "Deploy from a branch" and choose `main` branch
5. Your site will be live at `https://yourusername.github.io/repository-name`

### Option 2: Custom Domain (razorsecurity.net)

1. Follow GitHub Pages setup above
2. In your repository settings → Pages → Custom domain, enter `razorsecurity.net`
3. In your domain registrar (where you bought razorsecurity.net), add these DNS records:
   ```
   Type: A
   Name: @
   Value: 185.199.108.153
   
   Type: A
   Name: @
   Value: 185.199.109.153
   
   Type: A
   Name: @
   Value: 185.199.110.153
   
   Type: A
   Name: @
   Value: 185.199.111.153
   
   Type: CNAME
   Name: www
   Value: yourusername.github.io
   ```
4. Wait for DNS propagation (can take up to 48 hours, usually much faster)
5. Enable "Enforce HTTPS" in GitHub Pages settings

### Option 3: Local Development

Simply open `index.html` in any modern web browser - no build process required!

## 📁 File Structure

```
razorsecurity-website/
├── index.html          # Main website file (self-contained)
└── README.md          # This file
```

## 🎯 Features Highlighted

- **LLM Security & Training**: Adversarial robustness, prompt injection prevention
- **AI Attack Defense**: Real-time threat detection, behavioral analysis
- **Network Fortification**: Zero-trust architecture, DDoS mitigation
- **Asset Protection**: Data loss prevention, IP protection
- **Threat Intelligence**: Predictive analytics, dark web monitoring
- **Security Research**: Penetration testing, vulnerability assessment

## 🛠️ Customization Guide

### Colors
Edit the CSS variables at the top of the `<style>` section:
```css
:root {
    --razor-red: #ff0033;      /* Primary accent */
    --razor-cyan: #00ffff;     /* Secondary accent */
    --razor-purple: #9d00ff;   /* Tertiary */
    --dark-bg: #0a0a0f;        /* Main background */
}
```

### Content
All content is in the HTML file - search for section IDs:
- `#services` - Service offerings
- `#technology` - Tech stack
- `#contact` - Contact information
- Footer links and information

### Typography
Fonts are loaded from Google Fonts:
- **Orbitron**: Display/headings font
- **JetBrains Mono**: Body/code font

To change fonts, modify the Google Fonts link and CSS font-family declarations.

## 🔒 Security Features (Meta!)

This website demonstrates security principles:
- No external dependencies (except fonts)
- No JavaScript tracking
- No cookies or local storage
- Static HTML - minimal attack surface
- Content Security Policy ready

## 📱 Browser Support

- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- All modern mobile browsers

## 🤝 Contributing

This is a single-page site. To make changes:
1. Fork the repository
2. Edit `index.html`
3. Test locally
4. Submit a pull request

## 📧 Contact

For inquiries: contact@razorsecurity.net

## 📄 License

© 2026 RazorSecurity. All rights reserved.

---

**Built with precision. Deployed with confidence.**
