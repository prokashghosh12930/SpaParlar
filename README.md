# 🌸 Redical Spa and Saloon

A luxurious, responsive single-page website for a premium spa business featuring elegant design, smooth animations, and modern UI elements.

## 📸 Screenshots

### 🏠 Homepage with Carousel
![Homepage](https://via.placeholder.com/800x400/ff6b9d/ffffff?text=Redical+Spa+Homepage+with+Rotating+Carousel)

### 💆‍♀️ Services Section
![Services](https://via.placeholder.com/800x400/9d4edd/ffffff?text=Our+Special+Massage+Services+Section)

### 🖼️ Gallery
![Gallery](https://via.placeholder.com/800x400/c77dff/ffffff?text=Spa+Gallery+with+Hover+Effects)

### 💰 Pricing Catalog
![Pricing](https://via.placeholder.com/800x400/ffe1e8/9d4edd?text=Service+Pricing+Table)

### 📱 Mobile Responsive
![Mobile](https://via.placeholder.com/400x600/ff6b9d/ffffff?text=Mobile+Responsive+Design)

## ✨ Features

### 🎨 Design & UI
- **Elegant Color Scheme**: Soft pinks, purples, and white backgrounds
- **Luxurious Gradients**: Smooth color transitions throughout
- **Modern Typography**: Playfair Display & Poppins fonts
- **Hover Effects**: Interactive elements with smooth animations
- **Glass Morphism**: Modern translucent navigation bar

### 📱 Responsive Design
- **Mobile-First**: Optimized for all screen sizes
- **Hamburger Menu**: Touch-friendly mobile navigation
- **Flexible Layouts**: Adaptive grids for different devices
- **Cross-Browser**: Compatible with all modern browsers

### 🎪 Interactive Elements
- **Auto-Rotating Carousel**: 4 beautiful spa images with 5-second intervals
- **Touch Gestures**: Swipe support for mobile carousel navigation
- **Lightbox Gallery**: Click to view images in full screen
- **Smooth Scrolling**: Seamless navigation between sections
- **Booking Modals**: Interactive booking request system

## 🏗️ Project Structure

```
SpaParlar/
├── index.html          # Main HTML file
├── styles.css          # CSS styling and responsive design
├── script.js           # JavaScript functionality
└── README.md           # Project documentation
```

## 📄 Sections

### 1. 🧭 Navigation Bar
- Fixed header with smooth scrolling links
- Transparent background with blur effect
- Mobile hamburger menu
- Hover animations on links

### 2. 🏠 Home Section
- **Full-width carousel** with 4 rotating spa images
- **Auto-advance** every 5 seconds
- **Manual navigation** with clickable indicators
- **Keyboard support** (arrow keys)
- **Touch gestures** for mobile swiping

### 3. 💆‍♀️ About Section
- "Our Special Massage Services" heading
- Service specializations overview
- **Interactive service cards** with hover effects
- Icons representing different services

### 4. 🖼️ Gallery Section
- **6 high-quality spa images** from Unsplash
- **Grid layout** with responsive design
- **Hover zoom effects** and overlay
- **Lightbox functionality** for full-screen viewing

### 5. 💰 Catalog Section
- **Pricing table** with 6 services
- **Featured card** highlighting popular service
- **Interactive buttons** linking to contact
- **Responsive card layout**

### 6. 📞 Contact Section
- **Phone number**: +91 9876543210
- **Embedded Google Maps** for Kolkata location
- **Business hours** and location info
- **Interactive contact cards**

### 7. 🦶 Footer
- **Company information**
- **Quick navigation links**
- **Service listings**
- **Social media links**

## 💰 Pricing Table

| Service | Price (INR) | Duration |
|---------|-------------|----------|
| Full Body Massage | ₹2000 | 60 minutes |
| **Deep Tissue Massage** | **₹2500** | **75 minutes** |
| Sandwich Massage | ₹3000 | 90 minutes |
| Aroma Therapy | ₹1800 | 60 minutes |
| Couples Massage | ₹4000 | 90 minutes |
| Facial & Body Waxing | ₹1500 | 45 minutes |

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional software required

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/SpaParlar.git
   cd SpaParlar
   ```

2. **Open the website**
   - Double-click `index.html` to open in your default browser
   - Or right-click and choose "Open with" your preferred browser

3. **For development**
   - Use a local server for best performance:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   
   # Using PHP
   php -S localhost:8000
   ```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with flexbox, grid, and animations
- **JavaScript**: Interactive functionality and carousel
- **Font Awesome**: Icon library for UI elements
- **Google Fonts**: Playfair Display & Poppins typography
- **Unsplash**: High-quality spa imagery

## 🎯 Key Features Implementation

### Carousel Functionality
```javascript
// Auto-advance every 5 seconds
let carouselInterval = setInterval(nextSlide, 5000);

// Touch gesture support
carousel.addEventListener('touchstart', handleTouchStart);
carousel.addEventListener('touchend', handleTouchEnd);
```

### Responsive Design
```css
/* Mobile-first approach */
@media (max-width: 768px) {
    .nav-menu {
        position: fixed;
        flex-direction: column;
        /* Mobile menu styles */
    }
}
```

### Smooth Animations
```css
:root {
    --transition: all 0.3s ease;
    --shadow-hover: 0 20px 40px rgba(157, 78, 221, 0.2);
}
```

## 📱 Browser Compatibility

- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🔧 Customization

### Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-pink: #ff6b9d;
    --primary-purple: #9d4edd;
    --soft-pink: #ffc0cb;
    /* Add your custom colors */
}
```

### Images
Replace Unsplash URLs in `index.html` with your own images:
```html
<img src="your-image-url.jpg" alt="Description">
```

### Contact Information
Update contact details in the contact section:
```html
<p>📞 +91 YOUR-PHONE-NUMBER</p>
```

## 🚀 Performance Optimizations

- **Image Optimization**: Unsplash images with optimized parameters
- **Lazy Loading**: Implemented for better performance
- **Minified Assets**: Compressed CSS and JS for faster loading
- **Preload Critical Resources**: Fonts and above-the-fold images

## 📈 SEO Features

- **Semantic HTML**: Proper heading structure and landmarks
- **Meta Tags**: Responsive viewport and character encoding
- **Alt Attributes**: Descriptive image alt text
- **Clean URLs**: Single-page with anchor navigation

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Prokash**
- GitHub: [@yourhandle](https://github.com/yourhandle)
- Email: your.email@example.com

## 🙏 Acknowledgments

- **Unsplash** for beautiful spa imagery
- **Font Awesome** for icons
- **Google Fonts** for typography
- **CSS-Tricks** for responsive design inspiration

## 📞 Support

For support and questions:
- **Email**: support@radicalspa.com
- **Phone**: +91 9876543210
- **Website**: [Live Demo](https://yourwebsite.com)

---

⭐ **Star this repository if you found it helpful!** ⭐

*Made with 💖 for Redical Spa and Saloon*
