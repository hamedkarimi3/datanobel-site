from pathlib import Path


html_content = """
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DataNobel | Creative Data Intelligence</title>
    <style>
        body {
            margin: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f5f7fa;
            color: #333;
        }
        header {
            background: linear-gradient(90deg, #0d47a1, #1976d2);
            color: white;
            padding: 3rem 1rem;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 3rem;
        }
        header p {
            font-size: 1.25rem;
        }
        nav {
            background-color: #ffffff;
            padding: 1rem;
            text-align: center;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }
        nav a {
            margin: 0 15px;
            color: #0d47a1;
            text-decoration: none;
            font-weight: bold;
        }
        section {
            max-width: 1000px;
            margin: 2rem auto;
            padding: 1rem;
        }
        h2 {
            color: #0d47a1;
        }
        ul {
            list-style-type: square;
            padding-left: 1.5rem;
        }
        .features {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 1.5rem;
        }
        .feature {
            background: #ffffff;
            padding: 1rem;
            border-radius: 8px;
            box-shadow: 0 2px 6px rgba(0,0,0,0.05);
        }
        footer {
            background-color: #0d47a1;
            color: white;
            text-align: center;
            padding: 1.5rem 1rem;
            margin-top: 2rem;
        }
    </style>
</head>
<body>

<header>
    <h1>DataNobel</h1>
    <p>Creative Intelligence in Data, AI, and Analytics</p>
</header>

<nav>
    <a href="#about">About</a>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
</nav>

<section id="about">
    <h2>About Us</h2>
    <p>DataNobel is a cutting-edge data consultancy and research-driven company. We specialize in turning complex datasets into real-world solutions through automation, machine learning, and domain-driven analytics.</p>
</section>

<section id="services">
    <h2>Our Services</h2>
    <div class="features">
        <div class="feature">
            <h3>Data Engineering</h3>
            <p>We build scalable data pipelines, architectures, and infrastructures to automate data flows across systems and teams.</p>
        </div>
        <div class="feature">
            <h3>Omics & Life Sciences</h3>
            <p>We work with multi-omics data (genomics, proteomics, etc.) to support biomedical research and clinical innovation.</p>
        </div>
        <div class="feature">
            <h3>Advanced Analytics</h3>
            <p>Custom visualizations, dashboards, and statistical analysis to inform decisions with clarity and confidence.</p>
        </div>
        <div class="feature">
            <h3>Machine Learning & AI</h3>
            <p>We develop intelligent systems using state-of-the-art ML, NLP, and AI methods tailored to your domain.</p>
        </div>
        <div class="feature">
            <h3>NLP & Language Intelligence</h3>
            <p>Text mining, sentiment analysis, and transformer-based NLP to unlock insights from unstructured data.</p>
        </div>
        <div class="feature">
            <h3>Workflow Automation</h3>
            <p>We design efficient data workflows and CI/CD pipelines to streamline research and development processes.</p>
        </div>
    </div>
</section>

<section id="contact">
    <h2>Contact Us</h2>
    <p>For inquiries, collaborations, or project proposals, please email: <strong><a href="mailto:info@datanobel.se">info@datanobel.se</a></strong></p>
</section>

<footer>
    &copy; 2025 DataNobel. Empowering Insight Through Data.
</footer>

</body>
</html>



