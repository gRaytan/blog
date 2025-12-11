# Gil Raytan - Personal Website

A professional personal branding website showcasing my work as an engineering leader, products, writing, and professional journey.

## 🚀 Live Site

Visit the live site at: `https://graytan.github.io/blog/`

## 📋 Features

- **Responsive Design**: Fully responsive layout that works on desktop, tablet, and mobile
- **Modern UI**: Clean, professional design with smooth animations
- **Single Page Application**: Easy navigation with smooth scrolling
- **SEO Optimized**: Proper meta tags and semantic HTML
- **Fast Loading**: Minimal dependencies, optimized for performance

## 🛠️ Tech Stack

- **HTML5**: Semantic markup
- **CSS3**: Modern bento-style dashboard layout with CSS Grid
- **Vanilla JavaScript**: Interactive elements
- **Google Fonts**: Inter font family
- **GitHub Pages**: Free hosting

## 📁 Project Structure

```
blog/
├── index.html          # Main HTML file
├── styles.css          # All CSS styles
├── script.js           # JavaScript for interactivity
└── README.md           # This file
```

## 🚀 Deployment to GitHub Pages

### Step 1: Push to GitHub

```bash
git add .
git commit -m "Initial commit: Personal website"
git push origin main
```

### Step 2: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on **Settings**
3. Scroll down to **Pages** section (in the left sidebar)
4. Under **Source**, select **main** branch
5. Click **Save**
6. Your site will be published at `https://graytan.github.io/blog/`

### Step 3: Wait for Deployment

GitHub Pages typically takes 1-2 minutes to deploy. You'll see a green checkmark when it's ready.

## 🎨 Customization

### Adding More Career Tiles

Edit `index.html` and add more tiles in the Career section:

```html
<div class="bento-tile tile-company">
    <img src="logo-url.svg" alt="Company" class="tile-logo">
    <h3>Company Name</h3>
    <p class="role">Your Role</p>
    <p class="period">2020 - 2023</p>
    <p class="details">Description of your work.</p>
</div>
```

### Adding More Writing Posts

Add more post tiles in the Writing section:

```html
<div class="bento-tile tile-post">
    <span class="post-tag">Category</span>
    <h3>Post Title</h3>
    <p class="details">Post description...</p>
    <a href="https://your-post-link" target="_blank" class="tile-link">Read More →</a>
</div>
```

### Changing Colors

Edit the CSS variables in `styles.css`:

```css
:root {
    --bg-dark: #0a0a0a;
    --accent-blue: #3b82f6;
    /* ... other colors */
}
```

## 📱 Local Development

To run locally, simply open `index.html` in your browser. No build process required!

Or use a simple HTTP server:

```bash
# Python 3
python -m http.server 8000

# Node.js (if you have http-server installed)
npx http-server
```

Then visit `http://localhost:8000`

## 📝 Content Updates

- **Hero**: Edit name, tagline, and intro in the hero section
- **Career**: Add/edit career tiles with company logos and details
- **Writing**: Add/edit writing post tiles
- **Projects**: Add/edit project and contact tiles

## 🔧 Future Enhancements

- [ ] Add more writing posts
- [ ] Add podcast section
- [ ] Add press mentions section
- [ ] Add project showcase with images
- [ ] Add analytics

## 📄 License

© 2024 Gil Raytan. All rights reserved.

## 🤝 Contact

- **Email**: gil.raytan@gmail.com
- **LinkedIn**: [linkedin.com/in/gil-raytan](https://www.linkedin.com/in/gil-raytan/)
- **GitHub**: [github.com/gRaytan](https://github.com/gRaytan)
- **Substack**: [@gilraytan](https://substack.com/@gilraytan)