# Amazon Clone

A front-end replica of Amazon's user interface, built with **HTML** and **CSS**. This project demonstrates responsive web design and layout techniques commonly used in e-commerce websites.

## 📋 Overview

This Amazon Clone is a static website that replicates the visual design and layout of Amazon.com. It includes:

- **Header/Navbar** - Navigation bar with logo, search functionality, language selection, account options, and cart
- **Hero Section** - Promotional content and messaging area
- **Product Boxes** - Organized product categories displayed in a grid layout
- **Footer** - Typical e-commerce footer structure (if present)

## 🛠️ Technologies Used

- **HTML5** - Semantic markup structure
- **CSS3** - Styling and responsive design
- **Font Awesome 6.7.2** - Icon library (CDN)

## 📁 Project Structure

```
amazon-clone/
├── index.html        # Main HTML file with structure and layout
├── amazon1.css       # Stylesheet with all CSS styling
├── amazon_logo.png   # Amazon logo image
├── flag.png          # Country flag icon
├── box1_image.jpg    # Clothes category product image
├── box2_image.jpg    # Health & Personal Care category image
└── README.md         # Project documentation
```

## 🎯 Features

- **Navigation Bar** with:
  - Amazon logo
  - Delivery location indicator
  - Search bar with category dropdown
  - Language selection
  - Account & Lists menu
  - Returns & Orders link
  - Shopping cart icon

- **Product Category Boxes** including:
  - Clothes
  - Health & Personal Care
  - And more...

- **Responsive Design** - Uses flexbox for layout management

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No backend server or installation required

### Installation

1. Clone or download the repository:
   ```bash
   git clone <repository-url>
   cd Amazon-Clone
   ```

2. Open the project in your browser:
   - Simply open `index.html` directly in your web browser, or
   - Use a local server for better results:
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js (if you have http-server installed)
     npx http-server
     ```

3. Navigate to `http://localhost:8000` in your browser

## 📝 Code Structure

### HTML (`index.html`)
- Uses semantic HTML5 structure
- Incorporates Font Awesome icons via CDN
- Organized sections: header, navbar, product boxes, footer
- Mobile viewport meta tag included

### CSS (`amazon1.css`)
- Comprehensive styling for all components
- Flexbox layout for responsive design
- Hover effects on interactive elements
- Color scheme matching Amazon's branding
- Organized class selectors for maintainability

## 🎨 Design Elements

- **Primary Colors**:
  - Dark: `#0f1111` (header/navbar background)
  - Accent: Orange search button
  
- **Typography**: Arial, Helvetica, sans-serif

- **Layout**: Flexbox-based responsive design

## 🔄 Features to Enhance

Potential improvements for the future:
- Add JavaScript functionality (search, cart management)
- Implement responsive mobile design improvements
- Add product detail pages
- Create shopping cart functionality
- Integrate with a backend API
- Add product filtering and sorting

## 📷 Images Required

Make sure to include these image files in the project directory:
- `amazon_logo.png` - Logo for the navbar
- `flag.png` - Country flag icon (16.2px × 21.6px)
- `box1_image.jpg` - Clothes category image (347px × 100%)
- `box2_image.jpg` - Health & Personal Care image (347px × 100%)

## 💡 Notes

- This is a **static frontend** project with no backend functionality
- All styling is in a single CSS file for simplicity
- The code is well-organized and commented for easy understanding
- Perfect for learning HTML and CSS best practices

## 📄 License

This project is licensed under the MIT License — see the LICENSE file at the project root for details.

**Happy Coding! 🚀**
