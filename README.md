# Ali Jamal - Personal Portfolio Website

A modern, responsive personal portfolio website built for GitHub Pages.

## 🚀 Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations
- **Interactive Elements**: Smooth scrolling, mobile navigation, contact form
- **GitHub Pages Ready**: Optimized for deployment on GitHub Pages
- **SEO Friendly**: Proper meta tags and semantic HTML structure

## 📁 Project Structure

```
alijamal14.github.io/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript for interactivity
└── README.md           # This file
```

## 🎨 Sections

1. **Hero Section**: Introduction with your name and role
2. **About**: Personal description and key statistics
3. **Skills**: Technical skills organized by category
4. **Experience**: Timeline of work experience and projects
5. **Contact**: Contact information and contact form

## 🛠️ Customization

### Personal Information
Update the following in `index.html`:

- **Name**: Replace "Ali Jamal" with your name
- **Title**: Update "Software Developer & Technology Enthusiast"
- **Email**: Change "alijamal14@live.com" to your email
- **LinkedIn**: Update the LinkedIn URL
- **GitHub**: Update the GitHub URL

### Skills Section
Modify the skills in the Skills section:

```html
<div class="skill-category">
    <h3>Frontend</h3>
    <div class="skill-items">
        <span class="skill-item">Your Skill</span>
        <!-- Add more skills -->
    </div>
</div>
```

### Experience Timeline
Update the experience section with your actual work history:

```html
<div class="timeline-item">
    <div class="timeline-marker"></div>
    <div class="timeline-content">
        <h3>Your Job Title</h3>
        <h4>Company Name</h4>
        <span class="timeline-date">Start - End Date</span>
        <p>Description of your role and achievements</p>
    </div>
</div>
```

### Colors and Styling
Main color variables are defined in `styles.css`. Key colors:

- Primary Blue: `#2563eb`
- Accent Gold: `#fbbf24`
- Text Gray: `#6b7280`
- Background: `#f9fafb`

## 🚀 Deployment to GitHub Pages

1. **Push to GitHub**: Make sure all files are committed and pushed to your repository
2. **Enable GitHub Pages**:
   - Go to your repository settings
   - Scroll down to "Pages" section
   - Select "Deploy from a branch"
   - Choose "main" branch and "/ (root)"
   - Click "Save"

3. **Access Your Site**: Your website will be available at `https://alijamal14.github.io`

## 📱 Mobile Responsiveness

The website is fully responsive with:
- Mobile-first design approach
- Hamburger menu for mobile navigation
- Optimized layouts for all screen sizes
- Touch-friendly interactive elements

## ✨ Interactive Features

- **Smooth Scrolling**: Navigation links smoothly scroll to sections
- **Mobile Menu**: Animated hamburger menu for mobile devices
- **Contact Form**: Functional contact form with validation
- **Scroll Animations**: Elements animate as they come into view
- **Typing Effect**: Animated typing effect on the hero title

## 🔧 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📝 Contact Form

The contact form includes client-side validation and displays success/error messages. To add backend functionality:

1. Choose a form service (Netlify Forms, Formspree, etc.)
2. Update the form action in `index.html`
3. Modify the JavaScript in `script.js` if needed

## 🎯 SEO Optimization

The website includes:
- Semantic HTML structure
- Meta descriptions
- Proper heading hierarchy
- Alt text for images (when added)
- Fast loading times

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to fork this project and customize it for your own use. If you find any bugs or have suggestions for improvements, please open an issue.

---

**Happy coding!** 🎉
