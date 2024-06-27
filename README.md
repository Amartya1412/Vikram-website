<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vikram's Personal Webpage</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 1rem;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }
        nav a {
            color: white;
            padding: 1rem;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        .content {
            padding: 2rem;
        }
        .section {
            margin-bottom: 2rem;
        }
        footer {
            background-color: #333;
            color: white;
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
        <h1>Vikram's Personal Webpage</h1>
    </header>
    <nav>
        <a href="#about">About Me</a>
        <a href="#projects">Projects</a>
        <a href="#blog">Blog</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="content">
        <div id="about" class="section">
            <h2>About Me</h2>
            <p>My name is Vikram. I am a student of Mechanical Engineering at Savitribai Phule Pune University (SPPU). I love to read books and cook food in my free time.</p>
        </div>
        <div id="projects" class="section">
            <h2>Projects</h2>
            <ul>
                <li>Project 1: Description of Project 1</li>
                <li>Project 2: Description of Project 2</li>
                <li>Project 3: Description of Project 3</li>
            </ul>
        </div>
        <div id="blog" class="section">
            <h2>Blog</h2>
            <p>Coming soon...</p>
        </div>
        <div id="contact" class="section">
            <h2>Contact</h2>
            <p>Email: <a href="mailto:vikram@example.com">vikram@example.com</a></p>
        </div>
    </div>
    <footer>
        <p>&copy; 2024 Vikram</p>
    </footer>
</body>
</html>
