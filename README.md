# Professional Consulting Website

A modern, responsive consulting website built with HTML, CSS, and JavaScript featuring a corporate/bold design aesthetic.

## Features

- **Responsive Design**: Fully optimized for desktop, tablet, and mobile devices
- **Modern UI**: Corporate/bold design with strong colors and professional typography
- **Smooth Animations**: Scroll animations, hover effects, and transitions
- **Interactive Elements**: Mobile menu, form validation, and notification system
- **Contact Form**: Validated contact form with user feedback
- **SEO-Friendly**: Semantic HTML structure

## Project Structure

```
test-project/
├── index.html          # Main HTML file
├── css/
│   └── styles.css     # All styling
├── js/
│   └── main.js        # Interactive functionality
├── images/            # Place your images here
└── README.md          # This file
```

## Sections

1. **Navigation**: Sticky header with smooth scroll links
2. **Hero**: Eye-catching landing section with call-to-action buttons
3. **Services**: Grid layout showcasing 6 consulting services
4. **About**: Company information with statistics
5. **Contact**: Contact information and functional form
6. **Footer**: Quick links and social media

## Customization

### Changing Colors

Edit the CSS variables in `css/styles.css`:

```css
:root {
    --primary-color: #1a1a2e;      /* Dark navy */
    --secondary-color: #0f3460;     /* Medium blue */
    --accent-color: #e94560;        /* Bright red/pink */
    --light-bg: #f8f9fa;           /* Light gray background */
}
```

### Updating Content

- **Company Name**: Search for "ConsultPro" in `index.html` and replace
- **Contact Info**: Update address, phone, and email in the Contact section
- **Services**: Modify the service cards in the Services section
- **About Section**: Update text and statistics

### Adding Images

1. Place images in the `images/` folder
2. Replace the SVG placeholder in the About section:

```html
<img src="images/your-team-photo.jpg" alt="Team">
```

### Contact Form

The form currently displays a success message. To make it functional:

1. Set up a backend endpoint (e.g., PHP, Node.js, or a service like Formspree)
2. Update the form submission handler in `js/main.js`

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Getting Started

Simply open `index.html` in a web browser. For local development:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js http-server
npx http-server
```

Then visit `http://localhost:8000`

## Features Breakdown

### JavaScript Functionality

- Mobile menu toggle with hamburger animation
- Smooth scrolling with navbar offset
- Form validation and submission
- Notification system
- Scroll-based animations
- Active navigation link highlighting
- Animated statistics counter

### CSS Features

- CSS Grid and Flexbox layouts
- CSS custom properties (variables)
- Media queries for responsive design
- Smooth transitions and animations
- Modern gradient backgrounds

## License

Free to use and modify for your consulting business.
