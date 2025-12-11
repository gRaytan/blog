# 🚀 Quick Deployment Guide

## Deploy to GitHub Pages in 3 Steps

### Step 1: Commit and Push Your Code

```bash
# Initialize git (if not already done)
git init

# Add all files
git add .

# Commit
git commit -m "Initial commit: Personal website"

# Add remote (replace with your repository URL)
git remote add origin https://github.com/gRaytan/blog.git

# Push to GitHub
git push -u origin main
```

### Step 2: Enable GitHub Pages

1. Go to https://github.com/gRaytan/blog
2. Click **Settings** (top right)
3. Click **Pages** in the left sidebar
4. Under **Source**:
   - Select branch: **main**
   - Select folder: **/ (root)**
5. Click **Save**

### Step 3: Access Your Site

Your site will be live at:
```
https://graytan.github.io/blog/
```

⏱️ **Note**: It may take 1-2 minutes for the site to go live.

---

## 🌐 Optional: Add a Custom Domain

### If you have a custom domain (e.g., gilraytan.com):

1. In GitHub Pages settings, add your custom domain
2. In your domain registrar (GoDaddy, Namecheap, etc.), add these DNS records:

**For apex domain (gilraytan.com):**
```
Type: A
Name: @
Value: 185.199.108.153
Value: 185.199.109.153
Value: 185.199.110.153
Value: 185.199.111.153
```

**For www subdomain:**
```
Type: CNAME
Name: www
Value: graytan.github.io
```

3. Wait for DNS propagation (can take up to 24 hours)

---

## ✅ Verify Deployment

After deployment, check:
- [ ] Site loads correctly
- [ ] All links work
- [ ] Images display (if any)
- [ ] Mobile responsive design works
- [ ] Smooth scrolling works
- [ ] Contact links open correctly

---

## 🔄 Making Updates

After making changes to your site:

```bash
git add .
git commit -m "Update: description of changes"
git push
```

GitHub Pages will automatically redeploy within 1-2 minutes.

---

## 🐛 Troubleshooting

**Site not loading?**
- Check that GitHub Pages is enabled in Settings
- Verify the branch is set to `main`
- Wait a few minutes and refresh

**CSS/JS not loading?**
- Make sure file paths are correct
- Check browser console for errors
- Clear browser cache

**404 Error?**
- Verify repository name matches URL
- Check that index.html is in the root directory

---

## 📊 Optional: Add Analytics

To track visitors, add Google Analytics:

1. Get your Google Analytics tracking ID
2. Add this before `</head>` in index.html:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=YOUR-GA-ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'YOUR-GA-ID');
</script>
```

---

## 🎉 You're Live!

Your personal website is now live and accessible to the world!

Share it on:
- LinkedIn profile
- Email signature
- Business cards
- Social media

---

**Need help?** Check the main README.md for more details.
