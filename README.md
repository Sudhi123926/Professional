<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Professional Portfolio</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background: #f4f4f4; }
        header { background: #333; color: white; padding: 1em; text-align: center; }
        nav { text-align: center; padding: 1em; background: #555; }
        nav a { color: white; margin: 0 15px; text-decoration: none; }
        section { padding: 20px; max-width: 800px; margin: auto; background: white; }
        footer { text-align: center; padding: 1em; background: #333; color: white; position: fixed; width: 100%; bottom: 0; }
        .contact-form input, .contact-form textarea { width: 100%; padding: 10px; margin: 5px 0; }
        button { background: #333; color: white; padding: 10px; border: none; cursor: pointer; }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Professional Portfolio</h1>
    </header>
    <nav>
        <a href="#about">About Me</a>
        <a href="#blog">HR Blog</a>
        <a href="#resume">Resume</a>
        <a href="#contact">Contact</a>
    </nav>
    <section id="about">
        <h2>About Me</h2>
        <p>I am an Assistant HR Manager with 2.5 years of experience in HR operations...</p>
    </section>
    <section id="blog">
        <h2>HR Blog</h2>
        <p>Coming soon... Stay tuned for insights on HR trends and best practices!</p>
    </section>
    <section id="resume">
        <h2>Resume</h2>
        <a href="resume.pdf" download><button>Download My Resume</button></a>
    </section>
    <section id="contact">
        <h2>Contact Me</h2>
        <form class="contact-form">
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea placeholder="Your Message" rows="4" required></textarea>
            <button type="submit">Send</button>
        </form>
    </section>
    <footer>
        <p>&copy; 2025 My Portfolio. All Rights Reserved.</p>
    </footer>
</body>
</html>
