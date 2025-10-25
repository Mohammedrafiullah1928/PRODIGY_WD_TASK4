# 💼 Mohammed Rafiullah - Personal Portfolio# portfolio

A modern, interactive personal portfolio website showcasing my skills, projects, and experience as an Electronics & Communication Engineering graduate with expertise in software development and web technologies.

![Portfolio](https://img.shields.io/badge/Portfolio-Live-brightgreen)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## 🌟 Features

### 🎨 Design Highlights
- **Neon-Themed UI**: Futuristic neon glow effects with vibrant purple and cyan accents
- **Animated Background**: Dynamic floating shapes and particle effects
- **Glass Morphism**: Modern frosted glass design elements
- **Smooth Animations**: CSS keyframe animations and transitions throughout
- **Responsive Design**: Fully optimized for mobile, tablet, and desktop devices
- **Interactive Elements**: Hover effects, scroll animations, and dynamic content

### 📱 Sections

#### 🏠 Home/Hero Section
- Eye-catching introduction with animated text
- Quick access to projects and resume
- Social media links (LinkedIn, GitHub, Email)
- Professional profile image with glow effects

#### 👤 About Section
- Professional summary and career objectives
- Educational background from NSAKCET
- Personal interests and hobbies
- Visual presentation with animated cards

#### 💻 Skills Section
- **Programming Languages**: C, C++, Python, Java
- **Web Technologies**: HTML, CSS, JavaScript, Bootstrap, React
- **Tools & Platforms**: Git, GitHub, VS Code, Linux
- **Databases**: MySQL, MongoDB
- **Core Electronics**: Circuit Design, Embedded Systems, IoT
- **Soft Skills**: Communication, Problem Solving, Teamwork, Leadership
- Visual skill cards with icons and descriptions

#### 🚀 Projects Section
Interactive project cards featuring:
1. **Portfolio Website** (HTML, CSS, JavaScript)
   - Personal showcase with modern design
   - Responsive and interactive UI

2. **Arduino IoT Projects**
   - Smart home automation
   - Sensor integration and data monitoring

3. **Python Applications**
   - Custom automation scripts
   - Data processing tools

4. **Web Development Projects**
   - Modern web applications
   - Frontend and backend integration

#### 💼 Experience Section
- **Web Development Intern** at Prodigy InfoTech (Oct 2024 - Nov 2024)
  - Built responsive web applications
  - Implemented interactive features
  - Collaborated on real-world projects

- **Academic Projects**
  - Multiple engineering and software projects
  - Team collaboration experience

#### 📞 Contact Section
- Working contact form with validation
- Direct email and phone links
- Social media connections
- Professional communication channels

### ✨ Special Effects
- Neon glow animations on hover
- Floating geometric shapes in background
- Particle system animations
- Smooth scroll behavior
- Mobile-friendly hamburger menu
- Loading animations for content
- Interactive buttons with effects

## 🛠️ Technologies Used

### Frontend
- **HTML5**: Semantic markup and structure
- **CSS3**: 
  - Custom properties (CSS variables)
  - Flexbox and Grid layouts
  - Keyframe animations
  - Gradient effects
  - Media queries for responsiveness
  - Glass morphism effects
- **JavaScript (Vanilla)**:
  - DOM manipulation
  - Event handling
  - Scroll animations
  - Form validation
  - Mobile menu toggle
  - Particle system
  - Intersection Observer API

### External Libraries
- **Font Awesome 6.4.0**: Icons throughout the portfolio

### Assets
- Profile image (`mohdrafi_profile.png`)
- Resume PDF (`mohammed_rafiullah_resume.pdf`)

## 🚀 Getting Started

### View Live
Simply open `index.html` in any modern web browser.

### Local Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/Mohammedrafiullah1928/portfolio.git
   ```

2. Navigate to the project folder:
   ```bash
   cd portfolio
   ```

3. Open in browser:
   - Double-click `index.html`, or
   - Use a local server (recommended):
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js http-server
     npx http-server
     ```

4. Visit `http://localhost:8000` in your browser

## 📁 Project Structure

```
portfolio/
│
├── index.html                      # Main HTML file
├── style.css                       # Stylesheet with animations
├── script.js                       # JavaScript functionality
├── mohdrafi_profile.png            # Profile picture
├── mohammed_rafiullah_resume.pdf   # Resume document
└── README.md                       # Documentation
```

## 🎨 Color Scheme

The portfolio uses a modern neon-inspired color palette:

```css
Primary Colors:
- Neon Cyan: #00f3ff
- Deep Purple: #1a0033
- Dark Background: #0a0014
- Accent Pink: #ff006e

Neon Glow Effects:
- Box Shadow: 0 0 20px rgba(0, 243, 255, 0.5)
- Text Shadow: 0 0 10px #00f3ff
```

## 🔧 Customization

### Update Personal Information

1. **Edit HTML** (`index.html`):
   - Update name, title, and description
   - Modify skills, projects, and experience
   - Change social media links
   - Update contact information

2. **Replace Images**:
   - Replace `mohdrafi_profile.png` with your photo
   - Update resume PDF with your document

3. **Modify Styles** (`style.css`):
   - Change color scheme in CSS variables
   - Adjust animations and effects
   - Customize responsive breakpoints

4. **Update JavaScript** (`script.js`):
   - Modify particle system parameters
   - Customize scroll animations
   - Add new interactive features

## 📱 Responsive Breakpoints

```css
Desktop: > 1024px (default)
Tablet: 768px - 1024px
Mobile: < 768px
Small Mobile: < 480px
```

## ✅ Browser Compatibility

- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ✅ Opera 76+

## 🎯 Key Features Implementation

### Neon Effects
```css
.neon-text {
    color: #00f3ff;
    text-shadow: 0 0 10px #00f3ff, 0 0 20px #00f3ff;
}
```

### Smooth Scroll
```javascript
document.querySelectorAll('a[href^="#"]').forEach(anchor => {
    anchor.addEventListener('click', function (e) {
        e.preventDefault();
        document.querySelector(this.getAttribute('href'))
            .scrollIntoView({ behavior: 'smooth' });
    });
});
```

### Particle System
Dynamic particle generation with canvas or DOM elements for background effects.

## 📊 Performance Optimization

- Optimized images for web
- Minified CSS and JavaScript (for production)
- Efficient animations using CSS transforms
- Lazy loading for images
- Reduced HTTP requests

## 🤝 Contributing

This is a personal portfolio project, but suggestions are welcome!

## 📄 License

This project is open source and available for educational purposes.

## 👤 Contact

**Mohammed Rafiullah**

- 📧 Email: mohammedrafiullah1928@gmail.com
- 💼 LinkedIn: [Mohammed Rafiullah](https://www.linkedin.com/in/mohammed-rafiullah-3a679727a)
- 🐱 GitHub: [Mohammedrafiullah1928](https://github.com/Mohammedrafiullah1928)
- 📱 Phone: +91 9347574716

## 🎓 About Me

Electronics & Communication Engineering graduate from Narasaraopeta Engineering College (NSAKCET) with a passion for:
- 💻 Software Development
- 🌐 Web Technologies
- 🔌 Electronics & IoT
- 🤖 Embedded Systems
- 📊 Problem Solving

Currently seeking opportunities in software development and electronics domains to contribute to innovative projects and grow professionally.

## 🏆 Achievements

- Completed Web Development Internship at Prodigy InfoTech
- Built multiple full-stack web applications
- Strong foundation in programming and electronics
- Active GitHub contributor

## 🎯 Career Goals

Seeking an entry-level position where I can:
- Apply engineering principles to solve real-world problems
- Work with cutting-edge technologies
- Collaborate with dynamic teams
- Continue learning and growing professionally
- Contribute to innovative projects

---

**Built with ❤️ by Mohammed Rafiullah**

*Last Updated: October 2025*

## 📸 Screenshots

> 💡 **Tip**: View the live portfolio for the best experience with animations and interactive elements!

---

### 🌟 If you like this portfolio, please consider giving it a star! ⭐
