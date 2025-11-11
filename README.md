# Bound Bible Website

A static website for the Bound Bible mobile app, featuring a mobile-friendly design with a main landing page and privacy policy.

## Project Structure

```
BoundBibleWebsite/
├── index.html          # Main landing page
├── privacypolicy.html   # Privacy policy page
├── styles.css          # Stylesheet with mobile-responsive design
├── images/             # Directory for app screenshots
│   ├── app-screenshot-1.png  # App screenshot 1 (needs to be added)
│   ├── app-screenshot-2.png  # App screenshot 2 (needs to be added)
│   └── app-screenshot-3.png  # App screenshot 3 (needs to be added)
└── README.md           # This file
```

## Features

- **Mobile-friendly responsive design** - Works great on all device sizes
- **Modern, clean design** with gradient backgrounds and smooth transitions
- **App store buttons** - Ready for real App Store and Google Play links
- **SEO optimized** with proper meta tags and semantic HTML
- **Accessibility features** including focus states and reduced motion support

## Pages

### Main Page (`index.html`)
- Hero section with app title and description
- Three app screenshot mockups
- Download buttons for App Store and Google Play
- About Us section
- Footer with copyright and contact information

### Privacy Policy (`privacypolicy.html`)
- Complete privacy policy template
- Mobile-friendly layout
- Navigation back to main page

## Setup Instructions

1. **Add App Screenshots**: Place your actual app screenshots in the `images/` directory with these names:
   - `app-screenshot-1.png`
   - `app-screenshot-2.png` 
   - `app-screenshot-3.png`

2. **Update App Store Links**: In `index.html`, replace the `#` in the app store button `href` attributes with your actual app store URLs:
   ```html
   <a href="YOUR_APP_STORE_URL" class="app-store-btn apple-store">
   <a href="YOUR_GOOGLE_PLAY_URL" class="app-store-btn google-play">
   ```

3. **Customize Content**: Update any text, colors, or styling in `styles.css` to match your brand.

## Deployment

This is a static website that can be hosted on:
- GitHub Pages
- Netlify
- Vercel
- Any web hosting service

Simply upload all files to your web host and the site will be live.

## Mobile Optimization

The website is fully responsive and includes:
- Mobile-first CSS design
- Touch-friendly buttons and links
- Optimized images and layout for small screens
- Fast loading times

## Browser Support

The website supports all modern browsers including:
- Chrome/Safari/Firefox (latest versions)
- Mobile Safari (iOS)
- Chrome Mobile (Android)
- Internet Explorer 11+ (with graceful degradation)

## Contact

For questions about this website, contact: support@bound-bible.com
