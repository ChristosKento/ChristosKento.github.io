<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Simple Webpage</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        nav {
            background-color: #3498db;
            padding: 10px;
        }
        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin-right: 15px;
        }
        nav a {
            color: white;
            text-decoration: none;
        }
        h1 {
            font-size: 36px;
            font-weight: bold;
            color: #3498db;
        }
        p {
            font-size: 18px;
            line-height: 1.6;
            color: #333;
        }
    </style>
</head>

<body>
    <nav>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#blog">Blog</a></li>
        </ul>
    </nav>

    <h1>My first website</h1>
    
    <p>This is my first time using HTML to create a webpage. I have been learning through my online course about the basics of coding. However, this is me trying to actually code and to make somewhat of a decent page. I will just keep adding more code so hopefully the page becomes more advanced.</p>
    
    <div>As of 05/10/24 it hasn't even been a week since I started to learn how to code. To be honest, this page isn't being constructed from what I've learned from the course but rather trial and error, and using online resources.</div>

    <h2 id="projects">Projects I would like to take on</h2>
    <p>- Blogging</p>
    <p>- Online gym training</p>
    <p>- Clothing brand but start with POD</p>
    <p>- Build and keep working on my personal brand which links with all my other projects</p>

    <h3>Blogging</h3>
    
    <button onclick="showMessage()">Click me for a SURPRISE!</button>

    <script>
        function showMessage() {
            alert('Hello, welcome to my blog!');
        }
        
   </script>
    <select name="Brand">
    <option value="Nike">nike</option>
    <option value="Adidas">adidas</option>
    <option value="New Balance">new balance</option>
    <option value="Puma">puma</option>
    </select>
</body>
</html>
