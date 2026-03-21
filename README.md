# EMF Consultants Website

A modern, responsive professional website for EMF Consultants - a tax consulting firm specializing in KRA compliance and Airbnb tax support in Kenya.

## Features

- **Responsive Design**: Fully responsive layout that works on all devices
- **Modern UI**: Clean corporate design with professional color scheme (dark blue, white, gold accents)
- **Smooth Animations**: Subtle scroll animations and transitions
- **Interactive Elements**: FAQ accordion, mobile navigation, contact form
- **SEO Optimized**: Semantic HTML structure with proper meta tags

## Pages & Sections

1. **Home** - Hero section with call-to-action buttons
2. **About Us** - Company overview with statistics
3. **Services** - Six key service offerings displayed in cards
4. **Airbnb Tax Support** - Specialized section for Airbnb hosts
5. **Why Choose Us** - Four key differentiators
6. **Testimonials** - Client reviews
7. **FAQ** - Common questions about Airbnb taxes
8. **Contact** - Contact form and information

## Technologies Used

- HTML5
- CSS3 (with CSS Grid and Flexbox)
- Vanilla JavaScript
- Font Awesome Icons
- Google Fonts (Segoe UI)

## Setup Instructions

1. Download all files to a folder
2. Open `index.html` in a web browser
3. No build process or dependencies required

## Customization

### Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #1a3a5c;
    --secondary-color: #2c5f8d;
    --accent-color: #d4af37;
}
```

### Contact Information
Update the contact details in `index.html`:
- Phone number
- Email address
- Office address

### Images
Replace placeholder images with your own:
- Logo: Add your logo in the navigation
- Hero background: Update the URL in `.hero-overlay`
- About section image: Replace the Unsplash URL

### Form Submission
The contact form currently shows an alert. To connect it to a backend:
1. Update the form submission handler in `script.js`
2. Add your API endpoint or email service integration

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance

- Fast loading with minimal dependencies
- Optimized images (use compressed versions in production)
- Efficient CSS and JavaScript

## Future Enhancements

- Add blog section for tax tips
- Integrate with email service (e.g., EmailJS, Formspree)
- Add client portal login
- Implement booking system
- Add multilingual support (English/Swahili)

## License

© 2026 EMF Consultants. All rights reserved.

## Contact

For website support or inquiries:
- Email: info@emfconsultants.co.ke
- Phone: +254 XXX XXX XXX
