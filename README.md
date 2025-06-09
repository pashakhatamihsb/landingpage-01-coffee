# ☕ Brew Haven - Premium Coffee Shop Website

A modern, responsive coffee shop website built with pure HTML5 and CSS3. Features a clean design, smooth animations, and mobile-first approach without any JavaScript dependencies.

## 🌟 Features

### Design & UI/UX
- **Modern Responsive Design** - Fully responsive across all devices
- **Smooth Animations** - CSS animations and transitions for enhanced UX
- **Fixed Navigation** - Sticky navbar with backdrop blur effect
- **Hero Section** - Eye-catching header with call-to-action
- **Product Showcase** - Interactive product cards with hover effects
- **Professional Typography** - Google Fonts integration (Playfair Display + Inter)

### Technical Features
- **Pure CSS Implementation** - No JavaScript dependencies
- **CSS Grid & Flexbox** - Modern layout techniques
- **CSS Custom Properties** - Consistent color scheme and theming
- **CSS Animations** - Smooth transitions and hover effects
- **Mobile-First Approach** - Optimized for mobile devices
- **Semantic HTML** - Accessible and SEO-friendly structure
- **CSS Scroll Behavior** - Smooth navigation with pure CSS

## 🚀 Quick Start

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies required

### Installation

1. **Clone or Download**
   ```bash
   git clone [repository-url]
   cd brew-haven-coffee
   ```

2. **Open in Browser**
   ```bash
   # Simply open the HTML file in your browser
   open index.html
   # or
   double-click index.html
   ```

3. **Local Development Server (Optional)**
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   
   # Using PHP
   php -S localhost:8000
   ```

## 📁 Project Structure

```
brew-haven-coffee/
│
├── index.html          # Main HTML file with embedded CSS
├── README.md          # Project documentation
└── assets/            # Optional: for local images
    └── images/        # Local images (if any)
```

## 🎨 Color Palette

| Color | Hex Code | Usage |
|-------|----------|--------|
| Main Gold | `#D4A574` | Primary accent, buttons, highlights |
| Primary Brown | `#2C1810` | Section backgrounds |
| Background Dark | `#0F0D0E` | Main background |
| White | `#FFFFFF` | Primary text |
| Cream | `#F5F1ED` | Secondary text |
| Dark Brown | `#1A0E0A` | Footer background |
| Light Brown | `#8B4513` | Hover states |

## 📱 Responsive Breakpoints

| Device | Breakpoint | Layout Changes |
|--------|------------|----------------|
| Mobile | `< 480px` | Single column, reduced spacing |
| Tablet | `< 768px` | Stacked sections, hidden nav menu |
| Desktop | `> 768px` | Full grid layout, all features |

## 🔧 Customization

### Changing Colors
Edit the CSS custom properties in the `<style>` section within the HTML file:

```css
:root {
    --main-color: #D4A574;        /* Primary accent color */
    --primary-color: #2C1810;     /* Section backgrounds */
    --background-color: #0F0D0E;  /* Main background */
    /* ... other colors */
}
```

### Updating Content
1. **Logo & Branding**: Edit the `.logo` class content in HTML
2. **Menu Items**: Modify the product cards in the `#products` section
3. **Contact Info**: Update footer section with your details
4. **Images**: Replace Unsplash URLs with your own images

### Adding New Sections
Follow the existing pattern:

```html
<section class="new-section">
    <div class="container">
        <div class="section-title">
            <h2>Section Title</h2>
        </div>
        <!-- Section content -->
    </div>
</section>
```

### Separating CSS (Optional)
If you want to separate CSS into external file:

1. Create `style.css` file
2. Move all CSS from `<style>` tags to `style.css`
3. Add link in HTML: `<link rel="stylesheet" href="style.css">`

## 🖼️ Image Sources

All images are sourced from [Unsplash](https://unsplash.com) for demonstration purposes:
- Hero background: Coffee shop interior
- Story section: Coffee beans and brewing
- Product images: Various coffee drinks
- Coffee section: Café atmosphere

**Note**: Replace with your own images for production use.

## 🌐 Browser Compatibility

| Browser | Version | Support |
|---------|---------|---------|
| Chrome | 60+ | ✅ Full |
| Firefox | 55+ | ✅ Full |
| Safari | 12+ | ✅ Full |
| Edge | 79+ | ✅ Full |
| IE | 11 | ⚠️ Limited |

## 📈 Performance

- **Lightweight**: Single HTML file with embedded CSS
- **Fast Loading**: No external CSS/JS dependencies
- **Pure CSS Animations**: Smooth performance without JavaScript
- **Optimized**: Minimal HTTP requests
- **Mobile Optimized**: CSS-only responsive design
- **No Build Process**: Ready to deploy as-is

## 🔍 SEO Features

- Semantic HTML structure
- Meta tags optimization ready
- Alt text for images
- Proper heading hierarchy (H1-H4)
- Schema markup ready
- Clean URL structure

## 🚀 Deployment

### Netlify
1. Drag and drop the `index.html` file to [Netlify](https://netlify.com)
2. Get instant deployment URL
3. Connect to GitHub for continuous deployment

### Any Web Server
Since it's a single HTML file, you can:
- Upload to any web hosting service
- Use with Apache, Nginx, or any web server
- Deploy to CDN services
- Host on cloud platforms (AWS S3, Google Cloud, etc.)

## 🛠️ Development

### Code Structure
- **HTML**: Semantic, accessible markup with embedded CSS
- **CSS**: Modern CSS3 features, BEM methodology, mobile-first
- **Assets**: External images from Unsplash CDN

### Best Practices Implemented
- ✅ Mobile-first responsive design
- ✅ Accessibility considerations
- ✅ SEO-friendly structure
- ✅ Performance optimization
- ✅ Clean, maintainable code
- ✅ Cross-browser compatibility
- ✅ Modern CSS features
- ✅ No build process required
- ✅ Single file deployment

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

**Pasha Khatami Hasibuan**
- LinkedIn: [Your LinkedIn](https://www.linkedin.com/in/pashakhatamihsb/)

## 🙏 Acknowledgments

- [Unsplash](https://unsplash.com) for high-quality images
- [Google Fonts](https://fonts.google.com) for typography
- Coffee shop inspiration from various café designs
- Community feedback and suggestions

## 📊 Analytics & Metrics

Track your website performance:
- Google Analytics integration ready
- Core Web Vitals monitoring
- User engagement tracking
- Conversion rate optimization

---

**Built with ❤️ and lots of ☕**

*For support or questions, please open an issue or contact the developer.*
