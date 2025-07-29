# 🚀 Modern Portfolio Website

A beautiful, responsive, and interactive portfolio website built with vanilla HTML, CSS, and JavaScript. Features a modern design with dark/light theme toggle, smooth animations, and mobile-first responsive design.

## ✨ Features

- **🎨 Modern Design**: Clean, professional design with beautiful gradients and animations
- **🌓 Dark/Light Theme**: Toggle between dark and light themes with system preference detection
- **📱 Fully Responsive**: Optimized for all devices (mobile, tablet, desktop)
- **🎭 Interactive Animations**: Smooth scroll animations, floating elements, and hover effects
- **⚡ Performance Optimized**: Debounced scroll events and optimized animations
- **🍭 Easter Eggs**: Hidden confetti animation (click the logo 5 times!)
- **♿ Accessible**: Semantic HTML and keyboard navigation support
- **🔧 Easy to Customize**: Well-organized code structure for easy modifications

## 🏗️ Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # All styles and responsive design
├── script.js           # Interactive functionality
└── README.md          # This file
```

## 🎯 Sections

1. **Hero Section**: Eye-catching introduction with animated typing effect
2. **About Section**: Personal information with animated statistics
3. **Skills Section**: Technical skills organized by category
4. **Projects Section**: Featured projects with hover effects
5. **Contact Section**: Contact information and working contact form

## 🛠️ Customization Guide

### 1. Personal Information

**Update these placeholders in `index.html`:**

```html
<!-- Replace "Your Name" with your actual name -->
<title>Your Name - Portfolio</title>
<a href="#home">Your Name</a>
<h1>Hi, I'm <span class="highlight">Your Name</span></h1>

<!-- Update contact information -->
<p>your.email@example.com</p>
<p>+1 (555) 123-4567</p>
<p>Your City, Country</p>
```

### 2. About Section

Update the about text and statistics:

```html
<!-- In the about section -->
<p>Your personal description here...</p>

<!-- Update statistics -->
<h3>50+</h3> <!-- Your number of projects -->
<h3>3+</h3>  <!-- Your years of experience -->
<h3>25+</h3> <!-- Your happy clients -->
```

### 3. Skills

Modify the skills in each category:

```html
<!-- Frontend skills -->
<span class="skill-item">Your Skill</span>

<!-- Backend skills -->
<span class="skill-item">Your Backend Skill</span>

<!-- Tools & Others -->
<span class="skill-item">Your Tool</span>
```

### 4. Projects

Update project information:

```html
<h3>Your Project Name</h3>
<p>Your project description...</p>
<div class="project-tech">
    <span>Tech 1</span>
    <span>Tech 2</span>
</div>
```

**Add project links:**
```html
<a href="https://your-live-demo.com" class="project-link">
<a href="https://github.com/yourusername/project" class="project-link">
```

### 5. Social Links

Update social media links:

```html
<a href="https://github.com/yourusername" class="social-link">
<a href="https://linkedin.com/in/yourusername" class="social-link">
<a href="https://twitter.com/yourusername" class="social-link">
```

### 6. Colors and Styling

Customize the color scheme in `styles.css`:

```css
:root {
    --primary-color: #6366f1;      /* Main brand color */
    --secondary-color: #f59e0b;    /* Accent color */
    --gradient-primary: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
}
```

## 🖼️ Adding Images

To add your profile photo:

1. Add your image file to the project folder
2. Update the CSS for `.profile-img::before`:

```css
.profile-img::before {
    background-image: url('your-photo.jpg');
    background-size: cover;
    background-position: center;
}
```

For project images:

```css
.project-card:nth-child(1) .project-image {
    background-image: url('project1-image.jpg');
    background-size: cover;
    background-position: center;
}
```

## 📧 Contact Form

The contact form currently shows a demo submission. To make it functional:

1. **Using Netlify Forms** (easiest):
   ```html
   <form class="contact-form" netlify>
   ```

2. **Using Formspree**:
   ```html
   <form class="contact-form" action="https://formspree.io/f/your-form-id" method="POST">
   ```

3. **Custom Backend**: Replace the form submission handler in `script.js`

## 🚀 Deployment

### GitHub Pages
1. Push your code to a GitHub repository
2. Go to Settings > Pages
3. Select source branch (main/master)
4. Your site will be available at `https://yourusername.github.io/repository-name`

### Netlify
1. Connect your GitHub repository to Netlify
2. Deploy automatically on every push
3. Get a custom domain

### Vercel
1. Import your GitHub repository
2. Deploy with zero configuration
3. Automatic deployments

## 🔧 Browser Support

- ✅ Chrome 60+
- ✅ Firefox 60+
- ✅ Safari 12+
- ✅ Edge 79+

## 📱 Mobile Optimization

The portfolio is built with a mobile-first approach and includes:

- Responsive navigation with hamburger menu
- Touch-friendly button sizes
- Optimized images and animations
- Fast loading on slower connections

## 🎨 Design Credits

- **Fonts**: Inter from Google Fonts
- **Icons**: Font Awesome
- **Color Palette**: Modern gradient combinations
- **Animations**: Custom CSS animations with smooth transitions

## 🤝 Contributing

Feel free to fork this project and make it your own! If you create something cool, I'd love to see it.

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 💡 Tips

1. **Keep it updated**: Regularly update your projects and skills
2. **Optimize images**: Use WebP format for better performance
3. **Test on devices**: Check how it looks on different screen sizes
4. **SEO optimization**: Update meta tags for better search visibility
5. **Analytics**: Add Google Analytics to track visitors

---

**Made with ❤️ and lots of coffee** ☕

Happy coding! 🎉
