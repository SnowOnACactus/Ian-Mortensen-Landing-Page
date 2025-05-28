# Ian Mortensen - Professional Landing Page

A modern, responsive landing page showcasing Ian Mortensen's skills as a project manager and AI-powered developer. This page highlights his portfolio of web applications and demonstrates his expertise in human-AI collaboration.

## 🌟 Features

### Design & UX
- **Modern, Professional Design**: Clean and contemporary aesthetic with a focus on readability and user experience
- **Mobile-First Responsive**: Optimized for all devices from mobile phones to desktop computers
- **Smooth Animations**: Subtle animations and transitions that enhance the user experience
- **Accessibility Focused**: WCAG compliant with proper focus states, semantic HTML, and keyboard navigation

### Interactive Elements
- **Smooth Scrolling Navigation**: Seamless navigation between sections
- **Animated Project Previews**: Visual representations of each project with hover effects
- **Typing Animation**: Dynamic hero title with typewriter effect
- **Scroll Progress Indicator**: Visual feedback showing page scroll progress
- **Mobile Navigation**: Hamburger menu for mobile devices

### Technical Highlights
- **Pure HTML/CSS/JavaScript**: No frameworks required, lightweight and fast
- **CSS Custom Properties**: Consistent design system with easy customization
- **Intersection Observer**: Performance-optimized scroll animations
- **Progressive Enhancement**: Works without JavaScript, enhanced with it

## 🚀 Quick Start

1. **Clone or Download** the files to your local machine
2. **Update Content**: Customize the content in `index.html` to match your information
3. **Add Your Resume**: Replace `CV - Ian Mortensen - 2025.pdf` with your actual resume
4. **Update Project Links**: Add your actual GitHub Pages URLs to the project cards
5. **Deploy**: Upload to your hosting provider or GitHub Pages

## 📁 File Structure

```
landing-page/
├── index.html          # Main HTML file
├── styles.css          # All CSS styles and responsive design
├── script.js           # Interactive functionality
├── README.md           # This documentation
└── CV - Ian Mortensen - 2025.pdf  # Resume file
```

## 🎨 Customization

### Colors
The color scheme is defined using CSS custom properties in `styles.css`. Update these variables to match your brand:

```css
:root {
    --primary-color: #2563eb;      /* Main brand color */
    --primary-dark: #1d4ed8;       /* Darker shade for hovers */
    --accent-color: #f59e0b;       /* Accent color for highlights */
    --text-primary: #1e293b;       /* Main text color */
    --text-secondary: #64748b;     /* Secondary text color */
}
```

### Content Sections

#### Hero Section
Update the main headline and description in the hero section:
- Change the title to reflect your role and expertise
- Update the subtitle to describe your unique value proposition
- Modify the call-to-action buttons as needed

#### About Section
Customize the about content to reflect your background:
- Update the lead paragraph with your professional summary
- Modify the highlight items to showcase your key strengths
- Add or remove highlight cards as needed

#### Projects Section
For each project card:
1. Update the project title and description
2. Modify the technology tags to match your tech stack
3. Replace the placeholder links with actual URLs
4. Customize the visual previews to represent your projects

#### Skills Section
Update the three skill categories:
- **Project Management**: List your PM methodologies and tools
- **AI Collaboration**: Highlight your AI/ML experience
- **Technical Skills**: Include your programming languages and frameworks

#### Contact Section
Update contact information:
- Replace placeholder email with your actual email
- Add your LinkedIn and GitHub profile URLs
- Modify the contact call-to-action as needed

### Project Links
Replace the placeholder `#` links in the project cards with your actual project URLs:

```html
<a href="https://yourusername.github.io/project-name" class="btn btn-outline">Live Demo</a>
<a href="https://github.com/yourusername/project-name" class="btn btn-text">View Code</a>
```

## 🔧 Advanced Customization

### Adding New Sections
To add a new section:
1. Add the HTML structure following the existing pattern
2. Add corresponding CSS styles
3. Update the navigation menu to include the new section

### Modifying Animations
Animations are controlled in `script.js`. You can:
- Adjust timing by modifying the `setTimeout` values
- Change animation types by updating CSS classes
- Disable animations by commenting out the relevant code

### Adding a Contact Form
To add a functional contact form:
1. Add the form HTML in the contact section
2. Implement form handling in `script.js`
3. Connect to a backend service (Netlify Forms, Formspree, etc.)

## 📱 Browser Support

- **Modern Browsers**: Chrome, Firefox, Safari, Edge (latest versions)
- **Mobile Browsers**: iOS Safari, Chrome Mobile, Samsung Internet
- **Fallbacks**: Graceful degradation for older browsers

## 🚀 Deployment Options

### GitHub Pages
1. Create a new repository
2. Upload all files
3. Enable GitHub Pages in repository settings
4. Your site will be available at `https://yourusername.github.io/repository-name`

### Netlify
1. Drag and drop the folder to Netlify
2. Your site will be deployed instantly with a custom URL
3. Connect to GitHub for automatic deployments

### Vercel
1. Import your GitHub repository
2. Deploy with zero configuration
3. Get automatic deployments on every push

## 🎯 SEO Optimization

The page includes basic SEO optimization:
- Semantic HTML structure
- Meta tags for description and viewport
- Proper heading hierarchy
- Alt text for images (add when you include actual images)

To further optimize:
1. Add meta description and keywords
2. Include Open Graph tags for social sharing
3. Add structured data markup
4. Optimize images and add alt text

## 🔍 Performance

The landing page is optimized for performance:
- **Minimal Dependencies**: No external frameworks
- **Optimized CSS**: Efficient selectors and minimal repaints
- **Lazy Loading**: Intersection Observer for animations
- **Compressed Assets**: Minify CSS/JS for production

## 🤝 Contributing

Feel free to fork this project and customize it for your own use. If you make improvements that could benefit others, consider submitting a pull request.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- **Inter Font**: Google Fonts for the beautiful typography
- **CSS Grid & Flexbox**: For the responsive layout system
- **Intersection Observer API**: For performance-optimized animations

---

**Built with ❤️ and AI collaboration** - This landing page itself demonstrates the power of human-AI partnership in creating modern web experiences. 