# Personal Portfolio Website

A modern, responsive portfolio website with a dark theme featuring beautiful purple-to-pink gradients. This portfolio includes four main pages: Home, About, Contact Info, and Photos.

## Features

- 🎨 Modern dark theme with gradient accents
- 📱 Fully responsive design
- ✨ Smooth animations and transitions
- 🌟 Interactive elements and hover effects
- 🎯 Clean and professional layout
- 🚀 Fast and lightweight

## Pages

1. **Home** (`index.html`) - Hero section with introduction and call-to-action buttons
2. **About** (`about.html`) - Personal information, skills, and interests
3. **Contact Info** (`contact.html`) - Contact details and message form
4. **Photos** (`photos.html`) - Photo gallery showcasing projects and work

## Customization

Before deploying, make sure to customize:

1. **Personal Information:**
   - Replace "Your Name" with your actual name in all HTML files
   - Update the email address in `contact.html`
   - Add your social media links in `contact.html`
   - Replace placeholder images in `photos.html`

2. **Content:**
   - Update the about section with your personal information
   - Modify skills and interests to match your expertise
   - Add your actual photos/projects to the gallery

3. **Styling:**
   - Colors and gradients can be customized in `styles.css` under `:root` variables
   - Fonts can be changed by updating the Google Fonts link in HTML files

## How to Deploy to GitHub Pages

Follow these steps to push your portfolio to GitHub and make it live:

### Step 1: Create a GitHub Account
If you don't have one, go to [github.com](https://github.com) and sign up.

### Step 2: Create a New Repository

1. Click the "+" icon in the top right corner of GitHub
2. Select "New repository"
3. Name your repository (e.g., `portfolio` or `yourname-portfolio`)
4. Make it **Public** (required for free GitHub Pages)
5. **DO NOT** initialize with README, .gitignore, or license (we already have files)
6. Click "Create repository"

### Step 3: Initialize Git in Your Project

Open your terminal/command prompt in the project folder and run:

```bash
# Initialize git repository
git init

# Add all files
git add .

# Create your first commit
git commit -m "Initial commit: Portfolio website"
```

### Step 4: Connect to GitHub and Push

```bash
# Add your GitHub repository as remote (replace YOUR_USERNAME and YOUR_REPO_NAME)
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git

# Rename your branch to main (if needed)
git branch -M main

# Push your code to GitHub
git push -u origin main
```

**Note:** You'll be prompted to enter your GitHub username and password (or personal access token).

### Step 5: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on **Settings** (top menu)
3. Scroll down to **Pages** in the left sidebar
4. Under **Source**, select **Deploy from a branch**
5. Choose **main** branch and **/ (root)** folder
6. Click **Save**

### Step 6: Access Your Live Website

GitHub will provide you with a URL like:
```
https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/
```

It may take a few minutes for your site to be live. You'll see a green checkmark when it's ready!

## Updating Your Portfolio

Whenever you make changes to your portfolio:

```bash
# Add your changes
git add .

# Commit with a message
git commit -m "Update portfolio content"

# Push to GitHub
git push
```

Your changes will be live on GitHub Pages within a few minutes.

## Local Development

To view your portfolio locally:

1. Simply open `index.html` in your web browser, OR
2. Use a local server (recommended):
   - **VS Code**: Install "Live Server" extension and click "Go Live"
   - **Python**: Run `python -m http.server 8000` and visit `http://localhost:8000`
   - **Node.js**: Install `http-server` with `npm install -g http-server` and run `http-server`

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is open source and available for personal use.

---

**Need Help?** If you encounter any issues, check GitHub's documentation or feel free to reach out!

