# alvirauk.github.io
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Alvira Khan - Data Analyst</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css" integrity="sha512-z3gLpd7yknf1YoNbCzqRKc4qyor8gaKU1qmn+CShxbuBusANI9QpRohGBreCFkKxLhei6S9CQXFEbbKuqLg0DA==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="responsive.css">
</head>

<body>
    <!-- Navbar Header -->
    <header class="header">
        <nav class="navbar">
            <div class="logo">
                <h2 class="logo-heading">Alvira Khan</h2>
            </div>
            <div class="hamburger" id="hamburger">
                <i class="fas fa-bars hamburger-icon"></i>
                <i class="fas fa-times cross-icon"></i>
            </div>
            <div class="menu">
                <ul class="menu-list">
                    <li class="menu-list-items"><a class="links" href="#home">Home</a></li>
                    <li class="menu-list-items"><a class="links" href="#portfolio">Portfolio</a></li>
                    <li class="menu-list-items"><a class="links" href="#about">About</a></li>
                    <li class="menu-list-items"><a class="links" href="#services">Services</a></li>
                    <li class="menu-list-items"><a class="links" href="#contact">Contact</a></li>
                </ul>
            </div>
        </nav>
    </header>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="intro">
            <div class="headings">
                <h3 class="greet-heading">Hello, I'm</h3>
                <h1 class="my-heading">Alvira Khan</h1>
                <h4 class="sub-heading">A Data Analyst with Expertise in Business Intelligence & Visualization</h4>
            </div>
            <div class="intro-buttons">
                <button class="btn common-btn">Hire Me</button>
                <button class="btn ghost-btn">Get Resume</button>
            </div>
        </div>
    </section>

    <!-- Portfolio Section -->
    <section class="portfolio" id="portfolio">
        <div class="portfolio-heading">
            <h1 class="my-heading text-center">My Work</h1>
        </div>
        <div class="portfolio-content">
            <div class="my-row">
                <div class="my-col">
                    <div class="my-card port-card">
                        <div class="image">
                            <img src="./Images/data_viz.avif" alt="Data Visualization">
                        </div>
                        <h3 class="greet-heading blue-text">Data Visualization</h3>
                        <p class="small-para blue-text">Using Tableau & Power BI</p>
                    </div>
                </div>
                <div class="my-col">
                    <div class="my-card port-card">
                        <div class="image">
                            <img src="./Images/machine_learning.avif" alt="Machine Learning">
                        </div>
                        <h3 class="greet-heading blue-text">Machine Learning</h3>
                        <p class="small-para blue-text">Predictive Analytics</p>
                    </div>
                </div>
                <div class="my-col">
                    <div class="my-card port-card">
                        <div class="image">
                            <img src="./Images/sql_analysis.avif" alt="SQL Analysis">
                        </div>
                        <h3 class="greet-heading blue-text">SQL Analysis</h3>
                        <p class="small-para blue-text">Data Querying & Processing</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="about">
        <div class="about-text">
            <h1 class="my-heading">About Me</h1>
            <p class="lead-para">I am a passionate Data Analyst specializing in business intelligence, data visualization, and statistical analysis. I have experience in using Tableau, Power BI, Python, SQL, and Excel to provide data-driven solutions that drive business success.</p>
        </div>
        <div class="about-image">
            <img src="./Images/alvira_profile.avif" alt="About Alvira">
        </div>
    </section>

    <!-- Contact Section -->
    <section class="contact" id="contact">
        <div class="contact-heading">
            <h1 class="my-heading text-center">Contact Me</h1>
        </div>
        <div class="contact-content">
            <div class="contact-form-container">
                <h1 class="greet-heading">Get In Touch</h1>
                <form class="contact-form">
                    <input class="form-controls" type="text" placeholder="Your Name">
                    <input class="form-controls" type="email" placeholder="Your Email">
                    <input class="form-controls" type="text" placeholder="Your Phone">
                    <textarea class="form-controls" placeholder="Write your message" cols="30" rows="10"></textarea>
                    <input class="form-btn btn common-btn" type="submit" value="Send Message">
                </form>
            </div>
        </div>
    </section>

    <!-- Footer Section -->
    <footer class="footer">
        <div class="footer-content text-center">
            <h4>Copyright © 2025 All rights reserved | Designed by Alvira Khan</h4>
            <div class="social-links">
                <div class="footer-menu">
                    <ul class="footer-menu-list">
                        <li class="footer-list-items"><a class="footer-links" href="#"><i class="fab fa-linkedin"></i></a></li>
                        <li class="footer-list-items"><a class="footer-links" href="#"><i class="fab fa-github"></i></a></li>
                        <li class="footer-list-items"><a class="footer-links" href="#"><i class="fab fa-twitter"></i></a></li>
                    </ul>
                </div>
            </div>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
