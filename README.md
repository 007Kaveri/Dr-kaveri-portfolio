# dr-kaveri-portfolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dr. Kaveri's Medical Writing Portfolio</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;700&display=swap');
        body {
            font-family: 'Montserrat', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
        }
        header {
            background-color: #00bfa5;
            color: white;
            padding: 2rem 1rem;
            text-align: center;
            background-image: url('https://via.placeholder.com/1500x500'); /* Replace with your own image */
            background-size: cover;
            background-position: center;
        }
        header h1 {
            font-size: 2.5rem;
            margin: 0;
        }
        nav {
            background-color: white;
            padding: 1rem;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        nav ul {
            list-style-type: none;
            padding: 0;
            margin: 0;
            display: flex;
            justify-content: center;
        }
        nav ul li {
            margin: 0 1rem;
        }
        nav ul li a {
            color: #00bfa5;
            text-decoration: none;
            font-weight: bold;
            padding: 0.5rem 1rem;
            border-radius: 5px;
        }
        nav ul li a:hover {
            background-color: #00bfa5;
            color: white;
        }
        .container {
            padding: 2rem;
            max-width: 1200px;
            margin: auto;
            background-color: white;
            margin-top: 2rem;
            border-radius: 10px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        h2 {
            color: #00bfa5;
            margin-bottom: 1rem;
        }
        .about {
            display: flex;
            align-items: center;
        }
        .about img {
            border-radius: 50%;
            margin-right: 2rem;
            width: 150px;
            height: 150px;
        }
        .portfolio-item {
            background-color: #f1f1f1;
            padding: 1rem;
            margin-bottom: 1rem;
            border-radius: 5px;
            display: flex;
            flex-direction: column;
            align-items: flex-start;
        }
        .portfolio-item h3 {
            margin-top: 0;
            color: #00796b;
        }
        .portfolio-item p {
            margin-bottom: 1rem;
        }
        .portfolio-item a {
            color: #00796b;
            text-decoration: none;
            font-weight: bold;
            align-self: flex-end;
        }
        .portfolio-item a:hover {
            text-decoration: underline;
        }
        footer {
            background-color: #00bfa5;
            color: white;
            text-align: center;
            padding: 1rem 0;
            margin-top: 2rem;
        }
        form {
            display: flex;
            flex-direction: column;
        }
        form label {
            margin: 0.5rem 0 0.2rem;
        }
        form input, form textarea, form button {
            padding: 0.5rem;
            margin-bottom: 1rem;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        form input, form textarea {
            background-color: #f1f1f1;
        }
        form button {
            background-color: #00bfa5;
            color: white;
            border: none;
            cursor: pointer;
            font-weight: bold;
        }
        form button:hover {
            background-color: #00796b;
        }
        .blog img, .services img {
            width: 100%;
            border-radius: 10px;
            margin-bottom: 1rem;
        }
    </style>
</head>
<body>
    <header>
        <h1>Dr. Kaveri's Medical Writing Portfolio</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About Me</a></li>
            <li><a href="#portfolio">Portfolio</a></li>
            <li><a href="#blog">Blog</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    <div class="container" id="home">
        <h2>Welcome to Dr. Kaveri’s Medical Writing Portfolio</h2>
        <p>Explore my work and professional journey.</p>
    </div>
    <div class="container about" id="about">
        <img src="https://via.placeholder.com/150" alt="Dr. Kaveri"> <!-- Replace with your own image -->
        <div>
            <h2>About Me</h2>
            <p>Biography: Transition from dentistry to medical writing.</p>
            <p>Mission Statement: Your vision as a medical writer.</p>
        </div>
    </div>
    <div class="container" id="portfolio">
        <h2>Portfolio</h2>
        <div class="portfolio-item">
            <h3>Article Title 1</h3>
            <p>Short description of the article.</p>
            <a href="link-to-full-article">Read more</a>
        </div>
        <div class="portfolio-item">
            <h3>Article Title 2</h3>
            <p>Short description of the article.</p>
            <a href="link-to-full-article">Read more</a>
        </div>
    </div>
    <div class="container blog" id="blog">
        <h2>Blog</h2>
        <img src="https://via.placeholder.com/1200x400" alt="Blog Image"> <!-- Replace with your own image -->
        <p>Recent blog posts and updates.</p>
    </div>
    <div class="container services" id="services">
        <h2>Services</h2>
        <img src="https://via.placeholder.com/1200x400" alt="Services Image"> <!-- Replace with your own image -->
        <p>Descriptions of writing services offered.</p>
        <p>Testimonials from clients or colleagues.</p>
    </div>
    <div class="container" id="contact">
        <h2>Contact</h2>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>
            <button type="submit">Send</button>
        </form>
        <p>Email: dr.kaveri@example.com</p>
    </div>
    <footer>
        <p>&copy; 2024 Dr. Kaveri. All rights reserved.</p>
    </footer>
</body>
</html>
