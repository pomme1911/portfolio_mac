# Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and vanilla JavaScript.

## Features

- **Responsive Design**: Fully responsive layout that works seamlessly on desktop, tablet, and mobile devices
- **Modern UI**: Clean and modern design with gradient effects and smooth animations
- **Hero Section**: Full-screen hero section with background image
- **Project Showcase**: Display up to 3 projects in an attractive card layout
- **Contact Form**: Functional contact form with validation
- **Smooth Scrolling**: Smooth scroll navigation between sections
- **Mobile Navigation**: Hamburger menu for mobile devices

## Technologies Used

- HTML5
- CSS3 (with CSS Variables, Flexbox, Grid)
- Vanilla JavaScript (ES6+)

## Project Structure

```
portfolio_mac/
├── index.html      # Main HTML file
├── styles.css      # All styling and responsive design
├── script.js       # JavaScript functionality
└── README.md       # Project documentation
```

## Sections

1. **Navigation Bar**: Fixed navigation with logo and menu items
2. **Hero Section**: Full-screen background image with introduction
3. **Projects Section**: Showcase of 3 projects with images and descriptions
4. **Contact Section**: Contact information and message form
5. **Footer**: Copyright information

## Getting Started

1. Clone or download this repository
2. Open `index.html` in your web browser
3. No build process or dependencies required!

## Customization

### Changing Images

- **Hero Background**: Update the `background-image` URL in `.hero` class in `styles.css`
- **Project Images**: Update the `background-image` URLs in `.project-1`, `.project-2`, `.project-3` classes in `styles.css`

### Changing Colors

Modify the CSS variables in `:root` selector in `styles.css`:

```css
:root {
    --primary-color: #6366f1;
    --secondary-color: #8b5cf6;
    --accent-color: #ec4899;
    /* ... */
}
```

### Updating Content

Edit the HTML content directly in `index.html`:
- Update hero section text
- Modify project descriptions and tags
- Change contact information

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is open source and available under the MIT License.

## Author

Imago

---

Built with ❤️ using vanilla web technologies

