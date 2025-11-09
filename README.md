# Chris Clark - Portfolio Website

A modern, professional portfolio website showcasing software engineering experience, projects, and skills.

## Features

- 🎨 Clean, modern design with smooth animations
- 📱 Fully responsive (mobile, tablet, desktop)
- 🚀 Fast loading and performance optimized
- 🎯 SEO-friendly structure
- ⚡ No build process required - pure HTML/CSS/JS
- 🌐 Easy deployment to GitHub Pages, Netlify, or Vercel

## Quick Start

1. **Clone or Download** this repository
2. **Customize** your information (see below)
3. **Deploy** to your preferred hosting platform

## Customization Guide

### 1. Update Personal Information

**In `index.html`:**

- Line 8: Update the `<title>` tag
- Line 7: Update the `<meta name="description">` tag
- Hero section (lines 35-60): Update name, title, and description
- Contact section (lines 450-470): Add your email, LinkedIn, and GitHub URLs

### 2. Modify Content

**Projects Section:**
- Add/remove project cards in the `#projects` section
- Each project card includes:
  - Title and description
  - Key features list
  - Technology tags
  - Impact statement

**Experience Section:**
- Update or add timeline items in the `#experience` section
- Include company, role, dates, and accomplishments

**Skills Section:**
- Modify skill categories and tags in the `#skills` section

**Education & Certifications:**
- Update degrees and certifications in the `#education` section

### 3. Customize Colors

**In `styles.css` (lines 13-25):**
```css
:root {
    --primary-color: #2563eb;      /* Main brand color */
    --secondary-color: #0ea5e9;    /* Accent color */
    --accent-color: #10b981;       /* Success/highlight color */
    /* ... other color variables */
}
```

### 4. Add Your Photo (Optional)

Add an image to the About section:
```html
<div class="about-image">
    <img src="your-photo.jpg" alt="Chris Clark">
</div>
```

## Deployment Options

### Option 1: GitHub Pages (Free)

1. Create a new repository named `yourusername.github.io`
2. Push your files to the repository
3. Go to Settings → Pages
4. Select "Deploy from a branch" and choose `main` branch
5. Your site will be live at `https://yourusername.github.io`

### Option 2: Netlify (Free)

1. Create an account at [netlify.com](https://netlify.com)
2. Drag and drop your project folder to Netlify
3. Your site will be live instantly
4. Optional: Add a custom domain

### Option 3: Vercel (Free)

1. Create an account at [vercel.com](https://vercel.com)
2. Import your GitHub repository or drag and drop files
3. Deploy with zero configuration
4. Your site will be live in seconds

### Option 4: Traditional Web Hosting

Upload all files via FTP to your web host:
- index.html
- styles.css
- script.js
- Any images you've added

## File Structure

```
portfolio/
│
├── index.html          # Main HTML structure
├── styles.css          # All styling
├── script.js           # Interactive features
└── README.md          # This file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Performance Tips

1. **Optimize Images**: Compress any photos you add using tools like TinyPNG
2. **Use WebP Format**: Convert images to WebP for better performance
3. **Enable Caching**: Configure your hosting to cache static assets
4. **Consider a CDN**: Use Cloudflare or similar for global performance

## Customization Ideas

### Add a Blog Section
- Create a `blog/` directory with individual post HTML files
- Add navigation link to blog section
- Use a static site generator like Jekyll if you want more blog features

### Add Project Screenshots
- Create an `images/` directory
- Add screenshots of your projects
- Include them in the project cards

### Add Testimonials/Recommendations
- Create a new section after Projects
- Include quotes from colleagues or managers
- Add LinkedIn recommendation links

### Add a Contact Form
- Use services like Formspree, FormSubmit, or Netlify Forms
- Add a form in the Contact section
- No backend required!

### Analytics
- Add Google Analytics or Plausible Analytics
- Track visitor behavior and popular sections
- Paste tracking code before closing `</head>` tag

## SEO Optimization

Already included:
- ✅ Semantic HTML5 structure
- ✅ Meta description tag
- ✅ Proper heading hierarchy
- ✅ Alt text ready for images

To improve further:
1. Add Open Graph meta tags for social media
2. Create a `sitemap.xml` file
3. Add `robots.txt` file
4. Submit to Google Search Console

## Updating Content

To update your portfolio:
1. Edit the HTML files
2. Test locally by opening `index.html` in a browser
3. Commit and push changes (if using GitHub)
4. Changes will deploy automatically (GitHub Pages/Netlify/Vercel)

## Need Help?

Common issues:

**Navigation not working on mobile?**
- Check that `script.js` is loading properly
- Verify the hamburger menu event listener

**Sections not aligned properly?**
- Check the `margin-top` on the first section to account for fixed navbar
- Adjust padding in `.section` class

**Colors not updating?**
- Make sure you're editing the CSS variables in `:root`
- Clear browser cache (Ctrl+Shift+R or Cmd+Shift+R)

## Credits

- Font: Inter from Google Fonts
- Icons: Unicode emoji (no external dependencies)
- Design: Custom built for software engineering portfolios

## License

This template is free to use for your personal portfolio. Feel free to modify and customize as needed.

---

**Built by Chris Clark** | Last Updated: November 2025
