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
- **CSS3**: Modern styling with CSS Grid and Flexbox
- **Vanilla JavaScript**: Smooth scrolling and animations
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

### Adding More Products

Edit `index.html` and add more product cards in the Products section:

```html
<div class="product-card">
    <h3>Your Product Name</h3>
    <p>Product description here.</p>
    <a href="https://yourproduct.com" target="_blank" class="product-link">Visit Site →</a>
</div>
```

### Adding More Articles

Add more article cards in the Writing section:

```html
<article class="article-card">
    <h3>Article Title</h3>
    <p>Article description...</p>
    <a href="https://your-article-link" target="_blank" class="article-link">Read More →</a>
</article>
```

### Changing Colors

Edit the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #2563eb;    /* Change to your preferred color */
    --secondary-color: #1e40af;
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

- **Bio**: Edit the About section in `index.html`
- **Products**: Add/edit product cards in the Products section
- **Writing**: Add/edit articles in the Writing section
- **Contact**: Update social links in the Contact section

## 🔧 Future Enhancements

- [ ] Add blog integration
- [ ] Add podcast section with episodes
- [ ] Add press mentions
- [ ] Add dark mode toggle
- [ ] Add contact form
- [ ] Add analytics

## 📄 License

© 2024 Gil Raytan. All rights reserved.

## 🤝 Contact

- **Email**: gil.raytan@gmail.com
- **LinkedIn**: [linkedin.com/in/gil-raytan](https://www.linkedin.com/in/gil-raytan/)
- **GitHub**: [github.com/gRaytan](https://github.com/gRaytan)
- **Substack**: [@gilraytan](https://substack.com/@gilraytan)