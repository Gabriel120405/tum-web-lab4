# Quick Start Guide - Lab 4

## 🚀 Local Development (5 minutes)

```bash
# 1. Navigate to project
cd tum-web-lab4

# 2. Install dependencies
npm install

# 3. Start development server
npm start

# 4. Open browser
# Visit: http://localhost:8080
# CMS Admin: http://localhost:8080/admin/
```

## 📦 Build for Production

```bash
npm run build
# Output: _site/ folder (ready to deploy)
```

## 🌐 Deploy Options

### Option 1: Netlify (Recommended - Free CMS)

```bash
# Install Netlify CLI
npm install -g netlify-cli

# Deploy
netlify deploy --prod

# Get live URL with Git gateway enabled CMS
```

**Advantages:**
- Built-in Git gateway for CMS authentication
- Automatic builds on git push
- Free tier includes everything needed
- Live preview deployments

### Option 2: GitHub Pages (Free hosting)

```bash
# 1. Push to GitHub
git push origin main

# 2. Go to GitHub repo settings
# Settings > Pages > Select main branch, _site folder

# 3. Site goes live at username.github.io/tum-web-lab4
```

**Note:** For CMS on GitHub Pages, you'll need alternative authentication or Netlify's Git gateway

### Option 3: Vercel (Free alternative)

```bash
# Install Vercel CLI
npm install -g vercel

# Deploy
vercel --prod
```

## 📝 Content Management

### Editing Content (After deployment on Netlify)

1. Go to `your-site.netlify.app/admin/`
2. Sign in with GitHub
3. Edit pages, products, or settings
4. Changes auto-commit to your repo

### Local CMS Testing

```bash
# CMS available at: http://localhost:8080/admin/
# (Git gateway won't work locally without special setup)
```

## 🔧 Configuration Notes

**Site Settings:** `src/_data/site.json`
```json
{
  "title": "Change site title here",
  "description": "Change description here",
  "logo": "Change logo text here",
  "company": "Change company name here"
}
```

**CMS Collections:** `src/admin/config.yml`
- Add/remove collections
- Add/remove fields
- Customize editing interface

## 📊 Project Structure

```
src/
  ├── content/           # All editable content
  │   ├── index.md      # Home page
  │   └── products/     # Product pages (editable via CMS)
  ├── _layouts/         # HTML templates
  ├── _data/            # JSON data files
  ├── admin/            # CMS interface
  ├── css/              # Stylesheets
  └── assets/           # Images, media

_site/                  # Generated site (deploy this!)
```

## 🔄 Git Workflow

```bash
# Make changes locally
npm start

# Test changes
# Visit http://localhost:8080

# Commit changes
git add .
git commit -m "fix: update product descriptions"

# Push to remote
git push origin main

# Netlify/GitHub auto-deploys!
```

## 📚 Helpful Resources

- **11ty Docs:** https://www.11ty.dev/docs/
- **Decap CMS:** https://decapcms.org/docs/intro/
- **Netlify Docs:** https://docs.netlify.com/
- **Tailwind CSS:** https://tailwindcss.com/docs

## ✅ Checklist for Deployment

- [ ] All content looks correct locally
- [ ] npm run build completes without errors
- [ ] Git commits are clean and descriptive
- [ ] Repository is pushed to GitHub
- [ ] Choose deployment platform (Netlify recommended)
- [ ] Deployed to live URL
- [ ] CMS accessible at /admin/
- [ ] Test content editing via CMS
- [ ] Verify git commits from CMS changes

## 🐛 Troubleshooting

### npm install fails
```bash
# Clear npm cache
npm cache clean --force
rm -rf node_modules
npm install
```

### Build errors
```bash
# Check Node version (need 14+)
node --version

# Rebuild
npm run build
```

### CMS not loading
- Check `src/admin/config.yml` syntax
- Ensure `src/admin/index.html` exists
- For Git gateway: must be deployed on Netlify or configured Git host

## 📞 Support

Refer to README.md for detailed documentation.

---

**Lab 4 - Web Development**
*Static Site Generator with Git CMS*
