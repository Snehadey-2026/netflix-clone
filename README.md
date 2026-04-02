# Netflix Home Page - UI Clone

A professional and responsive Netflix home page interface built with HTML5, CSS3, and Bootstrap 5.

## 📋 Project Overview

This project creates a fully functional Netflix homepage UI with three main sections:

### **1. Header Section**
- Netflix logo with brand identity
- Sticky navigation bar that stays at the top while scrolling
- Language selection dropdown (English, हिन्दी, Tamil, Telugu, Kannada)
- Sign In button with hover effects
- Responsive mobile menu

### **2. Body Section**
- **Hero Banner** with attractive background image and call-to-action
- **Email Signup** section to collect user emails
- **Trending Now** section showcasing popular content
- **Why Choose Netflix** feature cards highlighting key benefits
- **Recommended For You** content carousel
- **FAQ (Frequently Asked Questions)** accordion with 5 common questions
- Smooth animations and hover effects on all interactive elements

### **3. Footer Section**
- Multiple link categories (Company, Community, Legal, Career)
- Language selector
- Copyright and legal information
- Contact and feedback links
- Professional dark theme styling

## 🛠️ Technologies Used

1. **HTML5** - Semantic markup and structure
2. **CSS3** - Advanced styling, animations, and responsive design
3. **Bootstrap 5** - Responsive grid system and components
4. **Font Awesome** - High-quality icons
5. **Google Fonts** - Montserrat font family

## 📁 Project Structure

```
NETFLIX PROJECT/
├── index.html          # Main HTML file with all sections
├── style.css           # Custom CSS styles
└── README.md          # Project documentation
```

## 🎨 Key Features

### Visual Design
- Netflix dark theme with red accent color (#e50914)
- Professional typography using Montserrat font family
- Smooth transitions and animations
- Advanced gradient overlays
- Custom scrollbar styling

### Responsive Layout
- Mobile-first design approach
- Fully responsive on all screen sizes:
  - 📱 Mobile (320px and up)
  - 📱 Tablets (768px and up)
  - 💻 Desktop (1024px and up)

### Interactive Elements
- Hover effects on cards and buttons
- Dropdown language selector
- Expandable FAQ accordion
- Smooth color transitions
- Scale animations on hover

### Accessibility
- Proper semantic HTML structure
- Focus states for keyboard navigation
- ARIA labels for screen readers
- Color contrast compliance
- Mobile-friendly viewport settings

## 🚀 How to Use

### Opening the Project
1. Navigate to the project folder: `c:\Users\SNEHA DEY\Desktop\NETFLIX PROJECT`
2. Open `index.html` in your web browser
3. View the responsive design by resizing your browser window

### Customization

#### Change Hero Background Image
Edit this line in `index.html` (line ~75):
```html
<div class="hero-bg" style="background-image: url('YOUR_IMAGE_URL');"></div>
```

#### Change Movie Images
Replace image URLs in the movie card sections with your own images

#### Modify Colors
Edit the CSS variables in `style.css` (lines 1-7):
```css
:root {
    --netflix-red: #e50914;        /* Main red color */
    --netflix-dark: #141414;       /* Dark background */
    --netflix-darker: #0f0f0f;     /* Darker background */
}
```

#### Update Text Content
All text content is editable directly in `index.html`

## 📱 Responsive Breakpoints

The design responds perfectly to:
- **Extra Small (XS)**: < 576px (Mobile phones)
- **Small (SM)**: ≥ 576px (Landscape phones)
- **Medium (MD)**: ≥ 768px (Tablets)
- **Large (LG)**: ≥ 992px (Desktops)
- **Extra Large (XL)**: ≥ 1200px (Large screens)

## 🎯 Section Details

### Header Navigation
- Sticky positioning keeps it visible while scrolling
- Transparent background that becomes opaque on scroll
- Mobile toggle button for hamburger menu
- Language dropdown with 5 options
- Red Sign In button with hover effects

### Hero Section
- Full-width banner with background image
- Gradient overlay for text readability
- Large headline and description
- Two CTA buttons: "Play" and "More Info"
- Responsive text sizing

### Signup Section
- Email input field with placeholder
- "Get Started" button
- Helpful descriptive text

### Content Sections
- Grid layouts for movie cards
- Hover animations showing play buttons
- 4x responsive grid system
- Multiple content categories

### FAQ Accordion
- 5 frequently asked questions
- Smooth collapse/expand animations
- Dark theme styling
- Accessible keyboard navigation

### Footer
- 4 link categories with proper hierarchy
- Language selector
- Legal information
- Responsive grid layout
- Contact and feedback options

## 🎬 Demo Content

The page includes:
- Sample movie poster images
- Featured content sections
- FAQ answers
- Placeholder text

All can be easily replaced with real Netflix content.

## ✨ CSS Features

- **Modern CSS Grid & Flexbox** for layouts
- **CSS Variables** for easy theme customization
- **Smooth Transitions** (0.3s ease)
- **Custom Animations** (fade-in effects)
- **Backdrop Filters** for modern effects
- **Advanced Gradients** for visual depth
- **Custom Scrollbar** styling

## 🔧 Browser Compatibility

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📖 Code Organization

### HTML Structure
```
Header (Navigation)
└── Logo, Language Selector, Sign In

Main Content
├── Hero Section
│   ├── Background Image
│   └── CTA Buttons
├── Signup Section
├── Trending Now
├── Feature Cards
├── Recommended Content
└── FAQ Accordion

Footer
├── Link Categories
├── Language Selector
└── Legal Info
```

### CSS Organization
```
1. Root Variables & General Styles
2. Header Styles
3. Hero Section Styles
4. Body Section Styles
5. Movie Cards & Features
6. FAQ Styles
7. Footer Styles
8. Responsive Design (Media Queries)
9. Animations
```

## 🎓 Learning Outcomes

This project demonstrates:
- ✅ Semantic HTML5 structure
- ✅ Advanced CSS3 techniques
- ✅ Bootstrap 5 framework expertise
- ✅ Responsive web design
- ✅ UI/UX best practices
- ✅ Accessibility compliance
- ✅ Modern web animations
- ✅ Form design patterns

## 📝 Notes

- All images use CDN URLs (Wikimedia Commons, Unsplash) for demo purposes
- Replace with your own images for production use
- Font Awesome icons are loaded via CDN
- Bootstrap is loaded via CDN for quick setup
- Google Fonts are loaded for typography

## 🚀 Future Enhancements

Potential additions:
- [ ] JavaScript for interactive features
- [ ] Video player integration
- [ ] Search functionality
- [ ] User authentication UI
- [ ] Content filtering/categories
- [ ] Watch list management
- [ ] User review section
- [ ] Live chat support

## 📄 License

This is an educational project inspired by Netflix design patterns.

## 👤 Creator

Netflix Home Page UI Clone - February 2026

---

**Enjoy exploring the Netflix UI Clone! 🎬🍿**
