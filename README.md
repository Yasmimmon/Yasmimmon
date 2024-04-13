<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Main Page</title>
    <style>
        /* Your CSS styles here */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 10px;
            text-align: center;
        }

        nav {
            background-color: #f4f4f4;
            padding: 10px;
        }

        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            text-align: center;
        }

        nav ul li {
            display: inline;
            margin-right: 20px;
        }

        nav ul li a {
            text-decoration: none;
            color: #333;
        }

        nav ul li a:hover {
            text-decoration: underline;
        }

        main {
            padding: 20px;
        }

        footer {
            background-color: #333;
            color: #fff;
            padding: 10px;
            text-align: center;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Website</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
    </nav>
    <main>
        <section>
            <h2>Featured Content</h2>
            <p>This is where your featured content goes.</p>
        </section>
        <section>
            <h2>Recent Posts</h2>
            <p>This is where your recent posts go.</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 My Website</p>
    </footer>
</body>
</html>
/* Your CSS styles here */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header, nav, main, footer {
    padding: 10px;
    margin: 10px;
    border: 1px solid #ccc;
}

ul {
    list-style-type: none;
    padding: 0;
}

ul li {
    display: inline;
    margin-right: 10px;
}

a {
    text-decoration: none;
    color: blue;
}

a:hover {
    text-decoration: underline;
}
