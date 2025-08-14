# Ahmed Shady - Professional Portfolio Website

A modern, responsive portfolio website showcasing the skills and projects of Ahmed Shady, a Mechatronics Engineering student specializing in AI and Machine Learning.

## Features

### Design & User Experience
- **Luxury Design**: Modern dark theme with gradient backgrounds and gold accents
- **Smooth Animations**: CSS animations and JavaScript interactions for enhanced user experience
- **Responsive Layout**: Optimized for desktop, tablet, and mobile devices
- **Interactive Elements**: Hover effects, smooth scrolling, and dynamic content

### Sections
1. **Hero Section**: Animated introduction with typewriter effect and floating particles
2. **About Section**: Professional background, education, and personal details
3. **Skills Section**: Technical expertise with animated progress bars
4. **Projects Section**: Featured projects with filtering capabilities
5. **Contact Section**: Interactive contact form and social media links

### Technical Features
- **Pure HTML/CSS/JavaScript**: No external frameworks required
- **Modern CSS**: CSS Grid, Flexbox, custom properties, and animations
- **Intersection Observer**: Scroll-triggered animations
- **Form Validation**: Client-side form validation with feedback
- **SEO Optimized**: Semantic HTML structure and meta tags

## File Structure

```
portfolio/
├── index.html          # Main HTML file
├── css/
│   └── style.css      # All styles and animations
├── js/
│   └── script.js      # JavaScript functionality
├── images/
│   ├── profile.jpg    # Profile picture
│   └── projects/      # Project images
│       ├── car-price-prediction.jpg
│       ├── spam-detection.jpg
│       ├── cnc-plotter.jpg
│       ├── hydraulic-cylinder.jpg
│       ├── image-classification.jpg
│       └── line-follower.jpg
└── assets/
    └── icons/         # Additional icons (if needed)
```

## Technologies Used

- **HTML5**: Semantic markup and accessibility features
- **CSS3**: Modern styling with animations and responsive design
- **JavaScript (ES6+)**: Interactive functionality and DOM manipulation
- **Google Fonts**: Montserrat and Poppins font families
- **Font Awesome**: Icons for enhanced visual appeal

## Key Animations

1. **Typewriter Effect**: Animated text typing in hero section
2. **Floating Particles**: Background animation with moving particles
3. **Scroll Animations**: Elements fade/slide in on scroll
4. **Progress Bars**: Animated skill level indicators
5. **Project Filters**: Smooth filtering with fade transitions
6. **Form Interactions**: Animated input labels and validation

## Browser Compatibility

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## Setup Instructions

1. Extract the portfolio files to your desired directory
2. Open `index.html` in a web browser
3. For local development, use a local server:
   ```bash
   python -m http.server 8000
   # or
   npx serve .
   ```

## Customization

### Colors
The color scheme can be modified by updating CSS custom properties in `style.css`:
```css
:root {
    --primary-color: #1a1a2e;
    --secondary-color: #16213e;
    --accent-color: #0f3460;
    --highlight-color: #e94560;
    --gold-color: #f39c12;
}
```

### Content
- Update personal information in `index.html`
- Replace project images in `images/projects/`
- Modify project descriptions and technologies
- Update contact information and social media links

### Animations
Animation timing and effects can be adjusted in the CSS animations section and JavaScript configuration.

## Performance Optimizations

- Optimized images for web
- Minified CSS and JavaScript (for production)
- Efficient animations using CSS transforms
- Lazy loading for images
- Debounced scroll events

## Contact Information

- **Email**: medoshady153@gmail.com
- **Phone**: +201030705013
- **Location**: Cairo, Egypt

## License

This portfolio template is created for Ahmed Shady. Feel free to use it as inspiration for your own portfolio projects.

---

*Built with passion and attention to detail. Showcasing the intersection of engineering and artificial intelligence.*

