# DirtOff - Premium Laundry & Dry Cleaning Services Website

A modern, responsive website for DirtOff, a premium laundry and dry cleaning service provider. Built with HTML5, CSS3, and JavaScript, featuring a clean design and comprehensive service showcase.

## 🚀 Project Overview

DirtOff is a static website designed for a laundry and dry cleaning business, offering various services including dry cleaning, wet cleaning, steam ironing, shoe cleaning, bag cleaning, carpet cleaning, curtain cleaning, and sofa cleaning.

## 🛠️ Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES5)
- **CSS Framework**: Bootstrap 4.x
- **JavaScript Libraries**:
  - jQuery 3.x
  - Owl Carousel 2.x
  - WOW.js (animations)
  - jQuery Fancybox (lightbox)
  - jQuery Nice Select
  - jQuery CountTo
  - jQuery TouchSpin
  - BxSlider
- **Icons**: Font Awesome 5 Pro, Flaticon
- **Fonts**: Google Fonts (Poppins, Lato)
- **Form Handling**: Web3Forms API integration

## 📁 Project Structure

```
Dirtoff-website-git/
├── assets/
│   ├── css/
│   │   ├── animate.css          # Animation styles
│   │   ├── bootstrap.css        # Bootstrap framework
│   │   ├── font-awesome-all.css # Font Awesome icons
│   │   ├── style.css           # Main stylesheet
│   │   ├── responsive.css      # Responsive design
│   │   └── ...
│   ├── js/
│   │   ├── jquery.js           # jQuery library
│   │   ├── bootstrap.min.js    # Bootstrap JS
│   │   ├── owl.js             # Owl Carousel
│   │   ├── script.js          # Main JavaScript
│   │   └── ...
│   ├── images/
│   │   ├── banner/            # Hero section images
│   │   ├── service/           # Service-related images
│   │   ├── logo/              # Brand logos
│   │   ├── icons/             # Icon assets
│   │   └── ...
│   └── fonts/                 # Font files
├── index.html                 # Homepage
├── about.html                 # About page
├── service.html               # Services overview
├── contact.html               # Contact page
├── service-details-*.html     # Individual service pages
└── README.md                  # Project documentation
```

## 🎨 Features

### Core Features
- **Responsive Design**: Mobile-first approach with Bootstrap grid system
- **Interactive Carousel**: Owl Carousel for image sliders and testimonials
- **Smooth Animations**: WOW.js for scroll-triggered animations
- **Contact Forms**: Integrated with Web3Forms for form submissions
- **Newsletter Subscription**: Email subscription functionality
- **Service Showcase**: Dedicated pages for each service type
- **Customer Testimonials**: Interactive testimonial carousel
- **Mobile Navigation**: Collapsible mobile menu

### Service Pages
- Dry Cleaning
- Wet Cleaning  
- Steam Ironing
- Bag Cleaning
- Shoe Cleaning
- Carpet Cleaning
- Curtain Cleaning
- Sofa Cleaning

### UI Components
- Sticky navigation header
- Hero banner with carousel
- Service cards with hover effects
- Progress bars for statistics
- Lightbox image gallery
- Social media integration
- Scroll-to-top functionality

## 🔧 Setup & Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd Dirtoff-website-git
   ```

2. **Local Development**
   - Open `index.html` in a web browser
   - Or use a local server (recommended):
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx http-server
   
   # Using PHP
   php -S localhost:8000
   ```

3. **Access the website**
   - Open `http://localhost:8000` in your browser

## 📱 Browser Compatibility

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+
- Internet Explorer 11+ (limited support)

## 🎯 Key JavaScript Functionality

### Main Features (script.js)
- **Carousel Management**: Owl Carousel initialization and controls
- **Mobile Menu**: Toggle functionality for mobile navigation
- **Smooth Scrolling**: Scroll-to-target functionality
- **Form Validation**: Contact form validation
- **Animation Triggers**: WOW.js integration for scroll animations
- **Sticky Header**: Dynamic header behavior on scroll

### Form Integration
- Web3Forms API for contact form submissions
- Newsletter subscription handling
- Form validation and error handling

## 🎨 CSS Architecture

### Main Stylesheets
- `style.css`: Core styles and component definitions
- `responsive.css`: Media queries and responsive adjustments
- `animate.css`: Animation keyframes and transitions
- `bootstrap.css`: Grid system and utility classes

### CSS Custom Properties
```css
:root {
  --primary-color: hsl(260, 35%, 60%);
}
```

### Key Design Elements
- **Color Scheme**: Purple primary color with ivory background
- **Typography**: Poppins for headings, Lato for body text
- **Layout**: CSS Grid and Flexbox for modern layouts
- **Animations**: CSS transitions and keyframe animations

## 📧 Contact Form Configuration

The website uses Web3Forms for form handling. To configure:

1. **Update Access Key** in contact forms:
   ```html
   <input type="hidden" name="access_key" value="YOUR_ACCESS_KEY">
   ```

2. **Form Endpoints**:
   - Contact Form: `https://api.web3forms.com/submit`
   - Newsletter: `https://api.web3forms.com/submit`

## 🔍 SEO Optimization

- Semantic HTML5 structure
- Meta tags for social sharing
- Optimized images with alt attributes
- Clean URL structure
- Mobile-friendly design
- Fast loading times

## 🚀 Performance Optimization

- Minified CSS and JavaScript files
- Optimized image formats
- Lazy loading for images
- CDN integration for external libraries
- Efficient CSS selectors

## 📱 Responsive Breakpoints

```css
/* Mobile First Approach */
@media (max-width: 767px) { /* Mobile */ }
@media (min-width: 768px) { /* Tablet */ }
@media (min-width: 992px) { /* Desktop */ }
@media (min-width: 1200px) { /* Large Desktop */ }
```

## 🔧 Customization

### Colors
Update the CSS custom property in `style.css`:
```css
:root {
  --primary-color: your-color-here;
}
```

### Content
- Edit HTML files for content changes
- Update images in `assets/images/` directory
- Modify service details in respective service pages

### Styling
- Main styles: `assets/css/style.css`
- Responsive adjustments: `assets/css/responsive.css`

## 📄 License

This project is proprietary software developed for DirtOff laundry services.

## 🤝 Contributing

This is a client project. For modifications or updates, please contact the development team.

---

**Developed by**: Shine Infosolutions  
**Project Type**: Static Website  
**Last Updated**: 2025