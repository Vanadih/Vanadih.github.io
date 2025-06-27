# Vanadih Bharat Foundation Landing Page

A modern, mobile-responsive landing page for Vanadih Bharat Foundation, a Section 8 nonprofit organization working on rural development in India.

## Features

- **Modern Design**: Clean, professional layout with earthy color palette
- **Mobile Responsive**: Optimized for all device sizes
- **Interactive Elements**: Smooth animations and hover effects
- **Accessibility**: Semantic HTML and keyboard navigation
- **Performance**: Optimized loading and smooth scrolling

## Color Palette

The design uses an earthy, warm color scheme:
- **Ochre**: #D68C45 (Primary accent)
- **Forest Green**: #2D5016 (Primary brand color)
- **Handloom Beige**: #F5F1E8 (Background)
- **Dark Brown**: #4A3728 (Text and accents)
- **Light Ochre**: #E8B366 (Hover states)

## File Structure

```
vandih/
├── index.html          # Main HTML structure
├── styles.css          # All styling and responsive design
├── script.js           # Interactive features and animations
└── README.md           # This file
```

## Sections Included

1. **Hero Section**: Main headline with CTA button
2. **About Section**: Organization description with impact statistics
3. **Impact Highlights**: Key metrics in card format
4. **Projects Section**: Featured initiatives with icons
5. **CSR & Donation**: Call-to-action for corporate partnerships
6. **Testimonials**: Success story from beneficiaries
7. **Contact & Footer**: Contact information and social links

## Setup Instructions

1. **Local Development**:
   ```bash
   # Simply open index.html in your browser
   open index.html
   ```

2. **Live Server** (recommended for development):
   ```bash
   # If you have Node.js installed
   npx live-server
   
   # Or use Python
   python -m http.server 8000
   ```

3. **Deployment**:
   - Upload all files to your web hosting service
   - Ensure all files are in the same directory
   - The page will work immediately without any build process

## Customization Guide

### Content Updates

1. **Text Content**: Edit the HTML file directly
2. **Images**: Replace the SVG background in CSS or add actual images
3. **Colors**: Modify CSS variables in `:root` section
4. **Fonts**: Change Google Fonts import in HTML head

### Adding Real Images

Replace the placeholder SVG background in `styles.css`:

```css
.hero-background {
    background: linear-gradient(rgba(45, 80, 22, 0.7), rgba(74, 55, 40, 0.7)),
                url('path/to/your/image.jpg');
}
```

### Contact Information

Update the footer section in `index.html`:
- Email address
- Phone number
- Social media links
- Physical address

### Form Integration

The CTA buttons currently show alert messages. To integrate with forms:

1. **Contact Forms**: Replace alert with form submission
2. **Email Integration**: Use services like Formspree or Netlify Forms
3. **CRM Integration**: Connect to your preferred CRM system

### Analytics

Add Google Analytics or other tracking:

```html
<!-- Add to <head> section -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Features

- **Lazy Loading**: Images and animations load on scroll
- **Smooth Scrolling**: Native CSS scroll-behavior
- **Optimized Animations**: Hardware-accelerated transforms
- **Minimal Dependencies**: Only Font Awesome for icons

## Accessibility Features

- Semantic HTML structure
- ARIA labels for interactive elements
- Keyboard navigation support
- High contrast color scheme
- Screen reader friendly

## SEO Optimization

The page includes:
- Proper meta tags
- Semantic HTML structure
- Descriptive headings
- Alt text placeholders for images

## Future Enhancements

Consider adding:
- **Blog Section**: Latest news and updates
- **Donation Portal**: Direct online donations
- **Volunteer Registration**: Sign-up forms
- **Project Gallery**: Photo/video showcase
- **Newsletter Signup**: Email marketing integration
- **Multi-language Support**: Hindi and other regional languages

## Support

For customization help or technical support, refer to:
- HTML/CSS documentation
- JavaScript ES6+ features
- Modern web development best practices

## License

This template is created for Vanadih Bharat Foundation. Customize freely for your organization's needs.

---

**Built with ❤️ for rural development in India** 