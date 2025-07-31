# Khulekani Mtshali - Portfolio Website 🚀

A modern, responsive portfolio website showcasing software development skills, projects, and professional experience. Built with clean HTML5, advanced CSS3, and interactive JavaScript features.

![Portfolio Preview](assets/img/preview.png)

## ✨ Features

### 🎨 Modern Design
- **Responsive Layout**: Optimized for all devices (mobile-first approach)
- **Smooth Animations**: ScrollReveal integration with Framer Motion-style effects
- **Interactive Elements**: Hover effects, button animations, and smooth transitions
- **Clean Typography**: Poppins font family for modern readability

### 🔧 Core Functionality
- **Typing Animation**: Dynamic text animation on hero section
- **Navigation**: Smooth scrolling with active link highlighting
- **Tabbed About Section**: Switch between Education and Experience
- **Skills Visualization**: Animated progress bars with percentages
- **Project Showcase**: Interactive grid with hover overlays
- **Contact Form**: Web3Forms integration for message handling
- **CV Management**: Upload and download functionality

### 💬 Interactive Features
- **Embedded Chatbot**: Botpress integration for visitor interaction
- **Social Media Links**: Direct connections to LinkedIn, GitHub, and Behance
- **Mobile Menu**: Collapsible navigation for mobile devices
- **Form Validation**: Client-side validation with status messages

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and accessibility features
- **CSS3**: Flexbox, Grid, Custom Properties, and Animations
- **JavaScript**: Vanilla JS for interactions and form handling
- **ScrollReveal**: Advanced scroll animations
- **Boxicons**: Icon library for consistent iconography
- **Web3Forms**: Contact form backend service
- **Botpress**: Chatbot integration

## 📁 Project Structure

```
portfolio-website/
├── index.html              # Main HTML file
├── assets/
│   ├── css/
│   │   └── styles.css      # Main stylesheet
│   ├── img/               # Images and graphics
│   │   ├── perfil.jpg     # Profile image
│   │   ├── about.jpg      # About section image
│   │   ├── work1-6.jpg    # Project screenshots
│   │   └── ...
│   └── js/
│       └── main.js        # JavaScript functionality
├── README.md              # Project documentation
└── .gitignore            # Git ignore file
```

## 🚀 Getting Started

### Prerequisites
- Modern web browser
- Local web server (optional, for development)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Mkhulekani/portfolio-website.git
   cd portfolio-website
   ```

2. **Open locally**
   ```bash
   # Option 1: Direct file opening
   open index.html
   
   # Option 2: Using Python server
   python -m http.server 8000
   
   # Option 3: Using Node.js server
   npx serve .
   ```

3. **View in browser**
   Navigate to `http://localhost:8000` or open `index.html` directly

## 📝 Customization

### Personal Information
Update the following sections in `index.html`:

```html
<!-- Hero Section -->
<h1 class="home__title">
    <span id="typing-text"></span>
    <span class="home__title-color" id="name-text"></span>
    <br><span id="job-text"></span>
</h1>

<!-- About Section -->
<h2 class="about__subtitle">I am Your Name</h2>
<p class="about__text">Your personal story...</p>
```

### Contact Form
Replace the Web3Forms access key:

```html
<input type="hidden" name="access_key" value="YOUR_WEB3FORMS_KEY">
```

### Social Media Links
Update social media URLs in the home and footer sections:

```html
<a href="https://linkedin.com/in/yourprofile" target="_blank" class="home__social-icon">
    <i class='bx bxl-linkedin'></i>
</a>
```

### Projects
Update project links and descriptions:

```html
<div class="work__item">
    <a href="https://github.com/yourusername/project" target="_blank" class="work__img">
        <img src="assets/img/your-project.jpg" alt="Project Name">
        <!-- ... -->
    </a>
</div>
```

### Skills
Modify skill percentages in CSS:

```css
.skills__html { width: 85%; }
.skills__css { width: 80%; }
.skills__js { width: 65%; }
/* Add your skills */
```

## 🎨 Color Scheme

The website uses CSS custom properties for easy theme customization:

```css
:root {
  --hue-color: 224;
  --first-color: hsl(var(--hue-color), 89%, 60%); /* Primary blue */
  --second-color: hsl(var(--hue-color), 56%, 12%); /* Dark blue */
}
```

## 📱 Responsive Breakpoints

- **Mobile**: < 576px
- **Tablet**: 576px - 768px
- **Desktop**: 768px - 992px
- **Large Desktop**: > 992px

## 🔧 Key Features Implementation

### Typing Animation
```javascript
function typeWriter() {
    const greeting = "Hi,\nI'am ";
    const name = "Khulekani";
    const job = "Software Developer";
    // Animation logic...
}
```

### Smooth Scrolling
```javascript
const sections = document.querySelectorAll('section[id]');
function scrollActive() {
    // Active link highlighting logic...
}
```

### Form Handling
```javascript
contactForm.addEventListener('submit', async function(e) {
    e.preventDefault();
    // Web3Forms integration...
});
```

## 🌟 Performance Optimizations

- **Lazy Loading**: Images load as needed
- **Minified Assets**: Compressed CSS and JS
- **CDN Integration**: External libraries from CDN
- **Smooth Animations**: Hardware-accelerated CSS transitions
- **Mobile-First**: Optimized for mobile performance

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Khulekani Mtshali**
- LinkedIn: [Khulekani Mtshali](https://www.linkedin.com/in/khulekani-mtshali-94b62a329)
- GitHub: [@Mkhulekani](https://github.com/Mkhulekani)
- Email: your.email@example.com

## 🙏 Acknowledgments

- **ScrollReveal**: For smooth scroll animations
- **Boxicons**: For beautiful icons
- **Web3Forms**: For contact form backend
- **Botpress**: For chatbot integration
- **Google Fonts**: For typography

## 📊 Browser Support

- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ⚠️ Internet Explorer (limited support)

---

⭐ **If you found this project helpful, please give it a star!** ⭐
