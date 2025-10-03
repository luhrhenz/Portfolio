# Lawrence's Portfolio Website

A modern, responsive portfolio website showcasing the work and skills of Lawrence, a passionate Full Stack Developer. Built with HTML, CSS, and JavaScript, featuring a sleek dark theme with light mode toggle and smooth animations.

## 🚀 Features

### Design & User Experience
- **Modern Dark Theme**: Sleek design with gradient backgrounds and glassmorphism effects
- **Light/Dark Mode Toggle**: Switch between themes with persistent preference storage
- **Responsive Design**: Fully responsive layout that works on all devices
- **Smooth Animations**: CSS animations and transitions for enhanced user experience
- **Particle Background**: Interactive particle animation using Particles.js

### Functionality
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Smooth Scrolling**: Navigate sections smoothly with scroll-spy functionality
- **Typing Animation**: Dynamic typing effect for job titles
- **Portfolio Filtering**: Filter projects by category (Web, App, Design)
- **Contact Form**: Functional contact form with validation
- **Scroll Animations**: Elements animate in as they come into view

### Sections
- **Home**: Hero section with profile image and animated introduction
- **About**: Personal information, skills showcase, and statistics
- **Portfolio**: Project showcase with filtering and modal previews
- **Experience**: Professional timeline with work history
- **Contact**: Contact information and functional contact form

## 🛠️ Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Modern styling with CSS Grid, Flexbox, and custom properties
- **JavaScript (ES6+)**: Interactive functionality and animations
- **Font Awesome**: Icon library for social media and UI elements
- **Google Fonts**: Inter and JetBrains Mono font families
- **Particles.js**: Interactive particle background animation

## 📁 Project Structure

```
portfolio/
├── html/
│   └── index.html          # Main HTML file
├── css/
│   └── styles.css          # All styling and responsive design
├── script.js               # JavaScript functionality
├── tools/                  # Images and assets
│   ├── ironman.jpg        # Profile image
│   └── mamchisom.jpeg     # Project image
└── README.md              # Project documentation
```

## 🎨 Design Features

### Color Scheme
- **Primary**: Purple gradient (#6366f1 to #8b5cf6)
- **Secondary**: Pink accent (#ec4899)
- **Background**: Dark gradient with glassmorphism effects
- **Typography**: Clean, modern fonts with excellent readability

### Responsive Breakpoints
- **Desktop**: 1024px and above
- **Tablet**: 768px - 1023px
- **Mobile**: 480px - 767px
- **Small Mobile**: Below 480px

## 🚀 Getting Started

### Prerequisites
- A modern web browser
- A local web server (optional for development)

### Installation

1. **Clone or download the project files**
2. **Open the project folder**
3. **Launch the website**:
   - Open `html/index.html` directly in your browser, or
   - Use a local server for better experience

### Using a Local Server (Recommended)

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (if you have live-server installed)
npx live-server html/

# Using PHP
cd html/
php -S localhost:8000
```

Then open `http://localhost:8000` in your browser.

## 📱 Mobile Experience

The website is fully responsive and provides an excellent mobile experience with:
- Touch-friendly navigation
- Optimized layout for small screens
- Fast loading times
- Smooth scrolling and animations

## 🎯 Key Features Explained

### Theme System
- Persistent theme preference using localStorage
- Smooth transitions between light and dark modes
- Carefully chosen colors for both themes

### Portfolio Filtering
- Filter projects by category
- Smooth animations when switching filters
- Hover effects and project details

### Interactive Elements
- Animated skill progress bars
- Hover effects on portfolio items
- **Functional contact form with Gmail integration** (using Formspree)
- Social media links with hover animations

### Contact Form Integration
- **Formspree Integration**: Contact form submissions are sent directly to your Gmail
- **Email**: lawrencesunday311@gmail.com
- **Form Validation**: HTML5 validation with user-friendly error messages
- **Success Notifications**: Visual feedback when messages are sent successfully

## 🔧 Customization

### Adding New Projects
Edit the portfolio section in `index.html` and add new project items following the existing structure.

### Modifying Colors
Update the CSS custom properties in `:root` selector in `styles.css`.

### Adding Sections
Follow the existing HTML structure and add corresponding CSS styles.

### Contact Form Setup
The contact form is integrated with Formspree for Gmail delivery:

1. **Current Setup**: Formspree endpoint `https://formspree.io/f/meorkwkj`
2. **Receiving Email**: Messages are forwarded to your registered Gmail address
3. **To Change Email**: Update the `action` attribute in the form to your new Formspree URL
4. **Get Formspree Account**: Visit [formspree.io](https://formspree.io) to set up your own forms
5. **Form Fields**: Name, email, subject, and message fields are properly mapped

**Note**: Make sure to verify your email address in Formspree to start receiving messages.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 About Lawrence

Lawrence is a passionate Full Stack Developer with expertise in:
- **Frontend**: React, React Native, TypeScript, Tailwind CSS
- **Backend**: Node.js, MongoDB
- **Tools**: Figma, Photoshop for design
- **Other**: Modern web technologies and best practices

**Location**: Kaduna, Nigeria
**Email**: lawrencesunday311@gmail.com
**Phone**: +234 706 816 5116, +234 901 177 0996

## 🌐 Links
- **GitHub**: [github.com/luhrhenz](https://github.com/luhrhenz)
- **Twitter**: [@luhrhenz](https://twitter.com/luhrhenz)
- **Portfolio**: [Live Demo](#) (https://meetwithluhrhenz.netlify.app)

---

⭐ **Star this repository if you found it helpful!**