<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sanya Jain - GitHub Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
        }
        nav {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 10px;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            font-size: 1.1rem;
        }
        section {
            padding: 20px;
        }
        .container {
            max-width: 1200px;
            margin: auto;
            background: #fff;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }
        .intro {
            display: flex;
            align-items: center;
            gap: 20px;
            padding: 20px;
        }
        .intro img {
            border-radius: 50%;
            width: 150px;
            height: 150px;
            object-fit: cover;
        }
        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            padding: 20px;
        }
        .card {
            background: #f9f9f9;
            border: 1px solid #ddd;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s;
        }
        .card:hover {
            transform: translateY(-5px);
        }
        .card img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }
        .card h3 {
            margin: 10px 15px;
        }
        .card p {
            margin: 10px 15px;
            color: #555;
        }
        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 20px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Sanya Jain</h1>
        <nav>
            <a href="#about">About</a>
            <a href="#experience">Experience</a>
            <a href="#projects">Projects</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section id="about" class="container">
        <div class="intro">
            <img src="https://via.placeholder.com/150" alt="Sanya Jain">
            <div>
                <h2>About Me</h2>
                <p>Hello! I'm Sanya Jain, a second-year MBA candidate at Chicago Booth. I'm passionate about technology, supply chain, finance, and entrepreneurship.</p>
            </div>
        </div>
    </section>

    <section id="experience" class="container">
        <h2>Experience</h2>
        <ul>
            <li><strong>Amazon</strong>: Incoming MBA Leadership Development Associate</li>
            <li><strong>Procter & Gamble</strong>: Led operations in South Asia with $66M in annual revenue.</li>
            <li><strong>Evercore Partners</strong>: Investment Banking Summer Associate.</li>
        </ul>
    </section>

    <section id="projects" class="container">
        <h2>Projects</h2>
        <div class="projects">
            <div class="card">
                <img src="https://via.placeholder.com/300x200" alt="Project 1">
                <h3>Cultural Differences Study</h3>
                <p>Analyzed risk aversion between Chile and the USA.</p>
            </div>
            <div class="card">
                <img src="https://via.placeholder.com/300x200" alt="Project 2">
                <h3>Market Penetration Strategy</h3>
                <p>Collaborated with startups to optimize market entry strategies.</p>
            </div>
            <div class="card">
                <img src="https://via.placeholder.com/300x200" alt="Project 3">
                <h3>Pampers Product Launch</h3>
                <p>Delivered $7M YoY cost savings through a new product launch.</p>
            </div>
        </div>
    </section>

    <section id="contact" class="container">
        <h2>Contact</h2>
        <p>Email: <a href="mailto:sanya.jain@chicagobooth.edu">sanya.jain@chicagobooth.edu</a></p>
        <p>LinkedIn: <a href="https://www.linkedin.com/in/sanyajain">Sanya Jain</a></p>
        <p>Twitter: <a href="https://twitter.com/sanyajain">@sanyajain</a></p>
    </section>

    <footer>
        <p>&copy; 2025 Sanya Jain</p>
    </footer>
</body>
</html>

