# 🎬 Samitha Bandara - Video Editor Portfolio

A modern, responsive personal portfolio website showcasing video editing services, projects, and professional experience. Built with HTML5 and CSS3 for the Advanced Client-Side Development coursework (5COSC026W).


## 🌟 Features

- **Modern Design**: Clean, professional layout with yellow accent colors (#FFD700) on dark theme
- **Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **Semantic HTML5**: Proper use of semantic elements (`<header>`, `<nav>`, `<main>`, `<article>`, `<section>`, `<aside>`, `<footer>`)
- **Advanced CSS3**: Includes animations, transitions, transforms, gradients, and shadows
- **Video Showcase**: Integrated video player for showreel
- **Contact Form**: HTML5 form validation with newsletter subscription
- **Fast Loading**: No external frameworks, pure HTML/CSS

## 📂 Project Structure

```
portfolio/
│
├── index1.html           # Home page with hero section
├── about.html            # About page with skills & experience
├── projects.html         # Projects showcase with video showreel
├── contact.html          # Contact page with form
├── style.css             # Main stylesheet
│
├── images/               # Image assets
│   ├── pp_pic-Photoroom.png
│   ├── PP_2.png
│   ├── ytvideo1.png
│   ├── comvideo1.png
│   └── docvideo1.webp
│
└── videos/               # Video assets
    └── comvideo1.mp4
```

## 🚀 Quick Start

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/samitha-portfolio.git
cd samitha-portfolio
```

### 2. Open in Browser

Simply open `index1.html` in your web browser:

```bash
# On Mac
open index1.html

# On Windows
start index1.html

# On Linux
xdg-open index1.html
```

Or use a local development server:

```bash
# Using Python 3
python -m http.server 8000

# Using Python 2
python -m SimpleHTTPServer 8000

# Using Node.js (if you have http-server installed)
npx http-server
```

Then navigate to `http://localhost:8000`

## 🎨 Design Elements

### Color Palette
- **Primary Yellow**: `#FFD700`
- **Dark Background**: `#0a0d1f`
- **White Text**: `#ffffff`
- **Orange Accent**: `#FFA500`

### Typography
- **Headings**: Bebas Neue (Google Fonts)
- **Body Text**: Poppins (Google Fonts)

### Key Features
- ✅ Smooth scroll animations
- ✅ Hover effects with transforms
- ✅ Circular profile images with glowing shadows
- ✅ Rotating decorative ring around profile
- ✅ Gradient buttons with shadow effects
- ✅ Form validation styling

## 📋 HTML5 & CSS3 Requirements Fulfilled

### HTML5 Semantic Elements
- ✅ `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>`
- ✅ `<time>` element with `datetime` attribute
- ✅ HTML5 form elements (`type="email"`, `type="tel"`, `required`, etc.)

### CSS3 Advanced Features (All 21 Requirements)
1. ✅ **Google Fonts** - Bebas Neue & Poppins
2. ✅ **Semi-transparent colors** - `rgba()` for overlays
3. ✅ **Shadows** - `box-shadow`, `text-shadow`
4. ✅ **Text effects** - Letter spacing, gradients
5. ✅ **Attribute selectors** - `[alt]`, `[href]`, `[type]`
6. ✅ **Pseudo-elements** - `::before`, `::after` with generated content
7. ✅ **User action pseudo-classes** - `:hover`, `:focus`, `:active`
8. ✅ **Child combinator** - `>`
9. ✅ **Structural selectors** - `:first-child`, `:last-child`
10. ✅ **Negation pseudo-class** - `:not()`
11. ✅ **Nth pseudo-class** - `:nth-child()`
12. ✅ **Validity pseudo-classes** - `:valid`, `:invalid`
13. ✅ **Relational selectors** - `+`, `~`
14. ✅ **Borders** - Various border styles
15. ✅ **Rounded corners** - `border-radius`
16. ✅ **Gradients** - `linear-gradient()`
17. ✅ **Transforms** - `scale()`, `translateY()`, `rotate()`
18. ✅ **Transitions** - Smooth animations on hover
19. ✅ **Animations** - `@keyframes` for fade-in, slide-in, rotate
20. ✅ **Specificity** - Demonstrated in CSS comments
21. ✅ **Comments & indentation** - Well-documented code

### Responsive Design
- ✅ Mobile-first approach
- ✅ Breakpoints: 1024px, 768px, 600px
- ✅ Flexible grid layouts
- ✅ Optimized for all screen sizes

## 📱 Responsive Breakpoints

```css
/* Desktop: Default */
/* Tablet: max-width: 1024px */
/* Mobile Large: max-width: 768px */
/* Mobile Small: max-width: 600px */
```

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Advanced styling
- **Google Fonts** - Typography
- **No JavaScript** - Pure HTML/CSS implementation
- **No Frameworks** - Vanilla code only

## 📄 Pages Overview

### 🏠 Home Page (`index1.html`)
- Hero section with introduction
- Profile photo with decorative elements
- Call-to-action buttons
- Social media links (YouTube, Facebook, LinkedIn)

### 👤 About Page (`about.html`)
- Personal bio and introduction
- Statistics (480+ videos, 6+ years, 25+ clients)
- Skills breakdown (Video Editing, Creative Direction, Software)
- Timeline showing work experience
- Software expertise icons (Pr, Ae, Ps, Au)

### 🎬 Projects Page (`projects.html`)
- Project showcase grid with 3 projects
- Video showreel section with embedded video player
- Services section highlighting 4 main services
- `<article>` and `<time>` elements for blog-style posts

### 📧 Contact Page (`contact.html`)
- Contact information with links
- HTML5 validated contact form
- Social media follow section
- Newsletter subscription option

## 🎓 Coursework Information

**Course**: 5COSC026W - Advanced Client-Side Development (2025/26)  
**Institution**: University of Westminster  
**Module Leader**: Ebad Majeed  
**Assessment**: Portfolio with in-class test  

This portfolio demonstrates proficiency in:
- HTML5 semantic markup and structure
- CSS3 advanced styling techniques
- Responsive web design with media queries
- Form validation and user interaction
- Web accessibility and best practices

## 📦 Deployment

### GitHub Pages
1. Push your code to GitHub
2. Go to repository Settings
3. Navigate to Pages section
4. Select main branch
5. Your site will be live at: `https://yourusername.github.io/samitha-portfolio/`

### Netlify
1. Drag and drop the project folder to [Netlify Drop](https://app.netlify.com/drop)
2. Or connect your GitHub repository for automatic deployment

### Vercel
```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
vercel
```

## 🔧 Customization

### Change Colors
Edit the color values in `style.css`:
```css
/* Primary Yellow */
#FFD700

/* Dark Background */
#0a0d1f

/* Orange Accent */
#FFA500
```

### Update Content
- **Personal info**: Edit text in HTML files
- **Images**: Replace files in `images/` folder
- **Videos**: Replace `comvideo1.mp4` in `videos/` folder
- **Social links**: Update URLs in HTML files

### Add More Projects
In `projects.html`, duplicate the `<article class="project-card">` section:
```html
<article class="project-card">
    <div class="project-image">
        <img src="images/your-image.png" alt="Project Title">
    </div>
    <div class="project-info">
        <h3>Your Project Title</h3>
        <p>Project Description</p>
        <time datetime="2025-11-05">November 2025</time>
    </div>
</article>
```

## 📊 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Opera (latest)

## 📝 License

This project is created for educational purposes as part of university coursework.

## 👤 Author

**Samitha Bandara**
- YouTube: [@samithabandaraa](https://www.youtube.com/@samithabandaraa)
- LinkedIn: [Samitha Bandara](https://www.linkedin.com/in/samitha-bandara-97a536253/)
- Facebook: [Samitha Bandara](https://web.facebook.com/profile.php?id=100069286082976)
- Email: samiyart543@gmail.com
- Website: [samitha.netlify.app](https://samitha.netlify.app)

## 🙏 Acknowledgments

- University of Westminster - Course materials and guidance
- Google Fonts - Typography resources
- Inspiration from modern portfolio designs

---

**⭐ If you found this portfolio helpful, please give it a star!**

**📧 For inquiries or collaborations, feel free to reach out via the contact page.**
