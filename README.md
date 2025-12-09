# AJT Global LLC Website

A professional website for AJT Global LLC - Heavy Duty Truck Parts, Custom Fabrication, and Global Marketing Solutions based in Joplin, Missouri.

## 🌐 Live Demo

Visit the live website: [https://tate-industries.github.io/AJT-Web/](https://tate-industries.github.io/AJT-Web/)

## 📋 Features

- **Responsive Design** - Mobile-friendly layout that works on all devices
- **Navigation Menu** - Sticky navigation with mobile hamburger menu
- **Hero Section** - Eye-catching header with call-to-action buttons
- **Service Sections** - Global Marketing, Heavy Duty Truck Parts, and Custom Fabrication
- **Professional Styling** - Modern color scheme with smooth animations
- **Contact Information** - Easy access to phone, email, and location details
- **Social Links** - Connect via Facebook, LinkedIn, and Twitter

## 📂 Project Structure

```
AJT-Web/
├── index.html          # Main HTML file
├── style.css           # Stylesheet
├── README.md          # This file
├── .gitignore         # Git ignore rules
└── .nojekyll          # GitHub Pages configuration
```

## 🚀 Getting Started

### Prerequisites
- No special requirements - this is a static HTML/CSS/JavaScript website
- A modern web browser
- (Optional) A local web server for testing

### Local Development

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Tate-Industries/AJT-Web.git
   cd AJT-Web
   ```

2. **Open in your browser:**
   - Simply open `index.html` in your preferred web browser, or
   - Use a local web server:
     ```bash
     # Using Python 3
     python3 -m http.server 8000
     
     # Using Python 2
     python -m SimpleHTTPServer 8000
     
     # Using Node.js (with http-server)
     npx http-server
     ```
   - Then visit `http://localhost:8000`

## 📝 Customization

### Edit Company Information
Update the following in `index.html`:
- **Phone Number:** Line 48 (in hero section) and Line 122 (footer)
- **Email:** Line 123
- **Location:** Line 124
- **Social Links:** Lines 127-129

### Edit Content Sections
- **Global Marketing Section:** Lines 56-73
- **Heavy Duty Truck Parts:** Lines 75-88
- **Custom Fabrication:** Lines 90-110
- **Values Section:** Lines 124-130
- **Footer Content:** Lines 133-152

### Customize Colors
Edit the CSS variables in `style.css` (lines 8-14):
```css
:root {
    --primary-blue: #0056b3;        /* Main brand color */
    --dark-grey: #1a1a1a;           /* Dark backgrounds */
    --light-grey: #f4f4f4;          /* Light backgrounds */
    --accent-orange: #d35400;       /* Accent color */
    /* ... more colors ... */
}
```

## 🎨 Technology Stack

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with CSS Grid and Flexbox
- **JavaScript** - Mobile menu toggle
- **Google Fonts** - Oswald and Roboto fonts
- **FontAwesome** - Icons library
- **Unsplash** - Background images

## 🌍 Deployment on GitHub Pages

This repository is configured for automatic GitHub Pages deployment.

### Steps to Deploy:

1. **Enable GitHub Pages:**
   - Go to your repository Settings
   - Scroll to "GitHub Pages" section
   - Select "Deploy from a branch"
   - Choose `main` branch and `/root` folder
   - Click "Save"

2. **Your site will be live at:**
   ```
   https://tate-industries.github.io/AJT-Web/
   ```

3. **Update links (if needed):**
   - The `.nojekyll` file is already included to skip Jekyll processing
   - All relative links are configured correctly for the `/AJT-Web/` subdirectory

### Troubleshooting Deployment:
- Ensure all files are committed and pushed to `main` branch
- Clear your browser cache (Ctrl+F5 or Cmd+Shift+R)
- Check the "Deployments" tab on GitHub for build status
- Verify the `.nojekyll` file exists in the repository root

## 📱 Responsive Breakpoints

The website is optimized for:
- **Desktop:** 1200px and above
- **Tablet:** 768px to 1199px
- **Mobile:** Below 768px

## 🔧 Browser Compatibility

- Chrome/Edge (Latest)
- Firefox (Latest)
- Safari (Latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📞 Contact Information

**AJT Global LLC**
- **Phone:** (417) 208-2354
- **Email:** jamesjenkins@ajtgloballlc.com
- **Location:** Joplin, Missouri

## 📄 License

© 2025 AJT Global LLC. All Rights Reserved.

## 🤝 Contributing

For updates or modifications to the website, please:
1. Create a new branch (`git checkout -b feature/your-feature`)
2. Make your changes
3. Commit your changes (`git commit -m 'Add your feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

## 📞 Support

For technical issues or questions about the website, please contact the development team.