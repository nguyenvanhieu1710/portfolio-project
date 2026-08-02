# Portfolio Front-end Project

A modern, responsive, and **SEO-optimized** personal portfolio website template. This project is designed to showcase your skills, projects, and experiences in a professional manner. Built with HTML5, CSS3 (including Bootstrap and custom SCSS), and JavaScript, it is easy to customize and extend for your personal branding.

## 🌟 Features

- ✅ **SEO Optimized** - Complete meta tags, structured data, sitemap
- ✅ Responsive design for all devices (desktop, tablet, mobile)
- ✅ Animated sections and smooth scrolling
- ✅ Portfolio showcase with image gallery
- ✅ Blog section for sharing articles or updates
- ✅ Contact form integration (front-end only)
- ✅ **Schema.org structured data** for rich search results
- ✅ **Open Graph & Twitter Card** tags for social media
- ✅ Built with Bootstrap for rapid development
- ✅ SCSS source files for easy style customization
- ✅ Font and icon support (IcoMoon, Bootstrap Glyphicons)
- ✅ Modern UI/UX with clean code structure
- ✅ **Accessibility optimized** with ARIA labels
- ✅ **Performance optimized** with caching and compression

## 🎯 SEO Features

- Complete meta tags (title, description, keywords, author)
- Structured data (Person, WebSite, ProfessionalService schemas)
- Open Graph tags for Facebook/LinkedIn sharing
- Twitter Card tags for rich Twitter previews
- XML Sitemap for search engine crawling
- Robots.txt for crawler instructions
- Semantic HTML5 markup
- Canonical URLs
- Mobile-friendly and responsive
- Fast loading with browser caching
- Security headers (.htaccess)

For complete SEO documentation, see **[SEO-GUIDE.md](SEO-GUIDE.md)**.

## 📁 Project Structure

```
Portfolio-Front-end-Project/
│
├── css/                    # Compiled CSS files (Bootstrap, custom styles, animations)
├── fonts/                  # Font files (Bootstrap Glyphicons, IcoMoon)
├── images/                 # Image assets for portfolio, blog, and UI
├── js/                     # JavaScript files (jQuery, Bootstrap, plugins, main.js)
├── sass/                   # SCSS source files for custom and Bootstrap styles
├── index.html              # Main HTML file (homepage) - SEO optimized
├── sitemap.xml             # XML sitemap for search engines
├── robots.txt              # Crawler instructions
├── SEO-GUIDE.md            # Complete SEO setup and maintenance guide
└── README.md               # Project documentation
```

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/nguyenvanhieu1710/Portfolio-Front-end-Project.git
cd Portfolio-Front-end-Project
```

### 2. Open the project

Simply open `index.html` in your web browser to view the portfolio.

### 3. Customize

- Replace images in the `images/` folder with your own.
- Edit `index.html` to update your personal information, projects, and blog posts.
- **Update all URLs** after deployment (see SEO-GUIDE.md for details)
- Modify styles in `sass/style.scss` and recompile if you want to change the look and feel.

### 4. SEO Setup (Important!)

After deploying your site, follow these steps:

1. **Update URLs in `index.html`:**
   - Replace `https://nguyenvanhieu.netlify.app/` with your actual domain
   - Update `og:image` and `twitter:image` URLs
   - Update Schema.org JSON-LD URLs

2. **Submit to Search Engines:**
   - Google Search Console: Submit `sitemap.xml`
   - Bing Webmaster Tools: Submit sitemap
   - Test structured data with [Google Rich Results Test](https://search.google.com/test/rich-results)

3. **Social Media Testing:**
   - Test Facebook preview: [Facebook Debugger](https://developers.facebook.com/tools/debug/)
   - Test Twitter card: [Twitter Card Validator](https://cards-dev.twitter.com/validator)

4. **Optional but Recommended:**
   - Set up Google Analytics
   - Monitor with Google PageSpeed Insights
   - Build backlinks by sharing on social media

For detailed instructions, see **[SEO-GUIDE.md](SEO-GUIDE.md)**.

### 5. Build (Optional)

If you want to edit SCSS files, use a SCSS compiler to generate the CSS:

```bash
# Example using sass (install with npm install -g sass)
sass sass/style.scss css/style.css
```

## 🛠️ Dependencies

- [Bootstrap](https://getbootstrap.com/)
- [jQuery](https://jquery.com/)
- [IcoMoon](https://icomoon.io/)
- [EasyPieChart](https://rendro.github.io/easy-pie-chart/)
- [Flexslider](https://woocommerce.com/flexslider/)
- [Google Maps JS API](https://developers.google.com/maps/documentation/javascript/overview)

All dependencies are included locally in the `css/` and `js/` folders.

## ✨ Customization

- **Colors & Fonts:** Edit `sass/style.scss` or `css/style.css`.
- **Sections:** Add, remove, or modify sections in `index.html`.
- **Icons:** Use IcoMoon or Bootstrap Glyphicons for custom icons.
- **SEO:** Update meta tags, structured data, and URLs after deployment.
- **Content:** Keep portfolio and blog sections updated for better SEO.

## 📊 SEO & Performance

This portfolio includes:

- **Complete SEO setup** with meta tags, structured data, and sitemaps
- **Performance optimization** with caching and compression (.htaccess)
- **Social media integration** with Open Graph and Twitter Cards
- **Accessibility features** with semantic HTML and ARIA labels

See **[SEO-GUIDE.md](SEO-GUIDE.md)** for complete documentation.

## 🔧 Post-Deployment

After deploying to Netlify (or other hosting):

1. Update all URLs in `index.html` with your actual domain
2. Submit `sitemap.xml` to Google Search Console
3. Test structured data and social previews
4. Set up Google Analytics (optional)
5. Monitor performance with PageSpeed Insights

Detailed checklist in **[SEO-GUIDE.md](SEO-GUIDE.md)**.

## 📈 Keywords Targeted

Primary: Nguyen Van Hieu, Full Stack Developer, Web Developer, ReactJS Developer, NodeJS Developer

See **[SEO-GUIDE.md](SEO-GUIDE.md)** for complete keyword strategy and maintenance guide.

## 🤝 Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📬 Contact

For questions or feedback, please open an issue or contact hieunv.dev.work@gmail.com.
