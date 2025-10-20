# Portfolio Website - Evelia Veldrine Kaharwa

A modern, responsive, and feature-rich portfolio website showcasing skills, certifications, and projects. Built with HTML, CSS, and JavaScript.

## ✨ Features

### Design & UI
- **Modern Hero Section** - Eye-catching landing area with animated elements
- **Dark Mode Toggle** - Seamless theme switching with localStorage persistence
- **Smooth Animations** - Fade-in effects, hover transitions, and floating elements
- **Gradient Backgrounds** - Beautiful color gradients throughout the site
- **Responsive Design** - Fully optimized for desktop, tablet, and mobile devices
- **Accessibility** - ARIA labels, semantic HTML, and keyboard navigation support

### Content Sections
- **About Me** - Introduction with statistics showcase
- **Skills & Expertise** - Interactive skill cards with progress bars
- **Featured Projects** - Grid layout showcasing certifications and job simulations
- **Contact** - Multiple contact methods including social media links and QR code
- **Certifications** - Highlighted achievements from FreeCodeCamp and job simulations

### Interactive Features
- **Smooth Scrolling** - Seamless navigation between sections
- **Scroll to Top Button** - Quick return to top of page
- **Intersection Observer** - Animations triggered on scroll
- **Hover Effects** - Interactive elements with visual feedback
- **Theme Persistence** - User's dark/light mode preference saved

## 🚀 Quick Start

### Local Development

1. **Clone or download this repository**
   ```bash
   git clone https://github.com/Tech-Vexy/portfolio.git
   cd portfolio
   ```

2. **Open in browser**
   - Simply open `index.html` in your web browser
   - Or use a local server (recommended):
   
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx http-server
   
   # Using PHP
   php -S localhost:8000
   ```

3. **View in browser**
   - Navigate to `http://localhost:8000`

### VS Code Live Server

1. Install the "Live Server" extension in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"

## 📁 Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── index.css           # Styling and animations
├── README.md           # This file
├── img/                # Images and icons
│   ├── *.svg          # Social media icons
│   ├── *.png          # Favicons and app icons
│   ├── phone.jpg      # Contact QR code
│   ├── manifest.json  # PWA manifest
│   └── browserconfig.xml
├── jpMorgan.pdf       # JPMorgan job simulation certificate
└── Walmart.pdf        # Walmart job simulation certificate
```

## 🎨 Customization

### Changing Colors

Edit the CSS variables in `index.css`:

```css
:root {
    --primary-color: #2c3e50;      /* Main color */
    --secondary-color: #3498db;    /* Accent color */
    --accent-color: #e74c3c;       /* Highlight color */
    --background-color: #f8f9fa;   /* Page background */
}
```

### Adding New Sections

1. Add HTML in `index.html`:
```html
<section id="new-section">
    <div class="container">
        <h2 class="section-title">New Section</h2>
        <!-- Your content -->
    </div>
</section>
```

2. Update navigation in header:
```html
<li><a href="#new-section">New Section</a></li>
```

### Modifying Skills

Update the skills in the HTML with your own:

```html
<div class="skill-card">
    <div class="skill-icon">🚀</div>
    <div class="skill-name">Your Skill</div>
    <div class="skill-bar">
        <div class="skill-progress" style="width: 85%"></div>
    </div>
</div>
```

## 🌐 Deployment

### GitHub Pages

1. Push your code to GitHub
2. Go to repository Settings → Pages
3. Select branch (main) and root folder
4. Save and wait for deployment
5. Visit: `https://yourusername.github.io/portfolio`

### Netlify

1. Drag and drop the project folder to [Netlify](https://app.netlify.com)
2. Or connect your GitHub repository
3. Netlify will automatically deploy

### Vercel

```bash
npm install -g vercel
vercel
```

## 📱 Progressive Web App (PWA)

The portfolio includes PWA features:
- `manifest.json` - App manifest for installation
- Multiple icon sizes for different devices
- Works offline after first visit

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with CSS Grid, Flexbox, animations
- **JavaScript** - Interactivity and theme management
- **SVG** - Scalable icons
- **PWA** - Progressive Web App features

## 🎯 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📄 License

This project is open source and available under the MIT License.

## 👤 Author

**Evelia Veldrine Kaharwa**
- Email: eveliaveldrine@gmail.com
- LinkedIn: [veldrineevelia](https://ke.linkedin.com/in/veldrineevelia)
- GitHub: [Tech-Vexy](https://github.com/Tech-Vexy)

## 🤝 Contributing

Feel free to fork this repository and customize it for your own portfolio!

## 📝 Notes

- Update the PDF files (`jpMorgan.pdf`, `Walmart.pdf`) with your own certificates
- Replace social media links with your own
- Update the QR code image in `img/phone.jpg`
- Customize the content in `index.html` to match your profile

---

Made with 💙 and ☕ by Evelia Veldrine Kaharwa
