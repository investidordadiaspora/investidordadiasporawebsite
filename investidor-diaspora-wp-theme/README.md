# Investidor da Diáspora - WordPress Theme

A custom WordPress theme for the Cabo Verde Diaspora Investor Guide website.

## 🎯 Features

- **Custom Post Types**: Opportunities, Institutions, and Testimonials
- **Interactive Elements**: Flip cards, SDG wheel, modal dialogs
- **Responsive Design**: Mobile-first approach with smooth animations
- **Customizer Integration**: Easy content management through WordPress Customizer
- **SEO Ready**: Optimized for search engines
- **Accessibility**: WCAG compliant with keyboard navigation support

## 📁 Theme Structure

```
investidor-diaspora-wp-theme/
├── style.css              # Main stylesheet with theme info
├── index.php              # Main template file
├── header.php             # Header template
├── footer.php             # Footer template
├── functions.php          # Theme functions and customizations
├── page.php               # Page template
├── single-opportunity.php # Single opportunity template
├── single-institution.php # Single institution template
├── 404.php               # 404 error page template
├── searchform.php        # Custom search form
├── comments.php          # Comments template
├── js/
│   └── script.js         # Theme JavaScript
└── images/               # Theme assets
    ├── icons/            # Icon images
    ├── logos/            # Partner logos
    ├── ods/              # SDG images
    └── ...               # Other images
```

## 🚀 Installation

1. **Upload the theme** to `/wp-content/themes/`
2. **Activate the theme** in WordPress Admin → Appearance → Themes
3. **Upload images** to WordPress Media Library
4. **Configure settings** in Appearance → Customize
5. **Add content** using the custom post types

## 📝 Custom Post Types

### Opportunities
- **Purpose**: Showcase business opportunities in Cabo Verde
- **Fields**: Title, Content, Featured Image, Excerpt
- **Template**: `single-opportunity.php`

### Institutions
- **Purpose**: Display government and support institutions
- **Fields**: Title, Content, Featured Image, Mission, Services, Website
- **Template**: `single-institution.php`
- **Meta Boxes**: Institution details (mission, services, website)

### Testimonials
- **Purpose**: Share success stories from diaspora investors
- **Fields**: Title (Name), Content (Quote), Featured Image, Position
- **Template**: Uses main template with custom styling

## ⚙️ Customizer Options

Access through **Appearance → Customize**:

### Site Identity
- Site Title
- Tagline
- Logo Text

### Hero Section
- Main Title
- Subtitle
- Button Text

### Navigation Labels
- Customize all navigation menu labels

### Footer
- Footer title and description
- Contact information
- Copyright text

## 🎨 Customization

### Colors
The theme uses CSS custom properties for easy color customization:

```css
:root {
    --primary-color: #0056b3;
    --dark-blue: #0d2f4f;
    --text-color: #333;
    --light-gray-bg: #f7f9fa;
    --white-color: #FFFFFF;
}
```

### Adding Custom CSS
Use **Appearance → Customize → Additional CSS** to add custom styles.

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px
- **Small Mobile**: Below 576px

## 🔧 JavaScript Features

### Interactive Elements
- **Flip Cards**: Click to reveal institution details
- **SDG Wheel**: Hover to see different development goals
- **Opportunities Modal**: Click cards to see detailed information
- **Download Form**: AJAX-powered form submission
- **Smooth Scrolling**: Enhanced navigation experience

### Browser Support
- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile browsers (iOS Safari, Chrome Mobile)
- Progressive enhancement for older browsers

## 📊 Performance Features

- **Optimized Images**: Responsive images with proper sizing
- **Minified CSS**: Compressed stylesheets
- **Lazy Loading**: Images load as needed
- **Caching Ready**: Compatible with caching plugins

## 🔒 Security Features

- **Sanitized Output**: All user input is sanitized
- **Nonce Verification**: CSRF protection for forms
- **Capability Checks**: Proper permission checks
- **Secure File Handling**: Safe file uploads and processing

## 📈 SEO Features

- **Semantic HTML**: Proper heading structure and markup
- **Meta Tags**: Automatic meta description and title generation
- **Schema Markup**: Structured data for better search results
- **Fast Loading**: Optimized for Core Web Vitals

## 🛠️ Development

### Prerequisites
- WordPress 5.0+
- PHP 7.4+
- Modern web browser
- Code editor (VS Code, Sublime Text, etc.)

### Local Development
1. **Set up local WordPress** using XAMPP, WAMP, or Docker
2. **Clone/copy the theme** to your local WordPress installation
3. **Activate the theme** in WordPress admin
4. **Make changes** to theme files
5. **Test functionality** in different browsers and devices

### File Structure Guidelines
- **PHP files**: Use WordPress coding standards
- **CSS**: Follow BEM methodology for class naming
- **JavaScript**: Use jQuery for WordPress compatibility
- **Images**: Optimize for web (WebP preferred)

## 🐛 Troubleshooting

### Common Issues

**Theme not activating:**
- Check file permissions (755 for folders, 644 for files)
- Ensure all required files are present
- Check for PHP syntax errors

**Images not loading:**
- Verify image paths in theme files
- Check WordPress media library
- Ensure proper file permissions

**JavaScript not working:**
- Check browser console for errors
- Verify jQuery is loaded
- Ensure script.js is properly enqueued

**Customizer not saving:**
- Check user permissions
- Verify theme support for customizer
- Clear any caching plugins

### Debug Mode
Enable WordPress debug mode by adding to `wp-config.php`:

```php
define('WP_DEBUG', true);
define('WP_DEBUG_LOG', true);
define('WP_DEBUG_DISPLAY', false);
```

## 📞 Support

For support and questions:
1. Check WordPress documentation
2. Review theme files for customization options
3. Contact your web developer
4. Check browser console for JavaScript errors

## 📄 License

This theme is developed for the Cabo Verde Diaspora Investor Guide project. All rights reserved.

## 🔄 Updates

### Version 1.0
- Initial release
- Custom post types implementation
- Interactive flip cards
- SDG wheel functionality
- Responsive design
- WordPress Customizer integration

---

**Theme Version:** 1.0  
**WordPress Compatibility:** 5.0+  
**PHP Version:** 7.4+  
**Last Updated:** 2025



