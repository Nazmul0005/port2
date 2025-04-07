# Nazmul Islam Portfolio

A modern, responsive, and interactive portfolio website built with HTML, CSS, and JavaScript.

## Features

- **Modern Design**: Clean and professional design with smooth animations
- **Responsive**: Fully responsive layout that works on all device sizes
- **Interactive**: Dynamic elements like project filtering and smooth scrolling
- **Sections**: Home, About, Skills, Experience, Projects, and Contact sections
- **Project Filtering**: Filter projects by category
- **Form Validation**: Contact form with client-side validation
- **Smooth Animations**: Scroll animations and preloader for better user experience

## Technologies Used

- HTML5
- CSS3 (Custom CSS, no frameworks)
- JavaScript (Vanilla JS, no libraries)
- Font Awesome (for icons)
- Google Fonts (Poppins)

## Getting Started

1. Clone this repository or download the ZIP file
2. Open `index.html` in your browser to view the portfolio
3. Customize the content in the HTML file to match your information
4. Update the styling in `css/style.css` if desired
5. Modify the JavaScript functionality in `js/script.js` if needed

## Customization

### Adding Your Information

1. Replace placeholder text in `index.html` with your personal information
2. Update skills, experience, and projects sections with your own
3. Add your own profile picture in the `images` folder and update the CSS reference
4. Customize colors by changing the CSS variables in `:root` in the CSS file

### Adding Projects

To add a new project, copy and paste the following HTML structure inside the `.projects-grid` div:

```html
<div class="project-card" data-category="your-category">
    <div class="project-img">
        <img src="images/your-project-image.jpg" alt="Project Name">
    </div>
    <div class="project-info">
        <h3>Project Name</h3>
        <p>Project description goes here...</p>
        <div class="project-tags">
            <span>Tag 1</span>
            <span>Tag 2</span>
            <span>Tag 3</span>
        </div>
        <div class="project-links">
            <a href="#" target="_blank"><i class="fab fa-github"></i></a>
            <a href="#" target="_blank"><i class="fas fa-external-link-alt"></i></a>
        </div>
    </div>
</div>
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements

- Font Awesome for the icons
- Google Fonts for the Poppins font
- Unsplash for placeholder images (if used) 