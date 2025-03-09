<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Alvira Khan - Data Analyst</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="responsive.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #121212;
            color: white;
            margin: 0;
            padding: 0;
        }
        .section-container {
            display: flex;
            flex-direction: row;
            justify-content: space-around;
            align-items: center;
            flex-wrap: wrap;
            padding: 50px 0;
            background: linear-gradient(135deg, #ff416c, #ff4b2b);
            color: white;
            text-align: center;
        }
        .portfolio-content, .services-content {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }
        .my-card {
            background: #1e1e1e;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(255, 75, 43, 0.5);
            text-align: center;
            width: 300px;
        }
        .my-card img {
            width: 100%;
            border-radius: 10px;
        }
        .hero {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 50px;
            background-color: #1e1e1e;
            text-align: left;
        }
        .hero img {
            max-width: 40%;
            border-radius: 10px;
        }
        .contact-content {
            background-color: #ff4b2b;
            color: white;
            padding: 50px;
            text-align: center;
        }
    </style>
</head>

<body>
    <header class="header">
        <nav class="navbar">
            <div class="logo">
                <h2 class="logo-heading">Alvira Khan</h2>
            </div>
        </nav>
    </header>

    <section id="home" class="hero">
        <div>
            <h1>HELLO!</h1>
            <h2>I Am Alvira Khan</h2>
            <p>A Data Analyst with expertise in Business Intelligence, Machine Learning, and Data Visualization.</p>
            <button class="btn common-btn">View Work</button>
            <button class="btn ghost-btn">Hire Me</button>
        </div>
        <img src="./mnt/data/image.png" alt="Alvira Khan">
    </section>

    <section class="section-container" id="portfolio">
        <h1>My Work</h1>
        <div class="portfolio-content">
            <div class="my-card">
                <img src="./Images/data_viz.avif" alt="Data Visualization">
                <h3>Data Visualization</h3>
                <p>Tableau, Power BI, Flourish</p>
            </div>
            <div class="my-card">
                <img src="./Images/machine_learning.avif" alt="Machine Learning">
                <h3>Machine Learning</h3>
                <p>Python, NLP, Hugging Face</p>
            </div>
            <div class="my-card">
                <img src="./Images/sql_analysis.avif" alt="SQL Analysis">
                <h3>SQL Analysis</h3>
                <p>Data Querying & Processing</p>
            </div>
        </div>
    </section>

    <section class="section-container" id="services">
        <h1>Skills</h1>
        <div class="services-content">
            <div class="my-card">
                <h3>Data Visualization</h3>
                <p>Tableau, Power BI, Flourish</p>
            </div>
            <div class="my-card">
                <h3>SQL & Data Querying</h3>
                <p>SQL, PostgreSQL, MySQL</p>
            </div>
            <div class="my-card">
                <h3>Machine Learning</h3>
                <p>Python, NLP, Hugging Face</p>
            </div>
            <div class="my-card">
                <h3>Financial Analysis</h3>
                <p>Business Intelligence & Risk Assessment</p>
            </div>
        </div>
    </section>

    <section class="contact-content" id="contact">
        <h1>Contact Me</h1>
        <p>Email: alvirauk@gmail.com | Phone: 07711923312</p>
        <p>LinkedIn: <a href="https://www.linkedin.com/in/alvira-khan98" target="_blank">Alvira Khan</a></p>
    </section>
</body>
</html>
