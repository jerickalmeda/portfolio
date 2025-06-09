# Portfolio Website - Jerick Carlo Almeda

A responsive portfolio website built with Tailwind CSS showcasing custom PHP systems development and WordPress expertise.

## 🚀 Features

- **Fully Responsive Design** - Works perfectly on all devices (desktop, tablet, mobile)
- **Modern UI/UX** - Clean, professional design with smooth animations
- **Interactive Elements** - Image galleries, project filtering, contact forms
- **Performance Optimized** - Fast loading with CDN-based resources
- **Accessibility Focused** - Semantic HTML and proper ARIA attributes
- **Dual Expertise Focus** - Balanced showcase of custom PHP systems and WordPress solutions

## 📁 Project Structure

```
jerick-portfolio/
├── index.html          # Homepage - PHP systems & WordPress developer intro
├── tech-stack.html     # PHP & WordPress technical skills
├── projects.html       # Custom PHP systems and WordPress projects
├── about.html          # Professional journey in PHP development
├── contact.html        # Contact form for PHP/WordPress inquiries
└── README.md          # This file
```

## 🎨 Design Features

### Color Scheme
- **Primary**: #0f172a (Slate)
- **Secondary**: #334155 (Slate)
- **Accent**: #06b6d4 (Cyan)
- **Dark**: #1F2937 (Dark Gray)

### Technologies Used
- **Tailwind CSS** (CDN) - Utility-first CSS framework
- **Font Awesome** (CDN) - Icons and symbols
- **Vanilla JavaScript** - Interactive functionality
- **Responsive Design** - Mobile-first approach
- **PHP Focus** - Custom systems development showcase
- **WordPress Integration** - Advanced WordPress solutions

## 📄 Pages Overview

### 1. Homepage (`index.html`)
- Hero section highlighting PHP systems development
- Custom PHP systems and WordPress expertise preview
- Featured projects (PHP systems + WordPress)
- Balanced call-to-action sections

### 2. Tech Stack (`tech-stack.html`)
- Custom PHP development skills and frameworks
- WordPress development expertise
- Database design and server management
- Tools, DevOps, and hosting technologies

### 3. Projects (`projects.html`)
- Project filtering by category (PHP systems, WordPress, All)
- Custom PHP applications and WordPress projects
- Interactive galleries for both project types
- Live demo and source code links

### 4. About (`about.html`)
- Professional journey in PHP and WordPress development
- Values focused on custom development and WordPress mastery
- Technical timeline and achievements
- PHP systems and WordPress philosophy

### 5. Contact (`contact.html`)
- Contact form with PHP/WordPress project options
- FAQ section covering PHP and WordPress services
- Business hours and response times
- Multiple contact methods for different project types

## 🔧 Customization

### Personal Information
Update the following placeholders with your actual information:

1. **Name and Branding**
   - Replace "Jerick Carlo Almeda" with your name/brand
   - Update navigation brand links

2. **Contact Information**
   - Email: `jerick@example.com`
   - Phone: `+1 (234) 567-8900`
   - Social media links

3. **Images**
   - Replace placeholder images with your actual photos
   - Profile pictures: 300x300px recommended
   - Project screenshots: 800x600px recommended

4. **Project Details**
   - Update project descriptions
   - Add your actual GitHub/demo links
   - Replace placeholder images with real screenshots

5. **Skills and Experience**
   - Update technology proficiency levels
   - Modify work experience timeline
   - Add your actual certifications

### Colors and Styling
Modify the Tailwind config in each HTML file:
```javascript
tailwind.config = {
    theme: {
        extend: {
            colors: {
                primary: '#YOUR_PRIMARY_COLOR',
                secondary: '#YOUR_SECONDARY_COLOR',
                accent: '#YOUR_ACCENT_COLOR',
                dark: '#YOUR_DARK_COLOR'
            }
        }
    }
}
```

## 🌐 Deployment

### Local Development
1. Clone or download the files to your web server directory
2. Open `index.html` in your browser
3. Test on different devices and screen sizes

### Web Hosting
Upload all files to your web hosting provider:
- Shared hosting (cPanel, etc.)
- Cloud platforms (Netlify, Vercel, GitHub Pages)
- VPS or dedicated servers

### Recommended Hosting Options
- **Netlify** - Easy deployment with form handling
- **Vercel** - Fast global CDN
- **GitHub Pages** - Free hosting for public repositories
- **Traditional Web Hosting** - Any provider supporting static HTML

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🔍 SEO Optimization

### Already Included
- Semantic HTML structure
- Meta viewport tags
- Descriptive page titles
- Alt text for images

### Recommended Additions
- Meta descriptions for each page
- Open Graph tags for social sharing
- Schema.org structured data
- XML sitemap
- robots.txt file

## 📧 Contact Form Integration

The contact form currently shows a success message simulation. To make it functional:

1. **Backend Integration**
   - PHP with mail() function
   - Node.js with email service
   - Python with email libraries

2. **Third-party Services**
   - Formspree
   - Netlify Forms
   - EmailJS

3. **Example PHP Integration**
   ```php
   <?php
   if ($_POST) {
       $name = $_POST['name'];
       $email = $_POST['email'];
       $message = $_POST['message'];
       
       mail('your@email.com', 'Contact Form', $message);
       echo json_encode(['success' => true]);
   }
   ?>
   ```

## 🚀 Performance Tips

1. **Image Optimization**
   - Use WebP format when possible
   - Compress images (TinyPNG, etc.)
   - Implement lazy loading for galleries

2. **Code Optimization**
   - Minify CSS/JS for production
   - Use critical CSS inlining
   - Optimize font loading

3. **Caching**
   - Set proper cache headers
   - Use service workers for offline support
   - Enable GZIP compression

## 🤝 Contributing

Feel free to submit issues and enhancement requests!

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

---

**Happy coding!** 🎉

For questions or support, please refer to the contact information in the portfolio.
