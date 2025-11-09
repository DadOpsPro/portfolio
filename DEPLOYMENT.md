# Quick Deployment Guide

## Deploy to GitHub Pages (5 minutes)

### Step 1: Create GitHub Repository

```bash
# Initialize git repository
git init

# Add all files
git add .

# Commit files
git commit -m "Initial commit: Portfolio website"

# Create a new repository on GitHub named 'yourusername.github.io'
# Then connect your local repository:
git remote add origin https://github.com/yourusername/yourusername.github.io.git

# Push to GitHub
git push -u origin main
```

### Step 2: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** → **Pages**
3. Under "Source", select **Deploy from a branch**
4. Choose **main** branch and **/ (root)** folder
5. Click **Save**

Your site will be live at: `https://yourusername.github.io`

## Deploy to Netlify (2 minutes)

### Option A: Drag and Drop
1. Go to [app.netlify.com](https://app.netlify.com)
2. Sign up or log in
3. Drag your portfolio folder onto the page
4. Done! Your site is live

### Option B: GitHub Integration
1. Push your code to GitHub (see above)
2. Go to Netlify and click "New site from Git"
3. Connect your GitHub repository
4. Click "Deploy site"
5. Netlify will automatically deploy and give you a URL

### Custom Domain (Optional)
- In Netlify: Domain settings → Add custom domain
- Update your DNS records as instructed

## Deploy to Vercel (2 minutes)

1. Push your code to GitHub (see Step 1 above)
2. Go to [vercel.com](https://vercel.com)
3. Sign up with GitHub
4. Click "New Project"
5. Import your repository
6. Click "Deploy"

Your site will be live instantly with a vercel.app URL.

## Pre-Deployment Checklist

Before deploying, make sure you've:

- [ ] Updated your name and title in `index.html`
- [ ] Added your email, LinkedIn, and GitHub links
- [ ] Updated the project descriptions with your actual projects
- [ ] Modified the experience section with your details
- [ ] Customized the skills section
- [ ] Added your education and certifications
- [ ] Tested the site locally (open index.html in browser)
- [ ] Checked mobile responsiveness (resize browser window)
- [ ] Added any images (and updated image paths)

## After Deployment

### Add to your resume:
```
Portfolio: https://yourusername.github.io
```

### Share on LinkedIn:
1. Update your LinkedIn profile with portfolio link
2. Make a post announcing your new portfolio
3. Tag it with #Portfolio #WebDevelopment #SoftwareEngineering

### Submit to job applications:
Include your portfolio URL in:
- Resume header
- Email signature
- Job application "portfolio" field
- Cover letters

## Troubleshooting

**Site not loading?**
- Wait 5-10 minutes for GitHub Pages to build
- Check that index.html is in the root directory
- Verify branch and folder settings in GitHub Pages

**Links not working?**
- Make sure all href links use relative paths
- Check that anchor links include the # symbol

**Images not showing?**
- Verify image paths are correct
- Make sure images are committed to the repository
- Use relative paths (e.g., `./images/photo.jpg`)

**Mobile menu not working?**
- Verify script.js is loading
- Check browser console for JavaScript errors

## Updating Your Portfolio

When you make changes:

```bash
# Add your changes
git add .

# Commit with a message
git commit -m "Updated projects section"

# Push to GitHub
git push

# GitHub Pages/Netlify/Vercel will automatically redeploy
```

## Analytics (Optional)

### Google Analytics
Add this before `</head>` in index.html:
```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

Replace `GA_MEASUREMENT_ID` with your actual ID from Google Analytics.

## Need More Help?

Resources:
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Netlify Documentation](https://docs.netlify.com/)
- [Vercel Documentation](https://vercel.com/docs)
- [Web Dev Simplified YouTube Channel](https://www.youtube.com/c/WebDevSimplified)

---

Good luck with your job search! 🚀
