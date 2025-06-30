# Lofi Drift - 24/7 Chill Beats Landing Page 🎵

A modern, responsive landing page for the Lofi Drift YouTube channel featuring a cozy vaporwave aesthetic, smooth animations, and mobile-first design.

## 🌟 Features

- **Responsive Design**: Mobile-first approach with seamless desktop experience
- **Modern Vaporwave Aesthetic**: Beautiful gradients, glowing effects, and smooth animations
- **YouTube Integration**: Embedded livestream player with custom controls
- **SEO Optimized**: Meta tags, semantic HTML, and fast loading times
- **Interactive Elements**: Smooth scrolling, hover effects, and animated statistics
- **Newsletter Signup**: Email collection form ready for integration
- **Social Media Links**: Easy access to all your social platforms
- **Performance Optimized**: Lazy loading, reduced motion support, and efficient animations

## 🚀 Quick Start

1. **Clone or download** the files to your preferred hosting location
2. **Customize** the content to match your channel details
3. **Deploy** to any web hosting service

## 📁 File Structure

```
lofi-drift/
│
├── index.html          # Main HTML file
├── styles.css          # All styling and animations
├── script.js           # Interactive functionality
└── README.md           # This file
```

## 🎨 Customization Guide

### 1. Channel Information

**Update YouTube Links:**
```html
<!-- In index.html, find and replace: -->
<a href="https://youtube.com/@lofidrift" target="_blank">
<!-- Replace with your actual YouTube channel URL -->
```

**Update YouTube Embed:**
```html
<!-- Replace the iframe src with your stream/video ID: -->
<iframe 
    id="youtube-player"
    src="https://www.youtube.com/embed/YOUR_VIDEO_ID_HERE?autoplay=0&mute=1&controls=1&loop=1&playlist=YOUR_VIDEO_ID_HERE"
    ...>
```

### 2. Social Media Links

Update all social media URLs in the footer:
```html
<a href="https://youtube.com/@lofidrift" target="_blank" class="social-link youtube">
<a href="https://twitter.com/lofidrift" target="_blank" class="social-link twitter">
<a href="https://instagram.com/lofidrift" target="_blank" class="social-link instagram">
<a href="https://discord.gg/lofidrift" target="_blank" class="social-link discord">
```

### 3. Donation/Support Links

Update donation platform URLs:
```html
<a href="https://patreon.com/lofidrift" target="_blank" class="donation-btn patreon">
<a href="https://ko-fi.com/lofidrift" target="_blank" class="donation-btn kofi">
<a href="https://buymeacoffee.com/lofidrift" target="_blank" class="donation-btn coffee">
```

### 4. Colors and Theme

Modify the CSS variables in `styles.css`:
```css
:root {
    --primary-gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    --secondary-gradient: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
    --accent-gradient: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%);
    /* Modify these to change the color scheme */
}
```

### 5. Schedule Content

Update the weekly schedule in the HTML:
```html
<div class="schedule-card">
    <div class="day">Monday</div>
    <div class="theme">Your Theme</div>
    <div class="description">Your description</div>
    <div class="icon"><i class="fas fa-your-icon"></i></div>
</div>
```

## 📧 Newsletter Integration

The newsletter form is ready for integration with popular email services:

### Mailchimp Integration
1. Replace the form action with your Mailchimp form URL
2. Update the JavaScript in `script.js` to handle Mailchimp responses

### ConvertKit Integration
1. Add your ConvertKit form ID
2. Include ConvertKit's JavaScript library
3. Update the form submission handler

### Custom Backend
1. Create an API endpoint to handle email submissions
2. Update the `initFormHandling()` function in `script.js`
3. Add proper validation and error handling

## 🌐 Deployment Options

### 1. Netlify (Recommended)
1. Drag and drop your files to Netlify
2. Connect to GitHub for automatic deployments
3. Custom domain support included

### 2. Vercel
1. Import from GitHub repository
2. Automatic deployments on push
3. Edge network for fast loading

### 3. GitHub Pages
1. Upload to a GitHub repository
2. Enable GitHub Pages in repository settings
3. Access via `yourusername.github.io/repository-name`

### 4. Traditional Web Hosting
1. Upload files via FTP/cPanel
2. Ensure all files are in the public_html directory
3. Access via your domain

## 🔧 Advanced Customization

### Adding Google Analytics
Add this to the `<head>` section:
```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_TRACKING_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_TRACKING_ID');
</script>
```

### Custom Domain Setup
1. Purchase a domain from a registrar
2. Point DNS to your hosting provider
3. Update social media links to use the new domain

### Performance Optimization
- Enable Gzip compression on your server
- Use a CDN for faster global loading
- Optimize images before uploading
- Consider using WebP format for images

## 🎵 Now Playing Widget

The "Now Playing" section is currently a placeholder. To make it functional:

1. **OBS Integration**: Use OBS browser source to display track info
2. **API Integration**: Connect to music streaming APIs
3. **Manual Updates**: Use a simple admin panel to update track info
4. **JSON Feed**: Create a JSON file that updates with current track

## 📱 Mobile Optimization

The site is fully responsive with:
- Mobile-first CSS approach
- Touch-friendly button sizes
- Optimized font sizes for mobile
- Collapsible navigation menu
- Fast loading on mobile networks

## 🐛 Troubleshooting

### YouTube Player Not Loading
- Check if the video ID is correct
- Ensure the video is set to public or unlisted
- Verify iframe embed permissions

### Animations Not Working
- Check if JavaScript is enabled
- Verify all CSS files are loading
- Test in different browsers

### Mobile Issues
- Test on actual devices, not just browser dev tools
- Check viewport meta tag is present
- Verify touch events are working

## 🤝 Contributing

Feel free to fork this project and customize it for your own use! If you make improvements that could benefit others, consider sharing them.

## 📄 License

This project is open source and available under the MIT License. You're free to use, modify, and distribute it as needed.

## 🎉 Easter Eggs

Try the Konami Code (↑↑↓↓←→←→BA) for a fun surprise! 🌙

---

**Ready to go live?** Just update the URLs and content, then deploy to your favorite hosting service. Your audience will love the smooth, modern experience! 🚀
