Overview
This is a responsive portfolio website built using only HTML and vanilla CSS (no frameworks or JavaScript libraries). The website features a clean, modern design with multiple sections to showcase your work, skills, and contact information.

Features
Fully responsive design that works on all devices

Pure HTML/CSS implementation (no frameworks)

Modern UI with smooth animations and transitions

Four main sections:

Hero section with introduction

About section with skills display

Projects showcase

Contact form

Mobile-friendly navigation with hamburger menu

Accessible and semantic HTML structure

Easy to customize with CSS variables

File Structure
text
portfolio/
├── index.html          # Main HTML file
├── README.md           # This documentation file
└── assets/             # Optional assets folder
    ├── images/         # For project images
    └── css/            # For additional CSS files
Installation
No installation required. Simply:

Download or clone the repository

Open index.html in any modern web browser

Customization
To personalize this portfolio:

1. Update Content
Replace placeholder text in the HTML with your information

Update the projects section with your own work

Change the skills listed in the About section

2. Change Images
Replace the placeholder image URLs with your own images:

html
<!-- Example in Hero section -->
background: linear-gradient(rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.7)), url('your-image-url.jpg');

<!-- Example in About section -->
<img src="your-profile-image.jpg" alt="Your Name" class="about-img">
3. Modify Colors
Edit the CSS variables at the top of the style section:

css
:root {
    --primary-color: #3498db;    /* Main brand color */
    --secondary-color: #2c3e50;  /* Dark accent color */
    --light-color: #ecf0f1;      /* Light background */
    --dark-color: #2c3e50;       /* Dark background */
    --accent-color: #e74c3c;     /* Highlight color */
}
4. Add More Projects
Duplicate the project card HTML block and update the content:

html
<div class="project-card">
    <img src="your-project-image.jpg" alt="Project Name" class="project-img">
    <div class="project-info">
        <h3>Project Title</h3>
        <p>Project description</p>
        <div class="project-links">
            <a href="#"><i class="fas fa-external-link-alt"></i> Live Demo</a>
            <a href="#"><i class="fab fa-github"></i> Code</a>
        </div>
    </div>
</div>
Browser Support
The website should work in all modern browsers including:

Chrome

Firefox

Safari

Edge

Mobile browsers

Dependencies
Font Awesome (for icons) - loaded via CDN

No other external dependencies

Deployment
To deploy this portfolio:

Upload all files to your web hosting service

Or use services like:

GitHub Pages

Netlify

Vercel

Firebase Hosting

License
This project is open source and available under the MIT License.

Contact
For any questions or suggestions, please open an issue in the repository or contact the developer directly.
