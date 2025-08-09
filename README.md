<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kohaq Education</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background-color: #f5f5f5;
            color: #333;
        }
        header {
            background-color: #007bff;
            color: white;
            padding: 15px;
            text-align: center;
        }
        nav {
            background-color: #0056b3;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }
        section {
            padding: 20px;
            max-width: 900px;
            margin: auto;
            background: white;
            margin-bottom: 20px;
            border-radius: 8px;
        }
        h2 {
            color: #007bff;
        }
        button {
            background-color: #007bff;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            font-size: 16px;
            cursor: pointer;
        }
        button:hover {
            background-color: #0056b3;
        }
        footer {
            background-color: #0056b3;
            color: white;
            text-align: center;
            padding: 10px;
        }
        @media (max-width: 600px) {
            nav a {
                display: block;
                margin: 10px 0;
            }
        }
    </style>
</head>
<body>

    <header>
        <h1>Welcome to Kohaq Education</h1>
        <p>Empowering Education for a Better Future</p>
    </header>

    <nav>
        <a href="#about">About</a>
        <a href="#schedule">Schedule</a>
        <a href="#courses">Courses</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="about">
        <h2>About Us</h2>
        <p>Kohaq Education is a platform dedicated to providing quality training and educational resources. 
           Our mission is to help students and professionals enhance their skills and achieve their career goals.</p>
    </section>

    <section id="schedule">
        <h2>Schedule</h2>
        <ul>
            <li>Web Development Bootcamp – Aug 15 to Aug 25</li>
            <li>Data Science Basics – Sept 1 to Sept 10</li>
            <li>Networking Fundamentals – Sept 15 to Sept 20</li>
        </ul>
    </section>

    <section id="courses">
        <h2>Our Courses</h2>
        <ul>
            <li>Frontend Development with HTML, CSS, JS</li>
            <li>Backend API Development</li>
            <li>Data Analysis with Python</li>
            <li>IT Networking Essentials</li>
        </ul>
        <button onclick="alert('Registration form coming soon!')">Register Now</button>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <p>Email: info@kohaq.com</p>
        <p>Phone: +92 300 1234567</p>
        <p>Follow us on <a href="#" style="color: #007bff;">Instagram</a> | <a href="#" style="color: #007bff;">LinkedIn</a></p>
    </section>

    <footer>
        <p>© 2025 Kohaq Education. All Rights Reserved.</p>
    </footer>

</body>
</html> 
