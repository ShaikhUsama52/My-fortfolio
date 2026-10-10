<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shaikh Usama - Portfolio</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #0f172a;
            color: #f8fafc;
            line-height: 1.6;
        }

        header {
            background: #1e293b;
            padding: 1.5rem 2rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: sticky;
            top: 0;
            z-index: 100;
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1);
        }

        .logo {
            font-size: 1.5rem;
            font-weight: bold;
            color: #38bdf8;
        }

        nav a {
            color: #cbd5e1;
            text-decoration: none;
            margin-left: 1.5rem;
            transition: color 0.3s;
        }

        nav a:hover {
            color: #38bdf8;
        }

        .hero {
            height: 80vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 0 1rem;
            background: linear-gradient(to bottom, #1e293b, #0f172a);
        }

        .hero h1 {
            font-size: 3rem;
            margin-bottom: 0.5rem;
            color: #f8fafc;
        }

        .hero h1 span {
            color: #38bdf8;
        }

        .hero p {
            font-size: 1.25rem;
            color: #94a3b8;
            margin-bottom: 1.5rem;
        }

        .btn {
            display: inline-block;
            background: #38bdf8;
            color: #0f172a;
            padding: 0.75rem 1.5rem;
            border-radius: 5px;
            text-decoration: none;
            font-weight: bold;
            transition: background 0.3s;
        }

        .btn:hover {
            background: #0ea5e9;
        }

        section {
            padding: 5rem 2rem;
            max-width: 1000px;
            margin: 0 auto;
        }

        section h2 {
            font-size: 2rem;
            margin-bottom: 1.5rem;
            border-bottom: 2px solid #38bdf8;
            display: inline-block;
            padding-bottom: 0.25rem;
        }

        .about p, .contact p {
            color: #94a3b8;
            font-size: 1.1rem;
        }

        .grid-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 1.5rem;
            margin-top: 2rem;
        }

        .card {
            background: #1e293b;
            padding: 1.5rem;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.2);
            transition: transform 0.3s;
        }

        .card:hover {
            transform: translateY(-5px);
        }

        .card h3 {
            margin-bottom: 0.5rem;
            color: #38bdf8;
        }

        .card p {
            color: #94a3b8;
            font-size: 0.95rem;
        }

        .social-links {
            margin-top: 1rem;
        }

        .social-links a {
            display: inline-block;
            background: #334155;
            color: #38bdf8;
            padding: 0.5rem 1rem;
            border-radius: 4px;
            text-decoration: none;
            margin-right: 0.75rem;
            margin-bottom: 0.5rem;
            font-weight: bold;
            transition: background 0.3s;
        }

        .social-links a:hover {
            background: #475569;
        }

        footer {
            text-align: center;
            padding: 2rem;
            background: #1e293b;
            color: #64748b;
        }
    </style>
</head>
<body>

    <header>
        <div class="logo">Shaikh Usama</div>
        <nav>
            <a href="#about">About</a>
            <a href="#experience">Experience</a>
            <a href="#projects">Projects</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <div class="hero">
        <h1>Hi, I'm <span>Shaikh Usama</span></h1>
        <p>CNC Machine Operator & Tech Enthusiast</p>
        <a href="#contact" class="btn">Get In Touch</a>
    </div>

    <section id="about" class="about">
        <h2>About Me</h2>
        <p>Hello! I am Shaikh Usama. I am a dedicated and hardworking professional who has worked as a CNC Machine Operator Trainee at Bajaj. Additionally, I have an interest in technology and programming. I believe in learning new skills and applying them effectively.
.</p>
    </section>

    <section id="experience" class="experience">
        <h2>Work Experience</h2>
        <div class="grid-container">
            <div class="card">
                <h3>CNC Machine Operator Trainee</h3>
                <p style="color: #38bdf8; font-weight: bold; margin-bottom: 0.5rem;">Bajaj Company</p>
                <p>Worked as a Trainee CNC Machine Operator, handling machine operations, ensuring quality production standards, and gaining hands-on industrial manufacturing experience.</p>
            </div>
        </div>
    </section>

    <section id="projects" class="projects">
        <h2>My Projects</h2>
        <div class="grid-container">
            <div class="card">
                <h3>Programming & Development</h3>
            </div>
        </div>
    </section>

    <section id="contact" class="contact">
        <h2>Contact Me</h2>
        <p>You can contact me via the links or details provided below:</p>
        <p style="margin-top: 1rem;"><strong>Email:</strong> shaikhusama5252@gmail.com</p>
        <p><strong>Phone:</strong> +91 9156526266</p>
        
        <div class="social-links">
            <a href="https://github.com/ShaikhUsama52" target="_blank">GitHub Profile</a>
            <a href="https://www.linkedin.com/in/shaikh-usama-aa007431a" target="_blank">LinkedIn Profile</a>
        </div>
    </section>

    <footer>
        <p>&copy; 2026 Shaikh Usama. All rights reserved.</p>
    </footer>

</body>
</html>
