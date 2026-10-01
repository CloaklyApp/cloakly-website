# Cloakly Official Website

Official website for Cloakly.ai - AI-powered local document redaction tool.

## 🌐 Live Site

**Production:** https://cloakly.ai

## 📁 Repository Structure

```
cloakly-website/
├── index.html              # English homepage
├── index-zh.html           # Chinese homepage
├── index-ja.html           # Japanese homepage
├── index-de.html           # German homepage
├── support.html            # English support page
├── support-zh.html         # Chinese support page
├── support-ja.html         # Japanese support page
├── support-de.html         # German support page
├── privacy.html            # English privacy policy
├── privacy-zh.html         # Chinese privacy policy
├── privacy-ja.html         # Japanese privacy policy
├── privacy-de.html         # German privacy policy
├── css/
│   └── style.css          # Unified stylesheet
├── images/
│   ├── logo.svg           # Logo
│   └── icon.png           # Icon
├── CNAME                  # Custom domain configuration
└── README.md              # This file
```

## 🚀 Deployment

This website is hosted on **GitHub Pages** with a custom domain.

### GitHub Pages Configuration
- **Source:** `main` branch, root directory
- **Custom Domain:** cloakly.ai
- **HTTPS:** Enforced (Let's Encrypt)

### DNS Configuration (Namecheap)
```
A Record: @ → 185.199.108.153
A Record: @ → 185.199.109.153
A Record: @ → 185.199.110.153
A Record: @ → 185.199.111.153
CNAME Record: www → [username].github.io.
```

## 🎨 Design

- **Style:** Modern, minimalist (Apple-inspired)
- **Primary Color:** Orange (#FF9500) - matches app upgrade button
- **Responsive:** Mobile, tablet, and desktop optimized
- **Font:** SF Pro Display / System fonts

## 🌍 Multilingual Support

- English (default)
- 中文简体 (Chinese Simplified)
- 日本語 (Japanese)
- Deutsch (German)

## 📝 Content

### Homepage
- Hero section with call-to-action
- Features showcase (6 key features)
- Use cases (Legal, Healthcare, HR, Research)
- Pricing comparison (Free vs Professional)

### Support Page
- FAQ (Frequently Asked Questions)
- Getting started guide
- Troubleshooting tips
- Contact information

### Privacy Policy
- Complete privacy policy
- GDPR and CCPA compliance information
- Data handling transparency

## 🔧 Local Development

To test locally:

```bash
# Option 1: Python
python3 -m http.server 8000

# Option 2: Node.js
npx http-server

# Then open: http://localhost:8000
```

## 📱 App Store Integration

This website serves as:
- **Support URL:** https://cloakly.ai/support.html
- **Marketing URL:** https://cloakly.ai

## 🔒 Privacy & Security

- **No analytics:** No Google Analytics, Mixpanel, or tracking
- **No cookies:** Static site, no cookies used
- **No external resources:** All assets hosted locally
- **HTTPS:** Enforced for all connections

## 📄 License

© 2024 Cloakly. All rights reserved.

## 📧 Contact

For website issues or suggestions:
- Email: cloaklyapp@gmail.com

## 🛠️ Maintenance

### Updating Content
1. Edit HTML files directly
2. Commit changes to `main` branch
3. GitHub Pages automatically deploys (2-3 minutes)

### Adding New Languages
1. Create new HTML files: `index-[lang].html`, `support-[lang].html`, `privacy-[lang].html`
2. Update navigation links in all existing pages
3. Update footer language selector

## ✅ SEO Optimization

- Meta descriptions on all pages
- Semantic HTML structure
- Mobile-friendly (responsive design)
- Fast loading (minimal CSS, no JavaScript)
- Proper heading hierarchy
- Alt text for images (when added)

## 📊 Performance

- **Page Size:** ~20-30 KB per page (HTML + CSS)
- **Load Time:** <1 second
- **No Dependencies:** Pure HTML/CSS, no frameworks

## 🎯 Future Enhancements

Potential improvements:
- [ ] Add blog section
- [ ] Add video demo
- [ ] Add customer testimonials
- [ ] Add changelog page
- [ ] Improve SEO with structured data
- [ ] Add language auto-detection

---

Built with ❤️ for privacy-conscious users worldwide.
