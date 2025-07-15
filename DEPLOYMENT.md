# GitHub Pages Deployment Guide

This guide will help you deploy your portfolio website to GitHub Pages and configure your custom domain.

## 🚀 Quick Deployment

### 1. Push to GitHub
```bash
git add .
git commit -m "Add portfolio website"
git push origin main
```

### 2. Enable GitHub Pages
1. Go to your repository on GitHub
2. Click on **Settings** tab
3. Scroll down to **Pages** section
4. Under **Source**, select **Deploy from a branch**
5. Choose **main** branch and **/ (root)** folder
6. Click **Save**

### 3. Configure Custom Domain (Optional)
1. In the same Pages section, enter your domain: `prashanthmerugu.io`
2. Check **Enforce HTTPS** (recommended)
3. Click **Save**

### 4. DNS Configuration
If using a custom domain, configure your DNS:
- **Type**: CNAME
- **Name**: @ (or your subdomain)
- **Value**: `yourusername.github.io`

## 📁 File Structure
```
prashanthmerugu.github.io/
├── index.html              # Main website file
├── styles.css              # Styles and animations
├── script.js               # JavaScript functionality
├── README.md               # Repository documentation
├── DEPLOYMENT.md           # This file
└── resume.md               # Resume content
```

## 🔧 Customization

### Update Content
- Edit `index.html` for main content
- Modify `styles.css` for styling
- Update `script.js` for functionality

### Add Images
1. Place images in the root folder
2. Reference them in HTML: `<img src="image.jpg" alt="Description">`

### Update Meta Tags
Edit the `<head>` section in `index.html` for:
- Page title
- Meta description
- Social media cards
- SEO keywords

## 🌐 Domain Setup

### Option 1: GitHub Pages Domain
- URL: `https://prashanthmerugu.github.io`
- No additional setup required

### Option 2: Custom Domain
1. Purchase domain (e.g., from Namecheap, GoDaddy)
2. Configure DNS records
3. Add domain in GitHub Pages settings
4. Wait for DNS propagation (up to 48 hours)

## 📊 Performance Optimization

### Before Deployment
- [ ] Optimize images (compress, use WebP format)
- [ ] Minify CSS and JavaScript (optional)
- [ ] Test on multiple devices
- [ ] Check loading speed

### After Deployment
- [ ] Test all links and forms
- [ ] Verify mobile responsiveness
- [ ] Check browser compatibility
- [ ] Monitor page load times

## 🔍 SEO Checklist

- [ ] Meta title and description
- [ ] Open Graph tags
- [ ] Twitter Card tags
- [ ] Structured data (optional)
- [ ] XML sitemap (optional)
- [ ] robots.txt (optional)

## 🛠️ Troubleshooting

### Common Issues

**Page not loading:**
- Check if GitHub Pages is enabled
- Verify the source branch and folder
- Wait for deployment (can take a few minutes)

**Custom domain not working:**
- Verify DNS configuration
- Check domain settings in GitHub
- Wait for DNS propagation

**Styling issues:**
- Clear browser cache
- Check file paths in HTML
- Verify CSS file is in the root folder

### Support
- GitHub Pages documentation: https://pages.github.com/
- GitHub Help: https://help.github.com/

## 📈 Analytics (Optional)

### Google Analytics
1. Create Google Analytics account
2. Get tracking ID
3. Add tracking code to `index.html` before `</head>`

### GitHub Pages Analytics
- Available in repository Settings > Pages
- Shows page views and referrers

---

**Your portfolio will be live at: https://prashanthmerugu.github.io**

*Last updated: January 2024* 