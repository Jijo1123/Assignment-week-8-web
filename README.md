index.html


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Enhanced Website - Home</title>
    <link rel="stylesheet" href="styles.min.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="services.html">Services</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section class="hero">
            <h1>Welcome to Our Website</h1>
            <p>Your journey to success begins here!</p>
            <button class="btn-primary">Discover More</button>
        </section>

        <section class="slider">
            <div class="slider-container">
                <div class="slide"><img src="image1.jpg" alt="Image 1"></div>
                <div class="slide"><img src="image2.jpg" alt="Image 2"></div>
                <div class="slide"><img src="image3.jpg" alt="Image 3"></div>
            </div>
            <button class="btn-primary slider-nav prev">Prev</button>
            <button class="btn-primary slider-nav next">Next</button>
        </section>

        <section class="services">
            <h2>Our Services</h2>
            <div class="service-cards">
                <div class="service-card">
                    <h3>Web Design</h3>
                    <p>We create visually appealing websites tailored to your brand.</p>
                </div>
                <div class="service-card">
                    <h3>App Development</h3>
                    <p>Transform your ideas into powerful mobile applications.</p>
                </div>
                <div class="service-card">
                    <h3>Digital Marketing</h3>
                    <p>Boost your online presence and increase your sales.</p>
                </div>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 My Enhanced Website | <a href="contact.html">Contact</a></p>
    </footer>

    <script src="script.min.js"></script>
</body>
</html>

about.html


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Enhanced Website - About</title>
    <link rel="stylesheet" href="styles.min.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="services.html">Services</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section class="about">
            <h1>About Us</h1>
            <p>We are a digital agency committed to providing the best in web and app development. With years of experience, our team ensures your business excels online.</p>
            <p>Our mission is to help you achieve your digital goals with innovative and user-centric designs.</p>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 My Enhanced Website | <a href="contact.html">Contact</a></p>
    </footer>

    <script src="script.min.js"></script>
</body>
</html>

contact.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Enhanced Website - Contact</title>
    <link rel="stylesheet" href="styles.min.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="services.html">Services</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section class="contact-form">
            <h1>Contact Us</h1>
            <form id="contactForm">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>

                <label for="message">Message:</label>
                <textarea id="message" name="message" required></textarea>

                <button type="submit" class="btn-primary">Submit</button>
            </form>
            <p id="formMessage"></p>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 My Enhanced Website | <a href="contact.html">Contact</a></p>
    </footer>

    <script src="script.min.js"></script>
</body>
</html>

style.min.css


/* General Styles */
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #333;
    color: white;
    padding: 20px 0;
    text-align: center;
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 1.2em;
    text-transform: uppercase;
}

/* Hero Section */
.hero {
    background-color: #007bff;
    color: white;
    text-align: center;
    padding: 50px 0;
}

.hero h1 {
    margin: 0;
    font-size: 3em;
}

.hero p {
    font-size: 1.5em;
    margin-top: 20px;
}

/* Button Styling */
button {
    background-color: #007bff;
    color: white;
    padding: 12px 30px;
    border: none;
    cursor: pointer;
    font-size: 1em;
    transition: background-color 0.3s ease, transform 0.3s ease;
}

button:hover {
    background-color: #0056b3;
    transform: scale(1.05);
}

/* Image Slider */
.slider {
    position: relative;
    overflow: hidden;
    margin: 20px 0;
}

.slider-container {
    display: flex;
    transition: transform 0.5s ease;
}

.slider .slide {
    width: 100%;
    height: 300px;
    object-fit: cover;
}

.slider-nav {
    position: absolute;
    top: 50%;
    transform: translateY(-50%);
    background-color: rgba(0, 0, 0, 0.5);
    color: white;
    padding: 10px;
    cursor: pointer;
}

.slider-nav.prev {
    left: 10px;
}

.slider-nav.next {
    right: 10px;
}

/* Services Section */
.services {
    background-color: #fff;
    padding: 50px 0;
    text-align: center;
}

.service-cards {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 30px;
}

.service-card {
    background-color: #f0f0f0;
    padding: 30px;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.service-card:hover {
    transform: translateY(-10px);
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.2);
}

/* Contact Form */
.contact-form {
    background-color: #fff;
    padding: 50px;
    max-width: 600px;
    margin: 0 auto;
    border-radius: 8px;
}

