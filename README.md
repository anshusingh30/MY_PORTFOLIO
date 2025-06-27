# 🚀 Shagun Verma - Personal Portfolio Website

A modern, professional, and visually appealing personal portfolio website built with HTML, CSS, and JavaScript. Perfect for showcasing your skills, projects, and professional presence as a final-year BTech CSE student.

## ✨ Features

- **Modern Design**: Clean, minimalistic, and elegant design with smooth animations
- **Responsive Layout**: Fully responsive design that works on all devices
- **Interactive Elements**: Smooth scrolling, hover effects, and dynamic content
- **Professional Sections**: Hero, About, Skills, Projects, Certifications, Education, Contact
- **Mobile-First**: Optimized for mobile devices with touch-friendly navigation
- **Performance Optimized**: Fast loading with lazy loading and optimized assets
- **Accessibility**: WCAG compliant with keyboard navigation support

## 🎨 Design Theme

- **Primary Colors**: #1F2937 (Dark Blue-Grey), #3B82F6 (Vibrant Blue), #F9FAFB (Light Grey-White)
- **Font**: Inter (Modern, clean typography)
- **Layout**: One-page scrollable with smooth navigation
- **Animations**: Subtle hover effects and scroll-triggered animations

## 📁 File Structure

```
my_portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript functionality
├── README.md           # This file
├── assets/             # Images, icons, and other assets
│   ├── resume.pdf      # Your resume (add your file here)
│   └── favicon.ico     # Website favicon
└── .gitignore          # Git ignore file
```

## 🚀 Quick Start

1. **Clone or Download** the portfolio files to your local machine
2. **Open `index.html`** in your web browser to view the portfolio
3. **Customize** the content by editing the HTML file
4. **Deploy** to your preferred hosting platform

## 🛠️ Customization Guide

### 1. Personal Information

Edit the following sections in `index.html`:

#### Hero Section
```html
<!-- Update your name and title -->
<h1 class="hero-title">
    Hi, I'm <span class="highlight">Shagun Verma</span> 👋
</h1>
<p class="hero-subtitle">
    Final-Year BTech CSE Student | Future Full-Stack Developer | Coding Enthusiast
</p>

<!-- Update your social links -->
<a href="https://github.com/yourusername" target="_blank" class="btn btn-secondary">
    <i class="fab fa-github"></i> View GitHub
</a>
<a href="https://linkedin.com/in/yourusername" target="_blank" class="btn btn-secondary">
    <i class="fab fa-linkedin"></i> Connect on LinkedIn
</a>
```

#### About Section
```html
<!-- Update your personal description -->
<p>
    I am a passionate final-year BTech Computer Science and Engineering student...
</p>
```

### 2. Skills Section

Update your skills in the skills section:

```html
<!-- Programming Languages -->
<div class="skill-item">
    <span class="skill-name">C++</span>
    <div class="skill-bar">
        <div class="skill-progress" style="width: 90%"></div>
    </div>
</div>

<!-- Add more skills as needed -->
```

### 3. Projects Section

Replace the sample projects with your own:

```html
<div class="project-card">
    <div class="project-image">
        <i class="fas fa-shopping-cart"></i>
    </div>
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Your project description here...</p>
        <div class="project-tech">
            <span class="tech-tag">React</span>
            <span class="tech-tag">Node.js</span>
        </div>
        <div class="project-links">
            <a href="https://github.com/yourusername/project" target="_blank" class="project-link">
                <i class="fab fa-github"></i> Code
            </a>
            <a href="#" class="project-link">
                <i class="fas fa-external-link-alt"></i> Live Demo
            </a>
        </div>
    </div>
</div>
```

### 4. Certifications & Internships

Update with your actual certifications:

```html
<div class="certification-card">
    <div class="certification-icon">
        <i class="fab fa-react"></i>
    </div>
    <div class="certification-content">
        <h3>Your Certification Name</h3>
        <p class="certification-issuer">Issuer Name</p>
        <p class="certification-date">Date</p>
    </div>
</div>
```

### 5. Education

Update your educational background:

```html
<div class="education-item">
    <div class="education-icon">
        <i class="fas fa-graduation-cap"></i>
    </div>
    <div class="education-content">
        <h3>BTech Computer Science and Engineering</h3>
        <p class="education-institution">Your College Name</p>
        <p class="education-duration">2021 - 2025</p>
        <p class="education-description">CGPA: 8.5/10 | Relevant Coursework: Data Structures, Algorithms...</p>
    </div>
</div>
```

### 6. Contact Information

Update your contact details:

```html
<div class="contact-item">
    <i class="fas fa-envelope"></i>
    <a href="mailto:your.email@example.com">your.email@example.com</a>
</div>
<div class="contact-item">
    <i class="fab fa-linkedin"></i>
    <a href="https://linkedin.com/in/yourusername" target="_blank">LinkedIn Profile</a>
</div>
<div class="contact-item">
    <i class="fab fa-github"></i>
    <a href="https://github.com/yourusername" target="_blank">GitHub Profile</a>
</div>
```

