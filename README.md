# Luis Salvador Heysen - Personal Portfolio

A modern, responsive personal portfolio website showcasing my projects, skills, and experience as a software engineer.

## 🌟 Features

- **Modern Design**: Clean, professional design with smooth animations
- **Dark/Light Mode**: Toggle between dark and light themes
- **Responsive**: Fully responsive design that works on all devices
- **Interactive**: Hover effects and smooth transitions
- **Fast Loading**: Optimized for performance
- **Accessible**: Built with accessibility in mind

## 🚀 Live Demo

Visit my portfolio at: [https://luissalvadorheysen.github.io/portfolio](https://luissalvadorheysen.github.io/portfolio)

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with CSS Grid and Flexbox
- **JavaScript**: Interactive features and theme switching
- **Font Awesome**: Icons
- **CSS Variables**: For theme management

## 📁 Project Structure

```
portfolio/
├── index.html          # Main portfolio page
├── README.md           # This file
└── .gitignore          # Git ignore file
```

## 🎨 Design Features

### Color Scheme
- **Primary**: Purple gradient (#667eea to #764ba2)
- **Dark Mode**: Adjusted colors for better contrast
- **Accents**: Consistent color usage throughout

### Typography
- **Font**: Segoe UI (system font stack)
- **Hierarchy**: Clear heading structure
- **Readability**: Optimized line heights and spacing

### Layout
- **Grid System**: CSS Grid for responsive layouts
- **Flexbox**: For component alignment
- **Mobile First**: Responsive design approach

## 🔧 Setup Instructions

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/LuisSalvadorHeysen/portfolio.git
   cd portfolio
   ```

2. **Open in browser**
   ```bash
   # Using Python (if installed)
   python -m http.server 8000
   
   # Using Node.js (if installed)
   npx serve .
   
   # Or simply open index.html in your browser
   ```

3. **View the site**
   - Navigate to `http://localhost:8000` (if using Python)
   - Or open `index.html` directly in your browser

### GitHub Pages Deployment

1. **Push to GitHub**
   ```bash
   git add .
   git commit -m "Initial portfolio commit"
   git push origin main
   ```

2. **Enable GitHub Pages**
   - Go to your repository settings
   - Navigate to "Pages" section
   - Select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Save the settings

3. **Your site will be available at**
   `https://yourusername.github.io/portfolio`

## 📱 Responsive Design

The portfolio is fully responsive and optimized for:

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px

## 🎯 Key Sections

### Header
- Name and title
- Social media links
- Professional introduction

### About Me
- Personal background
- Professional interests
- Current status

### Featured Projects
- Smart AI Email Client
- UChicago Exam Scheduler
- MyShell - Custom Unix Shell

### Skills
- Programming Languages
- Frameworks & Tools
- AI & APIs
- Other Skills

### Contact
- Email
- Location
- Education

## 🔄 Customization

### Personal Information
Update the following in `index.html`:

1. **Name and Title**
   ```html
   <h1>Your Name</h1>
   <p class="subtitle">Your Title</p>
   ```

2. **Social Links**
   ```html
   <a href="https://github.com/yourusername">GitHub</a>
   <a href="https://linkedin.com/in/yourprofile">LinkedIn</a>
   <a href="mailto:your.email@example.com">Email</a>
   ```

3. **About Me**
   ```html
   <p>Your personal description...</p>
   ```

4. **Projects**
   - Update project titles, descriptions, and links
   - Add or remove project cards as needed
   - Update technology tags

5. **Skills**
   - Modify skill categories
   - Add or remove skills
   - Update skill descriptions

6. **Contact Information**
   ```html
   <div>your.email@example.com</div>
   <div>Your Location</div>
   <div>Your Institution</div>
   ```

### Styling
The portfolio uses CSS custom properties for easy theming:

```css
:root {
    --primary-color: #667eea;
    --secondary-color: #764ba2;
    --bg-color: #f8f9fa;
    --text-color: #333;
    /* ... other variables */
}
```

## 🚀 Performance Optimizations

- **Minimal Dependencies**: Only Font Awesome for icons
- **CSS Variables**: Efficient theme switching
- **Optimized Images**: SVG patterns for backgrounds
- **Smooth Animations**: Hardware-accelerated transitions

## 📈 Analytics (Optional)

To add Google Analytics:

1. Get your tracking ID from Google Analytics
2. Add this script before the closing `</head>` tag:

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

## 🤝 Contributing

While this is a personal portfolio, suggestions and improvements are welcome:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📞 Contact

- **Email**: your.email@example.com
- **GitHub**: [@LuisSalvadorHeysen](https://github.com/LuisSalvadorHeysen)
- **LinkedIn**: [Your LinkedIn Profile](https://linkedin.com/in/yourprofile)

---

⭐ **Star this repository if you found it helpful!** 