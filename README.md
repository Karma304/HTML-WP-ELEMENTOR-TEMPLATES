# Professional SaaS HTML Widgets for WordPress Elementor

A comprehensive collection of professional, semantic HTML widgets specifically designed for creating modern SaaS websites. Each widget follows web standards, uses proper semantic HTML5 elements, and includes built-in responsive styles.

## 📋 Widget Collection

### Navigation & Header
- **header-navigation.html** - Professional sticky navigation bar with mobile menu support, logo placement, and action buttons

### Hero & CTA Sections
- **hero-section.html** - Full-width hero section with headline, subheading, dual CTAs, and stats display
- **cta-primary.html** - Bold call-to-action section with gradient background for maximum conversion
- **cta-secondary.html** - Subtle CTA card with icon, perfect for mid-page conversions
- **video-demo-section.html** - Video demonstration section with feature highlights and play button

### Features & Benefits
- **features-section.html** - Grid-based features showcase with icons, titles, and descriptions
- **integration-showcase.html** - Display available integrations with popular tools and services
- **stats-section.html** - Metrics and statistics section with animated counters and gradient background

### Pricing
- **pricing-section.html** - Three-tier pricing table with feature comparison and popular badge

### Social Proof
- **testimonials-section.html** - Customer testimonials with ratings, quotes, and author details
- **logo-showcase.html** - Client logo display with grayscale hover effects
- **team-section.html** - Team member profiles with photos, bios, and social links

### Forms & Engagement
- **contact-form.html** - Professional multi-field contact form with validation
- **newsletter-signup.html** - Email subscription form with gradient background

### FAQ & Footer
- **faq-section.html** - Collapsible FAQ section using HTML details/summary elements
- **footer-section.html** - Comprehensive footer with multiple columns, social links, and badges

## 🎨 Design Features

### Semantic HTML5
All widgets use proper semantic elements:
- `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`
- ARIA labels and roles for accessibility
- Proper heading hierarchy (h1-h6)
- Semantic form elements with labels

### Professional Styling
- Modern gradient backgrounds
- Smooth transitions and hover effects
- Professional color scheme (customizable)
- Consistent spacing and typography
- Box shadows and visual depth

### Responsive Design
- Mobile-first approach
- Breakpoints at 640px, 768px, and 968px
- Flexible grid layouts
- Touch-friendly interactive elements
- Optimized for all screen sizes

### Accessibility
- ARIA labels and landmarks
- Keyboard navigation support
- Semantic HTML structure
- Proper contrast ratios
- Screen reader friendly

## 🚀 Usage

### Individual Widget Usage
Each widget is self-contained with its own HTML structure and embedded CSS:

```html
<!-- Simply include the widget file -->
<include src="widgets/hero-section.html" />
```

### Customization
Each widget includes CSS variables and classes that can be easily customized:

1. **Colors**: Update the color values in the `<style>` section
2. **Spacing**: Adjust padding and margin values
3. **Typography**: Modify font sizes and weights
4. **Images**: Replace placeholder image sources with your own

### WordPress Elementor Integration
1. Open Elementor editor
2. Add an HTML widget
3. Copy the content of the desired widget file
4. Paste into the HTML widget
5. Customize as needed

## 📐 Widget Specifications

### Color Palette
- **Primary Blue**: #0066ff
- **Secondary Blue**: #00c6ff
- **Success Green**: #10b981
- **Warning Orange**: #f59e0b
- **Purple**: #8b5cf6
- **Pink**: #ec4899
- **Cyan**: #06b6d4
- **Dark**: #1a1a1a
- **Gray**: #666666
- **Light Gray**: #f8f9fa

### Typography
- **Headings**: System font stack with fallbacks
- **Body**: 1rem (16px) base size
- **Line Height**: 1.6 for body text, 1.2 for headings

### Breakpoints
- **Mobile**: < 640px
- **Tablet**: 640px - 968px
- **Desktop**: > 968px

## 🔧 Customization Guide

### Changing Colors
Find and replace color values in the CSS:
```css
/* Primary color */
background: #0066ff; /* Change to your brand color */
```

### Adjusting Spacing
Modify padding and margin values:
```css
padding: 5rem 0; /* Vertical section padding */
gap: 2rem; /* Grid gap between items */
```

### Updating Content
Replace placeholder text and images:
```html
<!-- Update headings -->
<h2>Your Custom Heading</h2>

<!-- Update images -->
<img src="your-image.jpg" alt="Your description">
```

## 📱 Browser Support
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🎯 Best Practices

### Performance
- Use optimized images (WebP format recommended)
- Lazy load images below the fold
- Minify CSS in production
- Use CDN for static assets

### SEO
- Include proper meta descriptions
- Use semantic heading hierarchy
- Add alt text to all images
- Implement structured data where applicable

### Accessibility
- Maintain ARIA labels
- Ensure keyboard navigation
- Test with screen readers
- Maintain color contrast ratios (WCAG AA minimum)

## 🤝 Contributing
Contributions are welcome! Please ensure:
- Semantic HTML5 is used
- Responsive design is implemented
- Accessibility standards are met
- Code is well-commented

## 📄 License
These widgets are provided as-is for use in WordPress Elementor projects.

## 🔗 Additional Resources
- [Elementor Documentation](https://elementor.com/help/)
- [HTML5 Semantic Elements](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)
- [Web Accessibility Guidelines](https://www.w3.org/WAI/standards-guidelines/wcag/)
- [Responsive Web Design](https://web.dev/responsive-web-design-basics/)

---

**Note**: Remember to replace placeholder images and content with your actual assets before deploying to production.
