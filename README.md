# Lucia Resort Philippines

A luxury tropical resort website showcasing the pristine beauty of Philippine islands and authentic Filipino hospitality.

## 🌴 About

Lucia Resort is a stunning website template for a luxury tropical resort located in the Philippines. The site features beautiful imagery, modern design, and comprehensive information about resort amenities, rooms, and experiences.

## ✨ Features

- **Responsive Design**: Fully responsive layout that works on all devices
- **Modern UI/UX**: Clean, elegant design with smooth animations
- **Multiple Pages**: Home, Rooms, About, Blog, and Contact pages
- **Interactive Elements**: Image galleries, carousels, and booking forms
- **Preloader**: Smooth loading experience with custom preloader
- **Contact Form**: PHP-powered contact form for guest inquiries

## 🏗️ Built With

- **HTML5**: Semantic markup structure
- **CSS3**: Modern styling with animations and responsive design
- **JavaScript**: Interactive functionality and dynamic content
- **Bootstrap**: Responsive grid system and components
- **jQuery**: DOM manipulation and event handling
- **Owl Carousel**: Image sliders and carousels
- **PHP**: Server-side contact form processing

## 📁 Project Structure

```
lucia-resort/
├── css/                    # Stylesheets
│   ├── bootstrap.min.css
│   ├── style.css
│   └── ...
├── js/                     # JavaScript files
│   ├── main.js
│   ├── jquery.min.js
│   └── ...
├── img/                    # Images and graphics
│   ├── banner/
│   ├── rooms/
│   ├── about/
│   └── ...
├── fonts/                  # Web fonts
├── scss/                   # SASS source files
├── index.html              # Homepage
├── about.html              # About page
├── rooms.html              # Rooms page
├── blog.html               # Blog page
├── contact.html            # Contact page
├── single-blog.html        # Single blog post page
├── elements.html           # UI elements showcase
└── contact_process.php     # Contact form handler
```

## 🚀 Getting Started

### Prerequisites

- Web server (Apache, Nginx, or similar)
- PHP support (for contact form functionality)
- Modern web browser

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/lucia-resort.git
   ```

2. Navigate to the project directory:
   ```bash
   cd lucia-resort
   ```

3. Open `index.html` in your web browser or deploy to a web server

### Local Development

For local development, you can use any local server setup:

- **Using Python**: `python -m http.server 8000`
- **Using Node.js**: `npx serve .`
- **Using PHP**: `php -S localhost:8000`

Then visit `http://localhost:8000` in your browser.

## 📱 Pages

- **Home** (`index.html`): Main landing page with hero slider and featured content
- **About** (`about.html`): Information about the resort and its story
- **Rooms** (`rooms.html`): Showcase of available accommodations
- **Blog** (`blog.html`): Latest news and articles
- **Contact** (`contact.html`): Contact information and inquiry form
- **Single Blog** (`single-blog.html`): Individual blog post template
- **Elements** (`elements.html`): UI components and styling examples

## 🎨 Customization

### Colors and Branding

Edit the CSS variables in `css/style.css` to customize the color scheme:

```css
:root {
  --primary-color: #your-color;
  --secondary-color: #your-color;
  --accent-color: #your-color;
}
```

### Content

- Replace images in the `img/` directory with your own
- Update text content in HTML files
- Modify contact information in `contact.html`
- Configure the contact form in `contact_process.php`

## 📧 Contact Form Setup

The contact form requires PHP configuration. Update `contact_process.php` with your email settings:

```php
$to = "your-email@example.com";
$subject = "New Contact Form Submission";
```

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Internet Explorer 11+

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📞 Support

For support and questions, please contact:
- Email: support@luciaresort.ph
- Phone: +63 917 123 4567

## 🙏 Acknowledgments

- Bootstrap team for the responsive framework
- jQuery team for the JavaScript library
- Font Awesome for the icon fonts
- All contributors who helped improve this project

---

**Lucia Resort Philippines** - Experience paradise in the heart of the Philippine archipelago.
