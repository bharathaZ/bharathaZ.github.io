# Personal Website & CV

A modern, responsive personal website template with CV sections that can be easily customized and hosted.

## Features

- 🎨 Modern, professional design
- 📱 Fully responsive (mobile-friendly)
- ⚡ Fast loading with optimized code
- 🎯 SEO-friendly structure
- 🌟 Smooth animations and interactions
- 📄 Complete CV sections (Experience, Education, Skills)
- 📞 Contact information and social links
- 🚀 Easy to customize and deploy

## Sections Included

1. **Hero Section** - Introduction and call-to-action
2. **About** - Personal description and key statistics
3. **Experience** - Work history with timeline layout
4. **Education** - Academic background and certifications
5. **Skills** - Technical skills organized by category
6. **Contact** - Contact information and social media links

## Customization Guide

### 1. Personal Information

Update the following in `index.html`:

- **Name**: Replace "Your Name" throughout the file
- **Title/Role**: Update the hero subtitle
- **Description**: Modify the about section text
- **Contact Details**: Update email, phone, and location
- **Social Links**: Add your actual social media URLs

### 2. Experience Section

Edit the experience timeline in `index.html`:

```html
<div class="timeline-item">
    <div class="timeline-content">
        <div class="timeline-header">
            <h3>Your Job Title</h3>
            <span class="company">Company Name</span>
            <span class="date">Year - Year</span>
        </div>
        <p>Job description...</p>
        <ul>
            <li>Achievement 1</li>
            <li>Achievement 2</li>
        </ul>
    </div>
</div>
```

### 3. Education Section

Update your education details:

```html
<div class="education-card">
    <div class="education-header">
        <h3>Your Degree</h3>
        <span class="institution">University Name</span>
        <span class="date">Year - Year</span>
    </div>
    <p>Description of your education...</p>
    <div class="achievements">
        <span class="achievement">GPA: X.X</span>
        <span class="achievement">Honor/Award</span>
    </div>
</div>
```

### 4. Skills Section

Modify the skills in each category:

```html
<div class="skill-category">
    <h3>Category Name</h3>
    <div class="skill-items">
        <span class="skill-item">Skill 1</span>
        <span class="skill-item">Skill 2</span>
    </div>
</div>
```

### 5. Styling Customization

Edit `styles.css` to change:

- **Colors**: Update the color scheme (primary color is `#2563eb`)
- **Fonts**: Change the font family (currently using Inter)
- **Layout**: Modify spacing and sizing
- **Animations**: Adjust transition effects

## Hosting Options

### 1. GitHub Pages (Free)

1. Create a GitHub repository
2. Upload your website files
3. Go to Settings > Pages
4. Select source branch (usually `main`)
5. Your site will be available at `https://username.github.io/repository-name`

### 2. Netlify (Free)

1. Sign up at [netlify.com](https://netlify.com)
2. Drag and drop your website folder
3. Get a custom URL instantly
4. Optionally connect a custom domain

### 3. Vercel (Free)

1. Sign up at [vercel.com](https://vercel.com)
2. Connect your GitHub repository
3. Deploy automatically on every push
4. Get a custom URL and domain options

### 4. Traditional Web Hosting

Upload files to any web hosting service:
- cPanel hosting
- AWS S3 + CloudFront
- Google Cloud Storage
- Any static file hosting

## File Structure

```
your-website/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance Tips

1. **Optimize Images**: Use WebP format and compress images
2. **Minify CSS/JS**: Use tools like UglifyJS and CSSNano
3. **Enable Gzip**: Configure server compression
4. **Use CDN**: Host fonts and icons on CDN (already implemented)
5. **Lazy Loading**: Consider adding lazy loading for images

## SEO Optimization

The website includes:
- Semantic HTML structure
- Meta tags for social sharing
- Proper heading hierarchy
- Alt text for images
- Fast loading times

## Customization Examples

### Change Color Scheme

In `styles.css`, update the primary color:

```css
:root {
    --primary-color: #your-color;
    --secondary-color: #your-secondary-color;
}
```

### Add More Sections

Create new sections following the existing pattern:

```html
<section id="projects" class="projects">
    <div class="container">
        <h2 class="section-title">Projects</h2>
        <!-- Your content here -->
    </div>
</section>
```

### Add a Blog Section

Create a blog page and link it in the navigation:

```html
<li><a href="blog.html" class="nav-link">Blog</a></li>
```

## Support

For questions or issues:
1. Check the code comments for guidance
2. Review browser console for errors
3. Test on different devices and browsers
4. Validate HTML/CSS using online validators

## License

This template is free to use for personal and commercial projects.

---

**Happy coding!** 🚀 