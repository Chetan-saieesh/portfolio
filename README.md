# Portfolio Website - Chetan Saieesh Kola

[personal portfolio website](https://chetan-saieesh.github.io/portfolio/)

A modern, professional personal portfolio website with a sleek black theme, animated typing effects, and responsive design.

## 🌟 Features

- **Dark Theme**: Professional black theme with cyan accents and glow effects
- **Animated Typing Effect**: Dynamic role display (Web Developer, Student, Video Editor)
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Professional Sections**: About Me, Skills (with icons), Education, and Contact
- **Smooth Animations**: Hover effects, transitions, and scroll animations
- **GitHub Pages Ready**: Easy deployment to GitHub Pages

## 📁 File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # Stylesheet with dark theme
├── script.js           # JavaScript for typing animation
├── pp.jpg              # Professional profile image
├── .gitignore          # Git ignore file
├── README.md           # This file
└── DEPLOYMENT.md       # Deployment guide
```

## 🚀 Quick Start

### Local Development

1. Clone or download this repository
2. Open `index.html` in your web browser
3. Or use a local server:
   ```bash
   # Python
   python -m http.server 8000
   
   # Node.js
   npx http-server
   ```
4. Visit `http://localhost:8000`

## 📤 Deployment to GitHub Pages

### Step 1: Push to GitHub

```bash
# Add remote (replace with your GitHub username)
git remote add origin https://github.com/Chetan-saieesh/portfolio.git
git branch -M main
git push -u origin main
```

### Step 2: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** → **Pages**
3. Under **Source**, select:
   - Branch: `main`
   - Folder: `/ (root)`
4. Click **Save**

Your portfolio will be live at: `https://chetan-saieesh.github.io/portfolio/`

For detailed deployment instructions, see [DEPLOYMENT.md](DEPLOYMENT.md)

## 🎨 Customization

### Update Profile Image

Replace `pp.jpg` with your professional photo (recommended: 400x400px or larger, square format)

### Update Contact Information

Edit the contact section in `index.html` - already configured with your details.

### Change Colors

Edit CSS variables in `styles.css`:

```css
:root {
    --primary-color: #00d4ff;  /* Main accent color */
    --accent-color: #ff6b6b;   /* Secondary accent */
    /* ... */
}
```

## 📱 Sections

- **Hero**: Animated introduction with profile image
- **About Me**: Detailed background, skills, and internships
- **Skills**: Technology logos with hover effects
- **Education**: Academic background
- **Contact**: Email, GitHub, and LinkedIn links

## 🛠️ Technologies Used

- HTML5
- CSS3 (with CSS Variables)
- JavaScript (Vanilla JS)
- Font Awesome Icons
- Google Fonts (Inter)

## 📄 License

This portfolio template is free to use and modify for personal use.

## 👤 Author

**Chetan Saieesh Kola**
- Email: saieeshkola03@gmail.com
- GitHub: [@Chetan-saieesh](https://github.com/Chetan-saieesh)
- LinkedIn: [Chetan Saieesh Kola](https://www.linkedin.com/in/chetan-saieesh-kola-6511a6236)

---

⭐ If you like this portfolio, feel free to star the repository!
