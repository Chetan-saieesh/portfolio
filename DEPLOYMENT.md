# Deployment Guide

## Step 1: Create GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the "+" icon in the top right corner
3. Select "New repository"
4. Name it: `portfolio` (or any name you prefer)
5. **DO NOT** initialize with README, .gitignore, or license (we already have these)
6. Click "Create repository"

## Step 2: Connect Local Repository to GitHub

After creating the repository on GitHub, run these commands:

```bash
git remote add origin https://github.com/Chetan-saieesh/portfolio.git
git branch -M main
git push -u origin main
```

**Note:** Replace `Chetan-saieesh/portfolio` with your actual GitHub username and repository name if different.

## Step 3: Deploy to GitHub Pages

### Option A: Using GitHub Website (Easiest)

1. Go to your repository on GitHub
2. Click on **Settings** (top menu)
3. Scroll down to **Pages** in the left sidebar
4. Under **Source**, select:
   - Branch: `main`
   - Folder: `/ (root)`
5. Click **Save**
6. Wait a few minutes for GitHub to build your site
7. Your portfolio will be live at: `https://chetan-saieesh.github.io/portfolio/`

### Option B: Using GitHub CLI (if installed)

```bash
gh repo create portfolio --public
git push -u origin main
gh pages --branch main --source .
```

## Step 4: Custom Domain (Optional)

If you want to use a custom domain:

1. In GitHub Pages settings, add your custom domain
2. Update your domain's DNS settings to point to GitHub Pages
3. GitHub will provide the exact DNS records needed

## Updating Your Portfolio

Whenever you make changes:

```bash
git add .
git commit -m "Description of changes"
git push
```

GitHub Pages will automatically update your live site within a few minutes.

## Troubleshooting

- **Site not loading?** Wait 5-10 minutes after first deployment
- **Changes not showing?** Clear your browser cache or wait a few minutes
- **404 Error?** Make sure `index.html` is in the root directory
- **Images not showing?** Check that image paths are correct and files are committed

## Your Live Portfolio URL

Once deployed, your portfolio will be available at:
`https://chetan-saieesh.github.io/portfolio/`

(Replace `chetan-saieesh` with your GitHub username and `portfolio` with your repository name)

