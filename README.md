<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>HWACKER</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #fdfdfd;
      color: #333;
    }

    header {
      background-color: #002244;
      color: white;
      padding: 40px 20px;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 36px;
      letter-spacing: 2px;
    }

    nav {
      background-color: #003366;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      padding: 12px 0;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 20px;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }

    .hero {
      background: linear-gradient(to right, #004080, #0066cc);
      color: white;
      padding: 80px 20px;
      text-align: center;
    }

    .hero h2 {
      font-size: 32px;
      margin-bottom: 10px;
    }

    .hero p {
      font-size: 18px;
      max-width: 700px;
      margin: auto;
    }

    section {
      padding: 60px 20px;
      max-width: 1100px;
      margin: auto;
    }

    section h3 {
      text-align: center;
      color: #002244;
      margin-bottom: 40px;
    }

    .grid {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: space-between;
    }

    .card {
      flex: 1 1 calc(33% - 20px);
      background-color: #ffffff;
      padding: 20px;
      border: 1px solid #ddd;
      border-radius: 8px;
    }

    .card h4 {
      color: #004080;
      margin-bottom: 10px;
    }

    .card p {
      font-size: 14px;
      color: #555;
    }

    footer {
      background-color: #002244;
      color: white;
      text-align: center;
      padding: 30px 20px;
      font-size: 14px;
      margin-top: 40px;
    }

    @media (max-width: 768px) {
      .card {
        flex: 1 1 100%;
      }

      nav a {
        margin: 10px;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>HWACKER</h1>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#services">Services</a>
    <a href="#resources">Resources</a>
    <a href="#contact">Contact</a>
  </nav>

  <div class="hero" id="home">
    <h2>Cybersecurity. Strategy. Integrity.</h2>
    <p>HWACKER delivers digital protection and legal clarity for a connected world.</p>
  </div>

  <section id="about">
    <h3>About HWACKER</h3>
    <p style="text-align: center;">We are a cybersecurity and digital law consultancy focused on helping organizations navigate complex threats and compliance challenges with confidence.</p>
  </section>

  <section id="services">
    <h3>Our Services</h3>
    <div class="grid">
      <div class="card">
        <h4>Penetration Testing</h4>
        <p>Simulated attacks to identify and fix vulnerabilities.</p>
      </div>
      <div class="card">
        <h4>Incident Response</h4>
        <p>Rapid containment and recovery from cyber breaches.</p>
      </div>
      <div class="card">
        <h4>Digital Forensics</h4>
        <p>Investigating and preserving digital evidence.</p>
      </div>
      <div class="card">
        <h4>Cyber Law Advisory</h4>
        <p>Legal guidance on data protection and compliance.</p>
      </div>
      <div class="card">
        <h4>Privacy & Data Governance</h4>
        <p>Helping you align with global privacy frameworks.</p>
      </div>
      <div class="card">
        <h4>Security Awareness Training</h4>
        <p>Educating teams to prevent cyber threats.</p>
      </div>
    </div>
  </section>

  <section id="resources">
    <h3>Resources</h3>
    <p style="text-align: center;">Explore insights, case studies, and updates on cybersecurity and digital law.</p>
  </section>

  <section id="contact">
    <h3>Contact Us</h3>
    <p style="text-align: center;">
      Email: <a href="mailto:princewoods256@gmail.com">princewoods256@gmail.com</a><br />
      Phone: <a href="tel:+256783501222">+256 783 501 222</a>
    </p>
  </section>

  <footer>
    &copy; 2025 HWACKER. All rights reserved.
  </footer>

</body>
</html>
