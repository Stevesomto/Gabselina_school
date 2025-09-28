# Gabselina School Website

A modern, interactive, and responsive school website built with HTML, CSS, and JavaScript featuring a dynamic image slider and beautiful UI design.

## Features

### 🎨 **Interactive Image Slider**
- Automatic slideshow with 5-second intervals
- Manual navigation with arrow buttons
- Clickable indicator dots
- Touch/swipe support for mobile devices
- Keyboard navigation (arrow keys)
- Pause on hover functionality
- Smooth transitions and animations

### 📱 **Responsive Design**
- Mobile-first approach
- Responsive navigation with hamburger menu
- Optimized for all screen sizes
- Touch-friendly interface

### 🎯 **Key Sections**
1. **Hero Section** - Eye-catching landing area with call-to-action
2. **Image Slider** - Showcase school facilities and activities
3. **About Section** - School information with statistics
4. **Academics** - Educational programs and offerings
5. **Gallery** - Photo gallery with lightbox effect
6. **Contact** - Contact form and information
7. **Footer** - Additional links and social media

### ✨ **Interactive Features**
- Smooth scrolling navigation
- Hover effects and animations
- Contact form with validation
- Gallery lightbox
- Mobile menu toggle
- Navbar scroll effects

## File Structure

```
gabselina_school/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## How to Use

### 1. **Open the Website**
- Simply open `index.html` in your web browser
- The website will load with all features working

### 2. **Customize Content**
- Edit `index.html` to change text content, images, and structure
- Modify `styles.css` to change colors, fonts, and layout
- Update `script.js` to modify slider behavior and interactions

### 3. **Replace Images**
The website uses placeholder images from Unsplash. To use your own images:

1. Replace the image URLs in `index.html` with your own image paths
2. Update the hero background image in `styles.css` (line 108)
3. Ensure your images are optimized for web (recommended size: 1000x500px for slider)

### 4. **Customize Colors**
Main color scheme (defined in CSS variables):
- Primary Blue: `#3498db`
- Dark Blue: `#2980b9`
- Dark Gray: `#2c3e50`
- Light Gray: `#f8f9fa`

## Slider Customization

### Add More Slides
1. Add new slide divs in the slider section of `index.html`
2. Add corresponding indicators
3. Update the JavaScript slide count if needed

### Change Slide Timing
- Modify the `slideDelay` variable in `script.js` (currently 5000ms = 5 seconds)

### Disable Auto-slide
- Comment out the `startAutoSlide()` call in `script.js`

## Browser Compatibility

- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers

## Performance Features

- Lazy loading for images
- Optimized animations
- Efficient event handling
- Touch gesture support
- Keyboard accessibility

## Customization Tips

### Change School Name
- Update the title in `<title>` tag
- Change the logo text in the navigation
- Update footer branding

### Add More Sections
- Follow the existing section structure
- Add corresponding navigation links
- Include proper IDs for smooth scrolling

### Modify Contact Form
- The form currently shows a success message
- To make it functional, add backend processing
- Consider using services like Formspree or Netlify Forms

### Add Real Content
- Replace placeholder text with actual school information
- Add real photos of your school
- Include actual contact details
- Add social media links

## Troubleshooting

### Slider Not Working
- Check if JavaScript is enabled in your browser
- Ensure all image URLs are accessible
- Verify that `script.js` is properly linked

### Mobile Menu Issues
- Test on actual mobile devices
- Check touch event handling
- Ensure proper viewport meta tag

### Styling Issues
- Clear browser cache
- Check CSS file path
- Verify font loading

## Future Enhancements

- Add a blog/news section
- Include student portal integration
- Add event calendar
- Implement search functionality
- Add multi-language support
- Include video backgrounds
- Add testimonials section

## Credits

- **Images**: Unsplash (placeholder images)
- **Icons**: Font Awesome
- **Fonts**: Google Fonts (Poppins)
- **Design**: Modern, clean, and professional

## License

This project is open source and available under the MIT License.

---

**Note**: This is a frontend-only website. For production use, consider adding:
- Backend functionality for the contact form
- Content Management System (CMS)
- SEO optimization
- Analytics tracking
- Security measures "# Gabselina_school" 
