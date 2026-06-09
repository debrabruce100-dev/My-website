# Debra Bruce - Personal Website

Welcome to my personal portfolio website! This is a modern, responsive website showcasing my work and experience.

## 📁 Project Structure

```
My-website/
├── index.html          # Homepage
├── about.html          # About page
├── portfolio.html      # Portfolio/Projects page
├── contact.html        # Contact page
├── styles.css          # Main stylesheet
└── README.md           # This file
```

## 🌐 Pages Included

- **Home** (`index.html`) - Landing page with hero section and featured services
- **About** (`about.html`) - Information about you and your skills
- **Portfolio** (`portfolio.html`) - Showcase of your projects
- **Contact** (`contact.html`) - Contact form and information

## ✨ Features

- ✅ Responsive design (works on desktop, tablet, and mobile)
- ✅ Modern, clean aesthetic
- ✅ Smooth animations and transitions
- ✅ Contact form with validation
- ✅ Social media links
- ✅ Professional color scheme
- ✅ SEO-friendly HTML structure

## 🎨 Customization Guide

### Change Your Name/Title
Edit the following in each HTML file:
- Replace "Debra Bruce" with your name in the title, logo, and footer
- Update the subtitle text in the hero section

### Update Portfolio Projects
In `portfolio.html`, modify the `.portfolio-card` sections:
```html
<div class="portfolio-card">
    <div class="portfolio-image">
        <div class="placeholder">Your Project Name</div>
    </div>
    <div class="portfolio-info">
        <h3>Your Project Title</h3>
        <p>Your project description</p>
        <div class="portfolio-tags">
            <span class="tag">Technology</span>
        </div>
    </div>
</div>
```

### Add Your Contact Information
In `contact.html`, update:
```html
<p><a href="mailto:your.email@example.com">your.email@example.com</a></p>
```

### Update Social Media Links
Replace `#` with your actual social media profiles:
```html
<a href="https://linkedin.com/in/yourprofile" target="_blank">LinkedIn</a>
<a href="https://github.com/yourprofile" target="_blank">GitHub</a>
```

### Customize Colors
In `styles.css`, modify the CSS variables in `:root`:
```css
:root {
    --primary-color: #667eea;        /* Main color */
    --secondary-color: #764ba2;      /* Accent color */
    --text-color: #333;              /* Text color */
    --light-bg: #f7fafc;             /* Light background */
}
```

## 🚀 Getting Started

1. **View locally**: Open any HTML file in your web browser
2. **Deploy**: Upload these files to your web hosting service or GitHub Pages
3. **Customize**: Edit the HTML and CSS to match your personal brand

## 📱 Responsive Breakpoints

The website is optimized for:
- Desktop: 1200px and above
- Tablet: 768px to 1199px
- Mobile: 480px to 767px
- Small Mobile: Below 480px

## 💡 Tips for Better Results

1. Add actual project images to your portfolio
2. Write compelling descriptions for your projects
3. Use professional photos or avatars
4. Keep content concise and engaging
5. Regularly update your portfolio with new work
6. Test on different devices before launching

## 🔧 Technologies Used

- HTML5
- CSS3 (with Flexbox and CSS Grid)
- Vanilla JavaScript
- Responsive design principles

## 📝 License

This template is free to use and modify for your personal website.

---

**Need help?** Review the HTML comments in each file for additional guidance on customization.

Happy building! 🚀
