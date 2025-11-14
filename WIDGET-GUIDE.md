# Widget Quick Reference Guide

## 🚀 Getting Started

Each widget is a self-contained HTML file with embedded CSS. Simply copy the content of any widget file and paste it into your WordPress Elementor HTML widget.

## 📚 Widget Directory

### 1. Navigation & Header

#### header-navigation.html
**Purpose**: Main site navigation with logo and action buttons  
**Key Features**:
- Sticky header that stays on scroll
- Mobile-responsive hamburger menu
- Logo placement
- Multiple navigation links
- Call-to-action buttons (Sign In, Get Started)

**Best Used**: At the top of every page as the main navigation

---

### 2. Hero Sections

#### hero-section.html
**Purpose**: Large hero banner with headline and CTAs  
**Key Features**:
- Eye-catching gradient background
- Large headline and subheading
- Two CTA buttons (primary and secondary)
- Statistics display (users, uptime, support)
- Image showcase area
- Fully responsive grid layout

**Best Used**: At the top of landing pages, immediately below navigation

---

### 3. Call-to-Action (CTA)

#### cta-primary.html
**Purpose**: Bold, high-conversion CTA section  
**Key Features**:
- Gradient background for visual impact
- Large headline and compelling copy
- Two action buttons
- Trust indicators (no credit card required, free trial, etc.)
- Checkmark icons for features

**Best Used**: Mid-page or bottom of page for conversions

#### cta-secondary.html
**Purpose**: Subtle, card-based CTA  
**Key Features**:
- Clean white card design
- Icon with message
- Single action button
- Less aggressive than primary CTA

**Best Used**: Mid-page between content sections

---

### 4. Features & Benefits

#### features-section.html
**Purpose**: Showcase product features with icons  
**Key Features**:
- 6 feature cards in responsive grid
- Custom SVG icons with colors
- Hover animations
- Descriptions for each feature

**Best Used**: Early on page to explain value proposition

#### integration-showcase.html
**Purpose**: Display available integrations  
**Key Features**:
- 6 integration cards
- Colorful icons
- "Learn more" links
- CTA for viewing all integrations

**Best Used**: Mid-page to show ecosystem compatibility

#### video-demo-section.html
**Purpose**: Video demonstration with context  
**Key Features**:
- Video thumbnail with play button
- Feature bullet points
- CTA button
- 16:9 responsive video wrapper

**Best Used**: After features section to show product in action

---

### 5. Social Proof

#### testimonials-section.html
**Purpose**: Customer testimonials with ratings  
**Key Features**:
- 3 testimonial cards
- 5-star rating display
- Customer photos
- Name, role, and company
- Hover effects

**Best Used**: Mid to late page to build trust

#### logo-showcase.html
**Purpose**: Display client/partner logos  
**Key Features**:
- Grayscale effect
- Hover color reveal
- Responsive grid
- 8 logo placeholders

**Best Used**: Below hero or early on page

#### team-section.html
**Purpose**: Showcase team members  
**Key Features**:
- 4 team member cards
- Large profile photos
- Name, role, bio
- Social media links
- Hover zoom effect on photos

**Best Used**: About page or to humanize brand

---

### 6. Pricing

#### pricing-section.html
**Purpose**: Three-tier pricing table  
**Key Features**:
- 3 pricing tiers (Starter, Professional, Enterprise)
- "Most Popular" badge
- Feature comparison lists
- Different CTAs per tier
- Hover effects
- Trust message at bottom

**Best Used**: Dedicated pricing page or mid-landing page

---

### 7. Data & Metrics

#### stats-section.html
**Purpose**: Display key metrics and statistics  
**Key Features**:
- 4 stat cards with icons
- Large numbers with labels
- Gradient background
- Animated hover effects

**Best Used**: Early on page to establish credibility

---

### 8. Engagement Forms

#### contact-form.html
**Purpose**: Professional contact form  
**Key Features**:
- Multiple input fields (name, email, phone, company)
- Subject dropdown
- Message textarea
- Newsletter opt-in checkbox
- Privacy policy acknowledgment
- Full validation

**Best Used**: Contact page or bottom of landing page

#### newsletter-signup.html
**Purpose**: Email subscription widget  
**Key Features**:
- Gradient card design
- Single email input
- Privacy message
- Compact layout

**Best Used**: Footer area or between sections

---

### 9. FAQ & Support

#### faq-section.html
**Purpose**: Collapsible FAQ section  
**Key Features**:
- 6 common questions
- Native HTML details/summary (no JavaScript needed)
- Smooth expand/collapse
- Chevron icons
- Link to support team

**Best Used**: Bottom of sales pages or dedicated FAQ page

---

### 10. Footer

#### footer-section.html
**Purpose**: Comprehensive site footer  
**Key Features**:
- 5 column layout (brand + 4 link columns)
- Social media icons
- Multiple link sections (Product, Company, Resources, Legal)
- Copyright and compliance badges
- Fully responsive

**Best Used**: Bottom of every page

---

## 🎨 Customization Tips

### Changing Colors
Find the color hex codes in each widget's `<style>` section:
- **Primary**: `#0066ff`
- **Success**: `#10b981`
- **Warning**: `#f59e0b`

### Updating Text
Simply edit the HTML content between tags:
```html
<h2>Your New Heading</h2>
<p>Your new paragraph text</p>
```

### Adding Images
Replace placeholder image sources:
```html
<img src="your-image.jpg" alt="Your description">
```

### Adjusting Spacing
Modify padding values in CSS:
```css
padding: 5rem 0; /* Vertical padding */
gap: 2rem; /* Space between elements */
```

## 📱 Responsive Breakpoints

All widgets are responsive with these breakpoints:
- **Mobile**: < 640px
- **Tablet**: 640px - 968px  
- **Desktop**: > 968px

## ♿ Accessibility Features

Every widget includes:
- Semantic HTML5 elements
- ARIA labels and roles
- Keyboard navigation support
- Proper heading hierarchy
- Alt text for images
- Color contrast compliance

## 🔧 WordPress Elementor Integration

1. Open page in Elementor editor
2. Add HTML widget from left panel
3. Copy content from widget file
4. Paste into HTML widget
5. Adjust settings and preview
6. Update/publish page

## 💡 Suggested Page Layouts

### Landing Page
1. header-navigation.html
2. hero-section.html
3. logo-showcase.html
4. features-section.html
5. stats-section.html
6. pricing-section.html
7. testimonials-section.html
8. cta-primary.html
9. footer-section.html

### About Page
1. header-navigation.html
2. hero-section.html (modified for about)
3. stats-section.html
4. team-section.html
5. testimonials-section.html
6. cta-secondary.html
7. footer-section.html

### Contact Page
1. header-navigation.html
2. contact-form.html
3. faq-section.html
4. footer-section.html

## 🎯 Pro Tips

1. **Consistency**: Use the same color scheme across all widgets
2. **Spacing**: Maintain consistent padding between sections
3. **Images**: Optimize images before upload (WebP format recommended)
4. **Testing**: Always test on mobile devices
5. **Performance**: Load images lazily for better performance
6. **A/B Testing**: Try different CTA button text and colors

## 📞 Support Resources

- See `README.md` for detailed documentation
- Check `example-saas-page.html` for layout inspiration
- Each widget file has inline comments explaining structure

---

**Remember**: These are production-ready widgets, but always replace placeholder content with your actual brand information before going live!
