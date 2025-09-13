# Miran Drug Shop Website

A modern, responsive website for Miran Drug Shop - your trusted healthcare partner since 2020.

## 🌟 Features

- **Modern Design**: Professional, healthcare-focused design with smooth animations
- **Fully Responsive**: Works perfectly on all devices (mobile, tablet, desktop)
- **Interactive Elements**: Search, filters, shopping cart, and contact forms
- **Fast Performance**: Optimized CSS and JavaScript for quick loading
- **SEO Friendly**: Proper meta tags and semantic HTML structure

## 🚀 Getting Started

### Option 1: Local Development Server

#### For Windows (PowerShell):
```powershell
# Navigate to your project directory
cd "C:\Users\richard\Desktop\drug shop"

# Start a local server (Python)
python -m http.server 8000

# Or if you have Node.js installed:
npx serve .

# Or if you have PHP installed:
php -S localhost:8000
```

#### For Mac/Linux:
```bash
# Navigate to your project directory
cd "/path/to/drug shop"

# Start a local server (Python)
python -m http.server 8000

# Or using Node.js (if you have it installed)
npx serve .

# Or using PHP (if you have it installed)
php -S localhost:8000
```

### Option 2: Open Directly in Browser
Simply double-click on `index.html` to open the website in your default browser.

## 📁 File Structure

```
drug shop/
├── index.html          # Home page
├── about.html          # About us page
├── product.html        # Products catalog
├── services.html       # Services offered
├── hours.html          # Business hours
├── contact.html        # Contact information
├── style.css           # Main stylesheet
├── script.js           # JavaScript functionality
├── images/             # Image assets
│   ├── drug shop 1.jpeg
│   ├── drug shop 2.jpeg
│   ├── Drug shop 3.jpeg
│   └── Drug shop 4.jpeg
├── README.md           # This file
├── sitemap.xml         # SEO sitemap
└── robots.txt          # Search engine instructions
```

## 🎨 Customization

### Colors
The website uses CSS custom properties (variables) for easy color customization. Edit the `:root` section in `style.css`:

```css
:root {
    --primary-color: #2c5aa0;      /* Main brand color */
    --secondary-color: #4a90e2;    /* Secondary brand color */
    --accent-color: #f39c12;       /* Accent/highlight color */
    --success-color: #27ae60;      /* Success/green color */
    --danger-color: #e74c3c;       /* Error/red color */
    --text-dark: #2c3e50;          /* Dark text color */
    --bg-light: #f8f9fa;           /* Light background color */
}
```

### Content Updates
- **Text Content**: Edit the HTML files directly
- **Images**: Replace images in the `images/` folder
- **Contact Information**: Update phone numbers, emails, and addresses in all HTML files
- **Business Hours**: Modify the hours in `hours.html`

### Adding New Products
To add new products to the products page:

1. Add a new product card in `product.html`:
```html
<div class="product-card card" data-category="your-category" data-price="price-range">
    <div class="product-image-container">
        <img src="images/your-product.jpg" alt="Product Name" class="product-image">
        <div class="product-overlay">
            <button class="btn btn-secondary quick-view-btn">Quick View</button>
        </div>
    </div>
    <div class="product-info">
        <h3>Product Name</h3>
        <p class="product-description">Product description here.</p>
        <div class="product-meta">
            <span class="price">$XX.XX</span>
            <span class="stock in-stock">In Stock</span>
        </div>
        <button class="btn btn-success add-to-cart-btn">
            <i class="fas fa-cart-plus"></i> Add to Cart
        </button>
    </div>
</div>
```

2. Update the category filter options if needed.

## 🔧 Technical Details

### Technologies Used
- **HTML5**: Semantic markup and modern structure
- **CSS3**: Flexbox, Grid, CSS Variables, and animations
- **JavaScript (ES6+)**: Modern JavaScript with modular functions
- **Font Awesome**: Professional icons throughout the interface

### Browser Support
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

### Performance Features
- CSS animations with hardware acceleration
- Efficient JavaScript event handling
- Optimized images and assets
- Responsive design without heavy frameworks

## 📱 Mobile Optimization

The website is fully optimized for mobile devices:
- Touch-friendly buttons and navigation
- Responsive images and layouts
- Mobile-first design approach
- Optimized for various screen sizes

## 🚀 Deployment

### Local Testing
1. Start a local server (see Getting Started section)
2. Open `http://localhost:8000` in your browser
3. Test all pages and functionality

### Web Hosting
To deploy to a web server:
1. Upload all files to your web hosting provider
2. Ensure the server supports HTML, CSS, and JavaScript
3. Test the live website thoroughly

### Recommended Hosting
- **Shared Hosting**: HostGator, Bluehost, or similar
- **Cloud Hosting**: AWS, Google Cloud, or Azure
- **Static Site Hosting**: Netlify, Vercel, or GitHub Pages

## 🛠️ Maintenance

### Regular Updates
- Update business hours and contact information
- Add new products and services
- Update images and content as needed
- Test functionality after any changes

### Performance Monitoring
- Check page load times
- Test on different devices and browsers
- Monitor user feedback and analytics

## 📞 Support

For technical support or questions about the website:
- Check this README file first
- Review the HTML, CSS, and JavaScript code
- Test functionality in different browsers
- Ensure all files are properly uploaded

## 🔄 Future Enhancements

Potential improvements for the future:
- **E-commerce Integration**: Add payment processing
- **Online Booking**: Appointment scheduling system
- **Patient Portal**: Secure patient information access
- **Blog/News**: Health tips and company updates
- **Multi-language Support**: Additional language options
- **Advanced Search**: Enhanced product search functionality

## 📄 License

This website template is created for Miran Drug Shop. Feel free to modify and customize for your specific needs.

---

**Miran Drug Shop** - Your trusted healthcare partner since 2020

*Built with modern web technologies for the best user experience*
