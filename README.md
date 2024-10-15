<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to My Website</h1>
        <nav>
            <ul>
                <li><a href="#about">About Us</a></li>
                <li><a href="#blog">Blog Posts</a></li>
                <li><a href="#privacy-policy">Privacy Policy</a></li>
                <li><a href="#terms">Terms and Conditions</a></li>
                <li><a href="#contact">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="about">
            <h2>About Us</h2>
            <p>We are committed to providing valuable information and resources to our visitors.</p>
        </section>

        <section id="blog">
            <h2>Blog Posts</h2>
            <p>Check out our latest articles on various topics!</p>
            <article>
                <h3>Blog Post Title</h3>
                <p>Excerpt from the blog post...</p>
                <a href="#">Read More</a>
            </article>
        </section>

        <section id="privacy-policy">
            <h2>Privacy Policy</h2>
            <p>Your privacy is important to us. We ensure that your information is kept safe and secure.</p>
        </section>

        <section id="terms">
            <h2>Terms and Conditions</h2>
            <p>Please read our terms and conditions carefully before using our website.</p>
        </section>

        <section id="contact">
            <h2>Contact Us</h2>
            <p>If you have any questions, feel free to reach out to us!</p>
            <form action="#" method="post">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                <label for="message">Message:</label>
                <textarea id="message" name="message" required></textarea>
                <button type="submit">Send Message</button>
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 My Website. All rights reserved.</p>
    </footer>
</body>
</html>
