# Agencio - Creative Agency Landing Page

A modern, responsive landing page for a creative agency built with HTML and Tailwind CSS.

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Sections](#sections)
- [Responsive Design](#responsive-design)
- [Browser Support](#browser-support)

## 🎯 Overview

Agencio is a beautifully designed, fully responsive landing page showcasing a creative agency's services, pricing plans, testimonials, and more. The design emphasizes modern aesthetics with smooth animations and a clean user interface.

## ✨ Features

- **Fully Responsive Design** - Optimized for mobile, tablet, and desktop devices
- **Modern UI/UX** - Clean, professional design with smooth transitions
- **Interactive Elements** - Hover effects and animations throughout
- **Accessible** - Semantic HTML with proper alt text for images
- **Performance Optimized** - Lightweight and fast loading
- **Cross-browser Compatible** - Works on all modern browsers

## 🛠 Technologies Used

- **HTML5** - Semantic markup
- **Tailwind CSS v4** - Utility-first CSS framework (via CDN)
- **Google Fonts** - Rubik font family
- **Vanilla JavaScript** - No frameworks required

## 📁 Project Structure

```
html-css-mini-project/
│
├── index.html              # Main HTML file
├── tailwind.config.js      # Tailwind configuration
├── README.md              # Project documentation
│
└── images/                # Image assets
    ├── dev1/              # Header & Hero section images
    ├── dev2-services-section/
    ├── dev2-take-your-hand-section/
    ├── dev3/
    │   ├── pricePlan/
    │   └── testimonial/
    └── img.Div.Q/         # Footer & Newsletter images
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- A local web server (optional, for development)

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd html-css-mini-project
```

2. Open the project:
   - **Option 1**: Simply open `index.html` in your web browser
   - **Option 2**: Use a local development server:
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js (http-server)
     npx http-server
     
     # Using PHP
     php -S localhost:8000
     ```

3. Navigate to `http://localhost:8000` (or your chosen port)

## 📑 Sections

The landing page consists of the following sections:

### 1. **Header & Navigation**
- Responsive navigation bar
- Mobile hamburger menu
- Desktop navigation links
- Call-to-action button

### 2. **Hero Section**
- Eye-catching hero image with overlays
- Compelling headline and description
- Primary and secondary action buttons
- Animated elements

### 3. **Services Section**
- Four service cards showcasing:
  - Increase conversion
  - Discussion for idea
  - Product analytics
  - Perfect testing
- Decorative elements for large screens

### 4. **Take Your Hand Section**
- Feature showcase with images
- Skewed background design
- Call-to-action button

### 5. **Pricing Plan Section**
- Comparison table with three tiers:
  - Regular ($2000)
  - Premium ($3000)
  - Corporate ($5000)
- Feature comparison with checkmarks and crosses
- Plan selection buttons

### 6. **Testimonial Section**
- Customer testimonial with image
- Quote display
- Author information

### 7. **Newsletter Section**
- Email subscription form
- Modern input design

### 8. **Footer**
- Company information
- Social media links
- Navigation links (desktop)
- Accordion menu (mobile)
- Copyright information

## 📱 Responsive Design

The page is designed with a mobile-first approach:

- **Mobile**: Optimized for screens < 1024px
- **Tablet**: Optimized for screens ≥ 1024px
- **Desktop**: Optimized for screens ≥ 1440px

### Breakpoints Used:
- `lg:` - Large screens (≥ 1024px)
- `xl:` - Extra large screens (≥ 1280px)
- `min-[550px]:` - Custom breakpoint at 550px
- `min-[551px]:` - Custom breakpoint at 551px

## 🌐 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Opera (latest)

## 🎨 Color Palette

- **Primary Blue**: `#1374F6`
- **Dark Blue**: `#0B0757`
- **Light Blue**: `#1F1E61`
- **Yellow**: `#FDD76E` / `#FDC46E`
- **Green**: `#00B894`
- **Gray**: `#8480AE`
- **Light Gray**: `#F4F7FC`
- **White**: `#FFFFFF`

## 📝 Notes

- All images should be placed in the `images/` directory
- Image paths use relative paths (e.g., `images/dev1/agencio-logo.svg`)
- Tailwind CSS is loaded via CDN for easy setup
- No build process required - just open and view!

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

Created with ❤️ for the Agencio Creative Agency

---

**Note**: This is a static HTML/CSS project. For production use, consider:
- Adding form validation for the newsletter section
- Implementing actual form submission functionality
- Adding JavaScript for interactive features
- Optimizing images for web
- Setting up a build process for production

