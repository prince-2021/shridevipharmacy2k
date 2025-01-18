<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My First Website</title>
    <style>
        body {
            font-family: sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
            color: #333;
        }
        header {
            background-color: #007bff;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            background-color: #333;
            color: white;
            padding: 10px;
        }
        nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
            text-align: center; /* Center the navigation links */
        }
        nav li {
            display: inline;
            margin: 0 10px;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 5px 10px; /* Add some padding for better clickability */
        }
        main {
            padding: 20px;
            min-height: 50vh; /* Ensure main takes up some vertical space */
        }
        footer {
            background-color: #333;
            color: white;
            padding: 10px;
            text-align: center;
            position: relative; /* To make sure footer stays at the bottom */
            bottom: 0; /* Align to bottom */
            width: 100%;
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
            <li><a href="#">Services</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
    </nav>

    <main>
        <h2>This is the main content area.</h2>
        <p>You can put your text, images, and other content here.</p>
        <img src="https://via.placeholder.com/300" alt="Placeholder Image">
    </main>

    <footer>
        <p>&copy; 2023 My Website. All rights reserved.</p>
    </footer>

</body>
</html>
