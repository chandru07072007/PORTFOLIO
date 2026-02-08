# Portfolio Website

A modern, responsive portfolio website inspired by clean minimalist design principles.

## Features

✨ **Modern Design**
- Clean, minimalist aesthetic with a light color scheme
- Professional black & white profile photo
- Vibrant accent colors (Orange, Red, Cyan)
- Smooth animations and transitions

🎨 **Sections**
- **Hero Section**: Large profile photo with introduction and CTA buttons
- **Resume**: Professional experience, education, and skills
- **Projects**: Showcase of work with project cards
- **Contact/Footer**: Contact information and social media links

📱 **Responsive**
- Fully responsive design that works on all devices
- Mobile-friendly navigation
- Optimized for tablets and desktops

⚡ **Performance**
- Vanilla HTML, CSS, and JavaScript (no frameworks)
- Fast loading times
- Smooth scroll behavior
- Intersection Observer for optimized animations

## File Structure

```
portfolio/
├── index.html          # Main HTML file
├── style.css           # Stylesheet with design system
├── script.js           # JavaScript for interactions
├── profile.jpg         # Profile photo
└── README.md           # This file
```

## Customization Guide

### 1. Update Personal Information

**In `index.html`:**
- Line 18: Update the `<title>` tag
- Line 23-26: Change logo name and subtitle
- Line 27-31: Update navigation links
- Line 40-47: Modify hero section text
- Lines 60-100: Update resume content (experience, education, skills)
- Lines 110-150: Update project information
- Lines 160-180: Update footer contact information

### 2. Change Colors

**In `style.css` (lines 11-16):**
```css
--color-orange: #ff9500;  /* Change to your preferred color */
--color-red: #ff3b30;     /* Change to your preferred color */
--color-cyan: #5ac8fa;    /* Change to your preferred color */
```

### 3. Replace Profile Photo

Replace `profile.jpg` with your own photo. For best results:
- Use a square image (recommended: 640x640px or larger)
- Professional headshot style
- Good lighting and clear background

### 4. Update Projects

Replace the project images in the `<img>` tags with your own project screenshots or use the Unsplash URLs as placeholders.

### 5. Add Your Social Media Links

**In `index.html` (lines 165-170):**
```html
<a href="YOUR_LINKEDIN_URL" class="social-link">
<a href="YOUR_TWITTER_URL" class="social-link">
```

## How to Use

### Local Development

1. Open `index.html` in your web browser
2. Or use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve
   ```

### Deployment

You can deploy this portfolio to:
- **GitHub Pages**: Push to a GitHub repo and enable Pages
- **Netlify**: Drag and drop the folder
- **Vercel**: Connect your Git repository
- **Any web hosting**: Upload files via FTP

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Credits

- Font: [Inter](https://fonts.google.com/specimen/Inter) from Google Fonts
- Icons: [Font Awesome](https://fontawesome.com/)
- Design inspired by modern portfolio trends

## License

Feel free to use this template for your personal portfolio. Customize it to make it your own!

---

**Built with ❤️ using vanilla HTML, CSS, and JavaScript**
