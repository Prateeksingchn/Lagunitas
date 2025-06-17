# Kyara Beverages - Official Website

> **Refreshment, Reimagined** - A premium website for Kyara Beverages, showcasing innovative millet-based fruit drinks with a modern, responsive design.

## 🚀 Project Overview

This project is a complete website redesign for **Kyara Beverages**, a health-focused beverage company specializing in millet-based fruit drinks. The website combines modern web design principles with smooth user experience to represent the brand's mission of reimagining traditional refreshment.

## ✨ Features

### 🎨 Design & User Experience
- **Smooth Scroll Animation** using Locomotive Scroll
- **Dynamic Animations** powered by GSAP (GreenSock Animation Platform)
- **Interactive Elements** with hover effects and micro-interactions
- **Premium Color Palette** with health-focused colors:
  - Soft green (#7eb77f) - Representing health and nature
  - Warm gold (#e8c07d) - Representing millet
  - Soft coral (#e27d60) - Representing fruit flavors
- **Parallax Effects** for engaging visual appeal

### 📱 Responsive Design
- **Flexible Layout** ensuring proper display across devices
- **TailwindCSS Integration** for utility-first styling
- **CSS Grid & Flexbox** for modern layouts

### 🔧 Technical Features
- **Semantic HTML5** structure for accessibility
- **CSS3 Advanced Features** (Custom Properties, Animations, Gradients)
- **GSAP Animation Library** for scroll-triggered animations
- **Locomotive Scroll** for smooth scrolling experience

## 📁 Project Structure

```
├── index.html          # Main HTML file
├── style.css           # CSS styling
├── script.js           # JavaScript for animations and interactions
├── README.md           # Project documentation
└── img/                # Image assets
    ├── grain-texture.svg
    ├── hero-bg.svg
    ├── kyara-logo.svg
    ├── millet-berry.svg
    ├── millet-citrus.svg
    ├── millet-mango.svg
    └── ... (other images)
```

## 🛠️ Technologies Used

- **HTML5** - Semantic markup and structure
- **CSS3** - Modern styling with advanced features:
  - CSS Custom Properties (Variables)
  - Media Queries for responsiveness
- **JavaScript (ES6+)** - Interactive functionality:
  - GSAP for animations
  - Locomotive Scroll for smooth scrolling
  - ScrollTrigger for scroll-based animations
- **External Libraries**:
  - GSAP (GreenSock Animation Platform)
  - Locomotive Scroll
  - TailwindCSS
  - Remix Icon

## 🌟 Key Sections

### 1. Hero Section
- Dynamic tagline: "Refreshment, Reimagined"
- Animated product showcase with GSAP animations
- Naturally Nourishing Millet Beverages branding

### 2. Product Specifications
- Premium Collection heading
- Millet Mango product showcase
- Health-focused specifications (Calories, Protein, Fiber)

### 3. Brand Story
- Company mission focused on ancient grains and sustainable farming
- Health benefits of millet-based drinks
- Nutritional information

### 4. Health Benefits
- Detailed information about antioxidants, essential minerals, and digestive health
- Visual representation of ingredients

### 5. Product Range
- Showcase of different flavors (Mango, Berry, Citrus)
- Special tags for bestsellers and new flavors

### 6. Lifestyle Integration
- "Drink Well, Live Well" section
- Ideas for incorporating millet drinks into daily routines

### 7. Merchandise
- "WEAR YOUR WELLNESS" section
- Eco-friendly merchandise promotion

### 8. Social Media Gallery
- #KYARABEVERAGES social media showcase
- Community engagement

### 9. Footer
- Brand information and navigation
- Newsletter signup
- Social media links

## 🚀 Getting Started

### Prerequisites
- Any modern web browser (Chrome, Firefox, Safari, Edge)
- Text editor (VS Code, Sublime Text, etc.) for modifications

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
     npx http-server .
     
     # Using VS Code Live Server extension
     Right-click index.html → "Open with Live Server"
     ```

4. **View the website** at `http://localhost:8000` (or your local server URL)

## 🎨 Color Palette

```css
/* Primary Colors */
--primary: #7eb77f; /* Soft green for health/nature */
--secondary: #e8c07d; /* Warm gold for millet */
--accent: #e27d60; /* Soft coral for fruit */
--light: #f9f5f0; /* Cream background */
--dark: #4a4a4a; /* Soft black for text */

/* Gradients */
--gradient-primary: linear-gradient(135deg, var(--primary), #a6dcb0);
--gradient-secondary: linear-gradient(135deg, var(--secondary), #f2d9a9);
--gradient-accent: linear-gradient(135deg, var(--accent), #f2a990);
```

## ⚡ Performance Optimizations

- **GSAP optimizations:** Efficient animations with minimal reflows
- **Locomotive Scroll:** Smooth scrolling with optimized performance
- **Image optimization:** SVG usage for scalable, lightweight graphics
- **Animation performance:** GPU-accelerated transforms

## 🔧 Customization

### Updating Content
- **Product Information:** Edit text content in `index.html`
- **Product Details:** Modify product sections
- **Images:** Replace SVG files in the img directory

### Styling Changes
- **Colors:** Modify CSS custom properties in `style.css`
- **Typography:** Update font families and sizes
- **Animations:** Customize GSAP animations in `script.js`

## 🐛 Browser Compatibility

- **Chrome** 60+ ✅
- **Firefox** 55+ ✅
- **Safari** 12+ ✅
- **Edge** 79+ ✅
- **Mobile browsers** (iOS Safari, Chrome Mobile) ✅

## 📈 Future Enhancements

- [ ] Backend integration for contact form
- [ ] E-commerce functionality
- [ ] Product detail pages
- [ ] Shopping cart functionality
- [ ] User accounts and preferences
- [ ] Progressive Web App (PWA) features

## 📄 License

This project is created for Kyara Beverages. All rights reserved.

---

**Built with ❤️ for Kyara Beverages**

*Showcasing modern web development with innovative design and smooth animations.*