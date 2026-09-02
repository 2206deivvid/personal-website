# Personal Portfolio Website

A modern, responsive personal portfolio website built with vanilla HTML, CSS, and JavaScript.

## ✨ Features

- **Clean & Modern Design** - Fully responsive layout with smooth scrolling and animations
- **No Dependencies** - Pure HTML, CSS, and JavaScript (no build tools needed)
- **Mobile-Friendly** - Touch-optimized and works on all devices
- **Customizable** - Easy to edit colors, content, and styling
- **GitHub Pages Ready** - Deploy for free with one click

## 📁 Project Structure

```
personal-website/
├── index.html           # Main HTML file
├── styles/
│   └── main.css         # All styling
├── scripts/
│   └── main.js          # Interactive features
├── README.md            # This file
└── .gitignore           # Git ignore rules
```

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/2206deivvid/personal-website.git
cd personal-website
```

### 2. Edit Your Information

Open `index.html` and update:
- Your name in the navbar and hero section
- Your bio in the About section
- Your skills (add/remove skill tags)
- Your projects with descriptions and links
- Your contact information

### 3. Customize the Colors

Edit `styles/main.css` and update the CSS variables at the top:

```css
:root {
    --primary-color: #0066cc;      /* Main brand color */
    --secondary-color: #333333;    /* Dark text */
    --accent-color: #00d4ff;       /* Highlight color */
    /* ... more variables */
}
```

### 4. Add Your Projects

In the Projects section of `index.html`, update each project card with:
- Project title
- Description
- Link to your project/GitHub repo

### 5. Deploy to GitHub Pages

1. Go to your repository settings
2. Scroll to **Pages** section
3. Set source to **Deploy from a branch**
4. Select **main** branch and **/ (root)** folder
5. Click **Save**

Your site will be live at: `https://2206deivvid.github.io/personal-website/`

## 📱 Responsive Breakpoints

- **Desktop**: 1200px+
- **Tablet**: 768px - 1200px
- **Mobile**: < 768px

All sections automatically adapt to screen size.

## 🎨 Customization Tips

### Change Font
Replace the font-family in `styles/main.css`:
```css
body {
    font-family: 'Your Font', sans-serif;
}
```

### Add More Projects
Copy a project card in `index.html` and update:
```html
<div class="project-card">
    <h3>Your Project Name</h3>
    <p>Project description here</p>
    <a href="project-link" class="project-link">View Project →</a>
</div>
```

### Add Social Links
Update the contact links in the Contact section with your actual URLs:
```html
<a href="https://github.com/yourusername" class="contact-link">GitHub</a>
```

### Add a Profile Image
Add an image element in the Hero section:
```html
<img src="images/profile.jpg" alt="Your Name" class="profile-pic">
```

Then style in CSS:
```css
.profile-pic {
    width: 200px;
    height: 200px;
    border-radius: 50%;
    margin-bottom: 2rem;
}
```

## 🔧 JavaScript Features

- **Smooth Scroll** - Clicking nav links smoothly scrolls to sections
- **Fade-in Animations** - Project cards fade in as you scroll
- **Active Nav Highlighting** - Current section highlighted in navbar
- **Mobile Menu Ready** - Structure ready for hamburger menu

## 📚 Resources

- [HTML Reference](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [CSS Reference](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [GitHub Pages Docs](https://docs.github.com/en/pages)
- [Web Accessibility](https://www.w3.org/WAI/fundamentals/accessibility-intro/)

## 💡 Best Practices

1. **High-Quality Images** - Use clear, professional images for projects
2. **Concise Descriptions** - Keep project descriptions brief and impactful
3. **Test on Mobile** - Always preview on phone/tablet
4. **Keep Content Fresh** - Update projects and bio regularly
5. **Add Real Links** - Link to actual GitHub repos, live demos, or websites
6. **SEO Friendly** - Update the meta description in `index.html`

## 🛠️ Troubleshooting

### Site not showing on GitHub Pages
- Make sure settings → Pages is set to deploy from main branch
- Wait a few minutes for deployment to complete
- Clear browser cache and refresh

### Styling not loading
- Verify the CSS file path is correct: `styles/main.css`
- Clear browser cache
- Check browser console for 404 errors

### Links not working
- Use absolute URLs (starting with `https://`) for external links
- Use relative paths for internal links

## 📄 License

Feel free to use this template for your personal portfolio!

## 🤝 Contributing

Feel free to fork, modify, and improve this template for your needs!

---

**Happy building! 🎉**

Made with ❤️ by 2206deivvid
