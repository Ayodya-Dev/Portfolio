# Professional Portfolio Website

A modern, responsive portfolio website for freelance web developers and mobile app developers. Built with HTML, CSS, and JavaScript.

## Features

- 🎨 **Modern Design**: Clean, professional design with beautiful gradients and animations
- 📱 **Fully Responsive**: Works perfectly on all devices (desktop, tablet, mobile)
- 💰 **Dual Currency**: Toggle between USD and LKR pricing
- 🚀 **Interactive Elements**: Smooth scrolling, hover effects, and animations
- 📝 **Contact Form**: Functional contact form with validation
- 🎯 **Service Showcase**: Highlight your web development and mobile app services
- 💻 **Tech Stack Display**: Showcase your technical skills
- 📊 **Pricing Packages**: Clear pricing structure for different service tiers

## Files Structure

```
Port/
├── index.html          # Main HTML file
├── styles.css          # CSS styling
├── script.js           # JavaScript functionality
├── dc.txt             # Your service details (reference)
└── README.md          # This file
```

## Quick Start

1. **Open the website**: Simply open `index.html` in your web browser
2. **Customize content**: Edit the HTML file to update your information
3. **Modify styling**: Adjust colors, fonts, and layout in `styles.css`
4. **Add functionality**: Enhance features in `script.js`

## Customization Guide

### 1. Personal Information

Update the following in `index.html`:

- **Name and Title**: Change "Portfolio" to your name
- **Contact Details**: Update email, phone, and location
- **Services**: Modify service descriptions to match your offerings
- **Pricing**: Adjust prices in both USD and LKR

### 2. Styling

Modify `styles.css` to change:

- **Colors**: Update the color scheme (primary: #2563eb, accent: #fbbf24)
- **Fonts**: Change font family (currently using Inter from Google Fonts)
- **Layout**: Adjust spacing, padding, and margins
- **Animations**: Modify hover effects and transitions

### 3. Functionality

Enhance `script.js` to add:

- **Form Submission**: Connect contact form to your email service
- **Analytics**: Add Google Analytics or other tracking
- **Portfolio Gallery**: Showcase your previous work
- **Blog Integration**: Add a blog section

## Key Sections

### Hero Section
- Eye-catching introduction with your main value proposition
- Call-to-action buttons
- Technology stack preview

### Services
- Website Development
- Web Applications
- Mobile Apps
- API & Integrations

### Technology Stack
- Frontend: React, Next.js, Tailwind CSS, TypeScript
- Backend: Node.js, Express, PostgreSQL, MongoDB
- Mobile: React Native, Flutter
- Cloud & DevOps: AWS, Vercel, Firebase, Docker

### Pricing Packages
- **Starter Site**: $200+ / 50,000 LKR+
- **Business Website**: $700+ / 70,000 LKR+
- **E-commerce**: $1,000+ / 90,000 LKR
- **Web App (MVP)**: $1,200+ / 100,000 LKR+
- **Mobile App (MVP)**: $1,000+ / 150,000 LKR+

## Browser Compatibility

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers

## Performance Features

- **Optimized Images**: Use WebP format for better performance
- **Minified CSS/JS**: Consider minifying for production
- **Lazy Loading**: Images load as needed
- **Smooth Animations**: Hardware-accelerated CSS transitions

## Deployment Options

### 1. GitHub Pages (Free)
```bash
git init
git add .
git commit -m "Initial portfolio commit"
git branch -M main
git remote add origin https://github.com/username/repository.git
git push -u origin main
```

### 2. Netlify (Free)
- Drag and drop your folder to Netlify
- Get instant HTTPS and custom domain support

### 3. Vercel (Free)
- Connect your GitHub repository
- Automatic deployments on push

### 4. Traditional Hosting
- Upload files via FTP/SFTP
- Configure your domain

## SEO Optimization

The website includes:
- Semantic HTML structure
- Meta tags for social sharing
- Proper heading hierarchy
- Alt text for images
- Fast loading times

## Contact Form Setup

To make the contact form functional:

1. **EmailJS** (Recommended for beginners):
   ```html
   <!-- Add EmailJS script -->
   <script src="https://cdn.jsdelivr.net/npm/@emailjs/browser@3/dist/email.min.js"></script>
   ```

2. **Formspree** (Simple form handling):
   ```html
   <form action="https://formspree.io/f/your-form-id" method="POST">
   ```

3. **Custom Backend**: Build your own API endpoint

## Adding Your Work

### Portfolio Gallery
Add a new section in `index.html`:
```html
<section class="portfolio">
    <div class="container">
        <h2 class="section-title">My Work</h2>
        <div class="portfolio-grid">
            <div class="portfolio-item">
                <img src="project1.jpg" alt="Project 1">
                <div class="portfolio-overlay">
                    <h3>Project Name</h3>
                    <p>Description</p>
                    <a href="#" class="btn">View Project</a>
                </div>
            </div>
        </div>
    </div>
</section>
```

### Testimonials
Add client feedback:
```html
<section class="testimonials">
    <div class="container">
        <h2 class="section-title">What Clients Say</h2>
        <div class="testimonials-grid">
            <div class="testimonial-card">
                <p>"Great work and excellent communication!"</p>
                <h4>Client Name</h4>
                <span>Company</span>
            </div>
        </div>
    </div>
</section>
```

## Maintenance

- **Regular Updates**: Keep your portfolio current with latest projects
- **Performance Monitoring**: Use tools like Lighthouse to check performance
- **Security**: Keep dependencies updated
- **Backup**: Regular backups of your portfolio files

## Support

If you need help customizing your portfolio:

1. Check the code comments for guidance
2. Modify one section at a time
3. Test changes in different browsers
4. Use browser developer tools for debugging

## License

This portfolio template is free to use for personal and commercial projects.

---

**Good luck with your freelance career! 🚀**

Remember to:
- Keep your portfolio updated
- Showcase your best work
- Include clear calls-to-action
- Make it easy for clients to contact you
- Highlight your unique value proposition
