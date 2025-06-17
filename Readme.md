# Kyara Beverages - Official Website

> **Refreshment, Reimagined** - A premium website for Kyara Beverages, showcasing innovative millet-based fruit drinks with a modern, responsive design.

## 🚀 Project Overview

This project is a complete website redesign for **Kyara Beverages**, a health-focused beverage company specializing in millet-based fruit drinks. The website combines modern web design principles with smooth user experience to represent the brand's mission of reimagining traditional refreshment.

## ✨ Features

### 🎨 Design & User Experience
- **Modern Glassmorphism UI** with blur effects and transparency
- **Smooth Animations** using CSS keyframes and transitions
- **Interactive Elements** with hover effects and micro-interactions
- **Premium Color Palette** with gradient backgrounds
- **Floating Elements** for dynamic visual appeal

### 📱 Responsive Design
- **Mobile-First Approach** ensuring perfect display on all devices
- **Breakpoints:**
  - Mobile: ≤ 480px
  - Tablet: 481px - 768px
  - Desktop: 769px - 1024px+
- **CSS Grid & Flexbox** for flexible, modern layouts

### 🔧 Technical Features
- **Semantic HTML5** structure for accessibility
- **CSS3 Advanced Features** (Grid, Flexbox, Animations, Gradients)
- **Vanilla JavaScript** for smooth interactions
- **Intersection Observer API** for scroll-triggered animations
- **Form Validation** with user-friendly feedback

## 📁 Project Structure

```
kyara-beverages-website/
│
├── index.html              # Main HTML file
├── css/
│   └── styles.css          # Main stylesheet
├── js/
│   └── script.js          # JavaScript functionality
├── images/                 # Image assets (if any)
├── README.md              # Project documentation
└── .gitignore             # Git ignore file
```

## 🛠️ Technologies Used

- **HTML5** - Semantic markup and structure
- **CSS3** - Modern styling with advanced features:
  - CSS Grid & Flexbox
  - CSS Animations & Transitions
  - CSS Custom Properties (Variables)
  - Media Queries for responsiveness
- **JavaScript (ES6+)** - Interactive functionality:
  - Smooth scrolling navigation
  - Form handling and validation
  - Scroll-based animations
  - Intersection Observer API

## 🌟 Key Sections

### 1. Hero Section
- Animated company logo and branding
- Dynamic tagline: "Refreshment, Reimagined"
- Call-to-action button with smooth scroll
- Floating background elements

### 2. About Section
- Company mission and values
- Focus on millet-based innovation
- Glassmorphism card design

### 3. Products Showcase
- Three signature drinks with descriptions:
  - Millet Citrus Burst
  - Berry Millet Fusion
  - Tropical Millet Dream
- Interactive product cards with hover effects

### 4. Contact Form
- Name, email, and message fields
- Client-side form validation
- Responsive design with smooth interactions

## 🚀 Getting Started

### Prerequisites
- Any modern web browser (Chrome, Firefox, Safari, Edge)
- Text editor (VS Code, Sublime Text, etc.) for modifications
- Basic knowledge of HTML, CSS, and JavaScript

### Installation & Setup

1. **Clone or Download** the project files
   ```bash
   git clone [repository-url]
   cd kyara-beverages-website
   ```

2. **Open the project** in your preferred code editor

3. **Launch the website** by opening `index.html` in your web browser
   - **Option 1:** Double-click `index.html` file
   - **Option 2:** Use a local server (recommended):
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js
     npx serve .
     
     # Using VS Code Live Server extension
     Right-click index.html → "Open with Live Server"
     ```

4. **View the website** at `http://localhost:8000` (or your local server URL)

## 📱 Responsive Breakpoints

```css
/* Mobile devices */
@media (max-width: 480px) {
    /* Mobile-specific styles */
}

/* Tablets */
@media (max-width: 768px) {
    /* Tablet-specific styles */
}

/* Desktop */
@media (min-width: 1024px) {
    /* Desktop-specific styles */
}
```

## 🎨 Color Palette

```css
/* Primary Colors */
--primary-gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
--secondary-gradient: linear-gradient(135deg, #ff6b6b, #ffa500);

/* Brand Colors */
--brand-pink: #d4a5a5;
--brand-rose: #c4999c;

/* Neutral Colors */
--white: #ffffff;
--light-gray: #f8f9fa;
--dark-gray: #333333;
--text-gray: #666666;
```

## ⚡ Performance Optimizations

- **CSS optimizations:** Efficient selectors and minimal reflows
- **JavaScript optimizations:** Event delegation and debounced scroll events
- **Image optimization:** Responsive images and proper sizing
- **Animation performance:** GPU-accelerated transforms and opacity changes

## 🔧 Customization

### Updating Content
- **Company Information:** Edit text content in `index.html`
- **Product Details:** Modify product cards in the products section
- **Contact Information:** Update form fields and contact details

### Styling Changes
- **Colors:** Modify CSS custom properties in `styles.css`
- **Typography:** Update font families and sizes
- **Layout:** Adjust Grid and Flexbox properties
- **Animations:** Customize keyframes and transition timings

### Adding Features
- **New Sections:** Follow existing HTML structure patterns
- **Interactive Elements:** Extend JavaScript functionality
- **Form Integration:** Connect contact form to backend service

## 🐛 Browser Compatibility

- **Chrome** 60+ ✅
- **Firefox** 55+ ✅
- **Safari** 12+ ✅
- **Edge** 79+ ✅
- **Mobile browsers** (iOS Safari, Chrome Mobile) ✅

## 📈 Future Enhancements

- [ ] Backend integration for contact form
- [ ] Blog/News section
- [ ] Product detail pages
- [ ] Shopping cart functionality
- [ ] Multi-language support
- [ ] Progressive Web App (PWA) features
- [ ] Advanced animations with JavaScript libraries

## 🤝 Contributing

This project was created as part of a web developer internship assignment. If you'd like to suggest improvements:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Create a Pull Request

## 📄 License

This project is created for educational and internship purposes. All rights reserved by Kyara Beverages.

## 📞 Contact

For any questions about this project or internship application:

- **Email:** careers@kyarabeverages.in
- **Project Creator:** Prateek Singh Chouhan
- **LinkedIn:** https://www.linkedin.com/in/prateek-singh-chouhan-654486243/
- **GitHub:** https://github.com/Prateeksingchn

---

**Built with ❤️ for Kyara Beverages Internship Application**

*Showcasing modern web development skills through innovative design and clean, efficient code.*