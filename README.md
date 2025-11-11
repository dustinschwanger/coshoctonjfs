# Coshocton County Department of Job & Family Services Website

Official website for the Coshocton County Department of Job and Family Services, providing information and resources for public assistance, child support, child and adult protective services, foster care, adoption, and workforce development.

## Features

- 🌐 **WCAG 2.2 AA Compliant** - Fully accessible website meeting latest accessibility standards
- 📱 **Responsive Design** - Optimized for desktop, tablet, and mobile devices
- 🎨 **USWDS Design System** - Built with the U.S. Web Design System
- ⚡ **Fast Performance** - Optimized assets and efficient caching
- 🔒 **Secure** - Security headers and best practices implemented

## Accessibility Features

This website has been designed to be 100% WCAG 2.2 AA compliant, including:

- Proper heading hierarchy
- Comprehensive ARIA labels and roles
- Enhanced focus indicators
- Keyboard navigation support
- Sufficient color contrast ratios
- Minimum target sizes (44x44px for interactive elements)
- Skip navigation links
- Screen reader friendly markup
- Form autocomplete attributes

## Technology Stack

- HTML5
- CSS3 with USWDS Framework
- Vanilla JavaScript
- Node.js + Express (for serving)
- Font Awesome icons

## Local Development

1. Install dependencies:
   ```bash
   npm install
   ```

2. Start the development server:
   ```bash
   npm start
   ```

3. Open your browser to `http://localhost:3000`

## Deployment

### Railway Deployment

This site is configured for easy deployment on [Railway](https://railway.app):

1. Connect your GitHub repository to Railway
2. Railway will automatically detect the Node.js project
3. The site will be built and deployed automatically
4. Your site will be available at the provided Railway URL

### Environment Variables

No environment variables are required for basic deployment. The application uses `PORT` environment variable automatically provided by Railway.

### Manual Deployment

If deploying manually:

```bash
# Install dependencies
npm install

# Set PORT environment variable (optional)
export PORT=3000

# Start the server
npm start
```

## Project Structure

```
.
├── index.html          # Main HTML file
├── styles.css          # Custom styles
├── server.js           # Express server
├── package.json        # Node.js dependencies
├── public/             # Public assets (images)
│   ├── adoption.png
│   ├── child-care.jpg
│   ├── child-protective.png
│   ├── child-support.png
│   ├── food-assistance.jpg
│   ├── job.png
│   ├── medicaid.jpg
│   └── workforce.png
├── hero.png           # Hero background image
├── logo.png           # Site logo
└── favicon_1.ico      # Favicon
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- Gzip compression enabled
- Static asset caching (1 day)
- Optimized images
- Minimal JavaScript
- CDN-hosted libraries (USWDS, Font Awesome)

## Security

The following security headers are implemented:

- `X-Content-Type-Options: nosniff`
- `X-Frame-Options: SAMEORIGIN`
- `X-XSS-Protection: 1; mode=block`
- `Referrer-Policy: strict-origin-when-cross-origin`

## License

© 2024 Coshocton County Department of Job & Family Services. All rights reserved.

## Support

For technical support or questions about the website, please contact:
- Email: info@coshoctonjfs.org
- Phone: 740-622-1020
- Address: 725 Pine Street, Coshocton, OH 43812

## Credits

Built with accessibility and user experience in mind, following U.S. federal web standards and best practices.
