<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Simple Website</title>
    <link rel="stylesheet" href="styles.css"> <!-- Optional: Link to an external CSS file -->
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background: #35424a;
            color: #ffffff;
            padding: 20px;
            text-align: center;
        }
        nav {
            margin: 20px 0;
        }
        nav a {
            margin: 0 15px;
            color: #ffffff;
            text-decoration: none;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
            background: #ffffff;
            padding: 20px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        footer {
            text-align: center;
            padding: 10px;
            background: #35424a;
            color: #ffffff;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>Welcome to My Simple Website</h1>
    <nav>
        <a href="index.html">Home</a>
        <a href="post.html">Blog Post</a>
        <a href="contact.html">Contact</a>
    </nav>
</header>

<div class="container">
    <h2>Home Page</h2>
    <p>This is the homepage of my simple website. Here you will find links to my blog posts and contact information.</p>
</div>

<footer>
    <p>&copy; 2024 My Simple Website</p>
</footer>

</body>
</html>