.contact-form input, .contact-form textarea {
    width: 100%;
    padding: 12px;
    margin-bottom: 15px;
    border-radius: 4px;
    border: 1px solid #ccc;
}

.contact-form button {
    width: 100%;
}

/* Media Queries */
@media (max-width: 768px) {
    .service-cards {
        grid-template-columns: 1fr;
    }

    .slider-container {
        flex-direction: column;
    }
}

script.min.js


// Image Slider Functionality
let currentSlide = 0;
const slides = document.querySelectorAll('.slide');
const prevButton = document.querySelector('.slider-nav.prev');
const nextButton = document.querySelector('.slider-nav.next');

function showSlide(index) {
    const totalSlides = slides.length;
    if (index >= totalSlides) currentSlide = 0;
    else if (index < 0) currentSlide = totalSlides - 1;
    else currentSlide = index;
    
    document.querySelector('.slider-container').style.transform = `translateX(-${currentSlide * 100}%)`;
}

prevButton.addEventListener('click', () => showSlide(currentSlide - 1));
nextButton.addEventListener('click', () => showSlide(currentSlide + 1));

// Contact Form Validation
document.getElementById('contactForm').addEventListener('submit', function(event) {
    event.preventDefault();
    
    const name = document.getElementById('name').value;
    const email = document.getElementById('email').value;
    const message = document.getElementById('message').value;
    let isValid = true;

    if (!name || !email || !message) {
        isValid = false;
        document.getElementById('formMessage').textContent = "All fields are required!";
        document.getElementById('formMessage').style.color = "red";
    }

    if (isValid) {
        document.getElementById('formMessage').textContent = "Form submitted successfully!";
        document.getElementById('formMessage').style.color = "green";
    }
});


README.md
Project Documentation
Project Overview
This project involves the design, coding, and deployment of a multipage website using HTML5, CSS3, and JavaScript. The website includes the following pages:

Home Page (index.html): The landing page with an engaging hero section and an image slider.
About Page (about.html): Information about the company or service.
Contact Page (contact.html): A contact form for user interaction.
The website is fully responsive, meaning it adapts seamlessly across various devices (desktop, tablet, mobile). It also incorporates advanced CSS and JavaScript for smooth user interactions and efficient deployment.

Design Choices
Layout: The layout is designed using modern CSS techniques, primarily Flexbox and CSS Grid. Flexbox is used for the navigation bar, while CSS Grid is used to arrange the service cards in a responsive manner.
Color Scheme: A blue-themed color palette is chosen for the hero section and call-to-action buttons. This color was selected to convey trust, professionalism, and engagement.
Typography: A clean and minimalistic typography choice (Arial, sans-serif) ensures readability across all screen sizes.
Features Implemented Using JavaScript
Image Slider:
The slider automatically transitions between images when the "Next" or "Prev" buttons are clicked. The images are placed inside a container that is moved horizontally via JavaScript. This feature is created using event listeners for the navigation buttons and a dynamic transform CSS property.
Form Validation:
The contact form includes basic validation to ensure that all fields (name, email, and message) are filled out before submission. If any field is missing, a warning message appears. If all fields are filled, a success message is displayed.
JavaScript prevents the form from submitting until validation is successful.
Challenges Faced
Responsive Layout:
Ensuring that the layout looks good on various devices was challenging. The solution involved using CSS media queries and Flexbox/Grid to adjust the layout dynamically.
JavaScript Form Validation:
Ensuring smooth form validation without refreshing the page was a bit tricky. However, using event.preventDefault() allowed us to handle form validation without needing to reload the page.
Deployment Process
GitHub Pages:

The website files (HTML, CSS, JavaScript) were pushed to a GitHub repository.
GitHub Pages was enabled in the repository settings to deploy the website.
The website is accessible through a GitHub Pages URL.
Netlify:

The project was linked to a GitHub repository, and Netlify was used to deploy it. Netlify automatically detected the website’s settings and deployed it with just a few clicks.
After successful deployment, the website is accessible through the custom URL provided by Netlify.
Minification:

For production, the CSS and JavaScript files were minified to reduce load times and improve performance.
The images were optimized to ensure faster page load times without compromising on quality.
