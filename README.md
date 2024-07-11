#Main Flow Task-1
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="A simple webpage with semantic HTML and CSS for structure and styling">
    <title>Simple Webpage</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            color: #333;
            background-color: #f4f4f4;
        }

        header {
            background: #50b3a2;
            color: #fff;
            padding: 1em 0;
            text-align: center;
        }

        nav ul {
            list-style: none;
            padding: 0;
            display: flex;
            justify-content: center;
            background: #333;
        }

        nav ul li {
            margin: 0 1em;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
        }

        main {
            padding: 1em;
        }

        section {
            margin-bottom: 1.5em;
            padding: 1em;
            background: #fff;
            border-radius: 5px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }

        footer {
            text-align: center;
            padding: 1em 0;
            background: #333;
            color: #fff;
        }

        h2 {
            color: #50b3a2;
        }

        p {
            margin-bottom: 1em;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Simple Webpage</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    <main>
        <section id="home">
            <h2>Home</h2>
            <p>This is the home section of the webpage. Here, you can find the latest updates and news about our website. Stay tuned for more exciting content!</p>
            <p>We strive to provide you with the best user experience and valuable information. Explore our site to learn more about what we offer.</p>
        </section>
        <section id="about">
            <h2>About</h2>
            <p>This section provides information about the webpage. Our mission is to create an informative and engaging platform for our users.</p>
            <p>Founded in 2024, our website has been committed to delivering high-quality content and resources to our audience. We cover a variety of topics to keep you informed and entertained.</p>
        </section>
        <section id="services">
            <h2>Services</h2>
            <p>We offer a range of services to cater to your needs:</p>
            <ul>
                <li><strong>Web Development:</strong> Custom website design and development services to bring your vision to life.</li>
                <li><strong>Content Creation:</strong> Professional content writing and editing services to enhance your online presence.</li>
                <li><strong>SEO Optimization:</strong> Strategies to improve your website's visibility on search engines.</li>
                <li><strong>Consulting:</strong> Expert advice and guidance to help you achieve your digital goals.</li>
            </ul>
        </section>
        <section id="contact">
            <h2>Contact</h2>
            <p>This section provides contact information. If you have any questions, suggestions, or feedback, feel free to reach out to us. We'd love to hear from you!</p>
            <h3>Email</h3>
            <p>support@simplewebpage.com</p>
            <h3>Social Media</h3>
            <p>Follow us on our social media channels for the latest updates and community engagement:</p>
            <ul>
                <li><a href="https://facebook.com" target="_blank">Facebook</a></li>
                <li><a href="https://twitter.com" target="_blank">Twitter</a></li>
                <li><a href="https://instagram.com" target="_blank">Instagram</a></li>
            </ul>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 My Simple Webpage</p>
    </footer>
</body>
</html>