## 🎨 Customizing Colors and Theme

Edit the CSS variables in `styles.css`:

```css
:root {
    /* Primary Colors - Change these to match your brand */
    --primary-color: #1F2937;        /* Dark Blue-Grey */
    --secondary-color: #3B82F6;      /* Vibrant Blue */
    --accent-color: #60A5FA;         /* Light Blue */
    
    /* Text Colors */
    --text-primary: #1F2937;         /* Dark text */
    --text-secondary: #6B7280;       /* Grey text */
    --text-light: #F9FAFB;           /* Light text */
    
    /* Background Colors */
    --background-light: #F9FAFB;     /* Light background */
    --background-dark: #111827;      /* Dark background */
    
    /* Other Colors */
    --border-color: #E5E7EB;         /* Border color */
    --shadow-color: rgba(0, 0, 0, 0.1); /* Shadow color */
}
```

## 📱 Adding Your Profile Photo

1. Add your profile photo to the `assets/` folder
2. Update the hero section in `index.html`:

```html
<!-- Replace the icon with your photo -->
<div class="profile-avatar">
    <img src="assets/your-photo.jpg" alt="Shagun Verma" class="profile-photo">
</div>
```

3. Uncomment and update the CSS for profile photo in `styles.css`:

```css
.profile-photo {
    width: 120px;
    height: 120px;
    border-radius: 50%;
    object-fit: cover;
    border: 4px solid var(--secondary-color);
}
```

## 📄 Adding Your Resume

1. Add your resume PDF to the `assets/` folder
2. Update the resume link in `index.html`:

```html
<a href="assets/your-resume.pdf" target="_blank" class="btn btn-primary">
    <i class="fas fa-download"></i> Download Resume
</a>
```

## 🌐 Deployment Options

### GitHub Pages (Free)
1. Create a new repository on GitHub
2. Upload your portfolio files
3. Go to Settings > Pages
4. Select source branch (usually `main`)
5. Your site will be available at `https://yourusername.github.io/repository-name`

### Netlify (Free)
1. Sign up for Netlify
2. Drag and drop your portfolio folder
3. Your site will be deployed instantly
4. You can add a custom domain later

### Vercel (Free)
1. Sign up for Vercel
2. Connect your GitHub repository
3. Deploy automatically on every push

### Traditional Hosting
Upload the files to any web hosting service via FTP or file manager.

## 🔧 Advanced Customization

### Adding New Sections

1. Add the HTML structure in `index.html`
2. Add corresponding CSS styles in `styles.css`
3. Add navigation link in the navbar
4. Add scroll functionality in `script.js`

### Custom Animations

Add custom CSS animations:

```css
@keyframes yourAnimation {
    0% { opacity: 0; transform: translateY(20px); }
    100% { opacity: 1; transform: translateY(0); }
}

.your-element {
    animation: yourAnimation 0.6s ease-out;
}
```

### Adding a Blog Section

1. Create a new HTML file for blog posts
2. Add navigation links
3. Style the blog layout
4. Consider using a static site generator for larger blogs

## 📊 SEO Optimization

Add meta tags to improve search engine visibility:

```html
<head>
    <meta name="description" content="Shagun Verma - Final-Year BTech CSE Student | Full-Stack Developer | Portfolio">
    <meta name="keywords" content="Shagun Verma, Portfolio, Full-Stack Developer, BTech CSE, React, Node.js">
    <meta name="author" content="Shagun Verma">
    <meta property="og:title" content="Shagun Verma - Portfolio">
    <meta property="og:description" content="Final-Year BTech CSE Student | Full-Stack Developer">
    <meta property="og:image" content="assets/your-photo.jpg">
    <meta property="og:url" content="https://yourwebsite.com">
</head>
```

## 🔍 Analytics Integration

Add Google Analytics to track visitors:

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

## 🐛 Troubleshooting

### Common Issues

1. **Images not loading**: Check file paths and ensure images are in the correct folder
2. **Fonts not loading**: Ensure internet connection for Google Fonts
3. **Animations not working**: Check if JavaScript is enabled
4. **Mobile menu not working**: Ensure all JavaScript files are loaded

### Browser Compatibility

- Chrome/Edge: Full support
- Firefox: Full support
- Safari: Full support
- Internet Explorer: Limited support (not recommended)

## 📞 Support

If you need help customizing your portfolio:

1. Check the comments in the code files
2. Review this README for guidance
3. Look at the CSS variables for easy customization
4. Test on different devices and browsers

## 📄 License

This portfolio template is free to use for personal and commercial projects. Attribution is appreciated but not required.

## 🙏 Credits

- **Fonts**: Google Fonts (Inter)
- **Icons**: Font Awesome
- **Design Inspiration**: Modern web design principles
- **Animations**: CSS3 and JavaScript

---

**Made with ❤ by Shagun Verma**

Feel free to customize this portfolio to match your personal brand and style. Good luck with your career journey! 🚀 