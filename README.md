# Cyber Security Website

> A modern, responsive landing page for cybersecurity services built with Bootstrap 5 and custom styling.

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-5.3.8-purple?logo=bootstrap&logoColor=white)](https://getbootstrap.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

## Table of Contents

- [About](#about)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## About

This project is a professional landing page template designed for cybersecurity companies and digital security service providers. It showcases modern web design practices with a sleek dark theme, smooth gradients, and responsive layout that works seamlessly across all devices.

**Purpose:**  
Create an engaging first impression for cybersecurity businesses while demonstrating proficiency in front-end development, responsive design, and modern CSS frameworks.

## Features

- 🎨 **Modern Dark Theme** - Eye-catching gradient background (navy to dark blue)
- 📱 **Fully Responsive** - Mobile-first design that adapts to all screen sizes
- 🧭 **Fixed Navigation** - Sticky navbar with smooth collapse on mobile
- 📊 **Statistics Counter** - Impressive metrics display (projects, clients, guarantees)
- 🛡️ **Services Section** - Highlighted security and privacy features with icons
- ⚡ **Fast Loading** - CDN-hosted Bootstrap and Font Awesome for optimal performance
- 🎯 **Call-to-Action** - "Get A Quote" button for lead generation
- ♿ **Accessible** - Semantic HTML structure

## Installation

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- A code editor (VS Code, Sublime Text, etc.)
- Basic knowledge of HTML/CSS

### Setup

1. Clone the repository:
```bash
git clone https://github.com/yourusername/cybersecurity-website.git
cd cybersecurity-website
```

2. Open the project:
```bash
# Simply open index.html in your browser
# Or use a live server for development
```

### Using Live Server (Recommended for Development)

If you have VS Code with the Live Server extension:
1. Right-click on `index.html`
2. Select "Open with Live Server"
3. The page will open automatically in your browser

## Usage

### Viewing the Website

Simply open `index.html` in any modern web browser to view the website locally.

### Navigation Structure

- **Home** - Hero section with main headline
- **About** - Company information and value propositions
- **Services** - Cybersecurity offerings
- **Pages** - Additional content pages
- **Blog** - News and updates
- **Get A Quote** - Contact/inquiry button

### Customizing Content

Replace the placeholder content in the HTML:

```html
<!-- Update hero text -->
<h1 class="fw-bold">Your Custom Headline Here</h1>

<!-- Update statistics -->
<h2 class="fw-bold display-4">Your Number+</h2>

<!-- Update about section -->
<p>Your company description here...</p>
```

## Technologies Used

- **HTML5** - Semantic markup structure
- **CSS3** - Custom styling with gradients
- **Bootstrap 5.3.8** - Responsive grid system and components
- **Font Awesome 6.0** - Professional icon library
- **Google Fonts** (implicit) - Typography enhancement

### CDN Resources

```html
<!-- Bootstrap CSS -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css">

<!-- Font Awesome Icons -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">

<!-- Bootstrap JavaScript Bundle -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/js/bootstrap.bundle.min.js">
```

## Project Structure

```
cybersecurity-website/
│
├── index.html          # Main HTML file
├── README.md           # Project documentation
└── LICENSE             # License file
```

## Customization

### Color Scheme

The current color palette uses:

```css
/* Primary Background Gradient */
background: linear-gradient(135deg, #0a0f22, #0f1630);

/* Primary Accent Color */
color: #0d6efd; /* Bootstrap primary blue */

/* Navbar Background */
background-color: #0f1630;
```

To change the theme:
1. Locate inline `style` attributes in the HTML
2. Update hex color codes or use Bootstrap color utilities

### Adding Sections

The website follows Bootstrap's grid system:

```html
<div class="container">
  <div class="row">
    <div class="col-lg-6">
      <!-- Your content -->
    </div>
  </div>
</div>
```

### Font Customization

Add custom Google Fonts in the `<head>`:

```html
<link href="https://fonts.googleapis.com/css2?family=Your+Font&display=swap" rel="stylesheet">
```

Then apply via inline styles or add a custom CSS file.

## Responsive Breakpoints

The design uses Bootstrap's responsive breakpoints:

- **Mobile**: < 576px (col-sm)
- **Tablet**: ≥ 576px (col-md)
- **Desktop**: ≥ 992px (col-lg)
- **Large Desktop**: ≥ 1200px (col-xl)

## Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ⚠️ IE 11 (Bootstrap 5 has limited support)

## Roadmap

- [ ] Add custom CSS file for better organization
- [ ] Implement smooth scroll navigation
- [ ] Add contact form with validation
- [ ] Create additional service pages
- [ ] Add animation effects on scroll
- [ ] Implement dark/light mode toggle
- [ ] Add testimonials section
- [ ] Integrate blog functionality
- [ ] Add SEO meta tags

## Contributing

Contributions are welcome! Here's how you can help:

### How to Contribute

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/NewSection`)
3. Commit your changes (`git commit -m 'Add testimonials section'`)
4. Push to the branch (`git push origin feature/NewSection`)
5. Open a Pull Request

### Contribution Ideas

- Add new sections (testimonials, team, pricing)
- Improve accessibility (ARIA labels, keyboard navigation)
- Create additional page templates
- Enhance mobile responsiveness
- Add animations and transitions
- Write documentation

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

**Your Name**

- GitHub: [@ClydeCenteno1](https://github.com/ClydeCenteno1)
- Email: centenoclydeamiel@gmail.com

## Acknowledgments

- Design inspired by modern cybersecurity company websites
- Icons provided by [Font Awesome](https://fontawesome.com/)
- CSS framework by [Bootstrap](https://getbootstrap.com/)
- Gradient inspiration from [UI Gradients](https://uigradients.com/)

---

⭐ If you found this project useful, please consider giving it a star!

**Made with ❤️ and Bootstrap**
