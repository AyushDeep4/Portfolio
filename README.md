# Ayush Deep - Personal Portfolio Website

![Portfolio Preview](https://api.placeholder.com/1200/630?text=Ayush+Deep+Portfolio)

## 📋 Overview

A clean, responsive portfolio website built with HTML, CSS, and JavaScript to showcase my skills, projects, education, and certifications. This personal website serves as a digital resume and portfolio to highlight my experience as an Information Technology student at Manipal University.

## ✨ Features

- **Responsive Design**: Fully responsive layout that works on mobile, tablet, and desktop devices
- **Modern UI**: Clean and professional interface with animations and transitions
- **Accessible**: Built with accessibility in mind for all users
- **Fast Loading**: Optimized for performance with minimal external dependencies
- **Easy to Customize**: Well-structured code that's easy to modify and extend
- **Navigation**: Smooth scrolling navigation to different sections of the website

## 🧩 Sections

- **Header**: Personal introduction and contact information
- **About**: Brief overview and key points about me
- **Skills**: Technical skills categorized by domain
- **Projects**: Featured projects with descriptions and technologies used
- **Education**: Academic history displayed in a timeline format
- **Certifications**: Professional certifications and courses
- **Contact**: Ways to connect with me

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript
- Flexbox & CSS Grid
- CSS Variables
- SVG Icons
- Responsive Design

## 🚀 How to Use

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/portfolio-website.git
   ```

2. **Navigate to the project directory**
   ```bash
   cd portfolio-website
   ```

3. **Open the index.html file in your browser**
   ```bash
   # On macOS
   open index.html
   
   # On Windows
   start index.html
   
   # On Linux
   xdg-open index.html
   ```

4. **Alternatively, use a local development server**
   ```bash
   # Using Python
   python -m http.server
   
   # Using Node.js (with http-server installed)
   npx http-server
   ```

## 🔧 Customization

### Personal Information
Edit the HTML file to update:
- Name and title in the header section
- Contact information (email, phone, LinkedIn)
- About me content
- Education details
- Project descriptions

### Styling
Modify the CSS variables in the `:root` selector to change the color scheme:
```css
:root {
    --primary: #2563eb;
    --primary-dark: #1d4ed8;
    --secondary: #4b5563;
    --light: #f3f4f6;
    --dark: #111827;
    --accent: #8b5cf6;
}
```

### Adding Projects
To add a new project, copy the existing project card structure and update the content:
```html
<div class="project-card">
    <div class="project-image">
        <!-- SVG or image here -->
    </div>
    <div class="project-info">
        <h3 class="project-title">Your Project Title</h3>
        <div class="project-tags">
            <span class="project-tag">Technology 1</span>
            <span class="project-tag">Technology 2</span>
        </div>
        <p>Project description here...</p>
    </div>
</div>
```

## 📱 Responsive Behavior
The website is fully responsive with breakpoints at:
- Mobile: Up to 768px
- Tablet: 768px to 1024px
- Desktop: 1024px and above

## 🧠 Future Improvements

- Add a dark/light theme toggle
- Implement a blog section
- Add project filtering capability
- Integrate a contact form
- Add animations on scroll
- Create a project details page for each project

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📬 Contact

- Email: ayushdeep004@gmail.com
- LinkedIn: [Ayush Deep](https://linkedin.com/in/ayush-deep-81a48a288)
- Phone: +91-8092810015

---

Made with ❤️ by Ayush Deep
