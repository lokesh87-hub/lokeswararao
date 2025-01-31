<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 1rem;
            text-align: center;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 1rem;
        }
        h1, h2, h3 {
            color: #333;
        }
        .intro, .projects, .contact {
            background-color: #fff;
            padding: 2rem;
            margin-bottom: 1rem;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .project {
            border-bottom: 1px solid #ddd;
            padding: 1rem 0;
        }
        .project:last-child {
            border-bottom: none;
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 0.5rem;
            margin-bottom: 0.5rem;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        .contact-form button {
            background-color: #333;
            color: #fff;
            border: none;
            padding: 0.75rem;
            border-radius: 4px;
            cursor: pointer;
        }
        .contact-form button:hover {
            background-color: #555;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 1rem;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Student Name</h1>
        <p>Aspiring Web Developer</p>
    </header>
    <div class="container">
        <section class="intro">
            <h2>Introduction</h2>
            <p>Hello! I am a passionate web development student currently learning HTML, CSS, and JavaScript. I am enthusiastic about creating dynamic and responsive websites. I enjoy tackling new challenges and continuously improving my skills in web development.</p>
        </section>
        <section class="projects">
            <h2>Projects</h2>
            <div class="project">
                <h3>Project 1: Portfolio Website</h3>
                <p>A personal portfolio website to showcase my skills and projects. Built using HTML, CSS, and JavaScript.</p>
            </div>
            <div class="project">
                <h3>Project 2: To-Do List App</h3>
                <p>A simple to-do list application with add, edit, and delete functionalities. Developed using JavaScript and local storage.</p>
            </div>
            <div class="project">
                <h3>Project 3: Responsive Blog Template</h3>
                <p>A responsive blog template that adjusts layout based on screen size. Created with HTML and CSS media queries.</p>
            </div>
        </section>
        <section class="contact">
            <h2>Contact</h2>
            <form class="contact-form">
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
                <button type="submit">Send Message</button>
            </form>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 Student Name. All rights reserved.</p>
    </footer>
</body>
</html>
