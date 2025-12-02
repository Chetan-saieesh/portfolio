# Portfolio Website

A clean, professional personal portfolio website for K. Chetan Saieesh.

## Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI**: Clean and professional design with smooth animations
- **Smooth Scrolling**: Navigation links smoothly scroll to sections
- **Organized Sections**: About, Skills, Education, Projects, and Contact

## File Structure

```
portfolio/
├── index.html      # Main HTML file
├── styles.css      # Stylesheet with modern design
├── script.js       # JavaScript for interactivity
└── README.md       # This file
```

## Customization Guide

### 1. Update Contact Information

Edit the contact section in `index.html` (around line 150-160):
- Replace `your.email@example.com` with your actual email
- Replace `yourusername` in GitHub and LinkedIn URLs with your actual usernames

### 2. Add Your Projects

In the Projects section of `index.html`, replace the placeholder project cards with your actual projects:

```html
<div class="project-card">
    <h3 class="project-title">Your Project Name</h3>
    <p class="project-description">Your project description here...</p>
    <div class="project-tech">
        <span class="tech-tag">Technology 1</span>
        <span class="tech-tag">Technology 2</span>
    </div>
    <div class="project-links">
        <a href="your-github-link" class="project-link">GitHub</a>
        <a href="your-demo-link" class="project-link">Live Demo</a>
    </div>
</div>
```

### 3. Customize Colors

Edit the CSS variables in `styles.css` (at the top of the file) to change the color scheme:

```css
:root {
    --primary-color: #2563eb;  /* Change this to your preferred color */
    --primary-dark: #1e40af;
    /* ... other variables */
}
```

## How to Use

1. Open `index.html` in your web browser
2. For local development, you can use a simple HTTP server:
   - Python: `python -m http.server 8000`
   - Node.js: `npx http-server`
   - Then visit `http://localhost:8000`

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This portfolio template is free to use and modify for personal use.

