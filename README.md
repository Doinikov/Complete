<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Complete AI — Official Site</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: #111;
      color: #fff;
    }
    a {
      color: #0af;
      text-decoration: none;
    }
    header, footer, .section, .cta {
      text-align: center;
      padding: 60px 20px;
    }
    .hero {
      background: linear-gradient(135deg, #111 0%, #222 100%);
      padding: 120px 20px 80px;
    }
    .hero h1 {
      font-size: 60px;
      margin: 0;
    }
    .hero p {
      margin-top: 20px;
      font-size: 18px;
      opacity: 0.7;
    }
    .hero button {
      margin-top: 40px;
      padding: 14px 30px;
      border: 1px solid #fff;
      border-radius: 30px;
      background: transparent;
      color: #fff;
      font-weight: bold;
      font-size: 14px;
      cursor: pointer;
    }
    .section {
      max-width: 800px;
      margin: auto;
    }
    .section h2 {
      font-size: 36px;
      margin-bottom: 20px;
    }
    .section p {
      font-size: 16px;
      line-height: 1.6;
      opacity: 0.85;
    }
    .section a {
      display: inline-block;
      margin-top: 12px;
      font-weight: bold;
    }
    .cta input[type="email"] {
      padding: 12px;
      width: 300px;
      max-width: 90%;
      border-radius: 25px;
      border: 1px solid #555;
      background: #111;
      color: #fff;
      outline: none;
      margin-bottom: 20px;
    }
    .cta button {
      display: block;
      margin: 0 auto;
      padding: 10px 30px;
      border-radius: 25px;
      border: none;
      background: #0af;
      color: #000;
      font-weight: bold;
      cursor: pointer;
    }
    .social-icons a {
      margin: 0 10px;
      font-size: 20px;
      display: inline-block;
      color: #fff;
    }
    footer {
      font-size: 13px;
      background: #000;
      color: #777;
    }
  </style>
</head>
<body>
  <div class="hero">
    <p>LOREM IPSUM</p>
    <h1>Complete AI</h1>
    <p>AI platform for writing, prompting, and automation</p>
    <button onclick="document.getElementById('articles').scrollIntoView({behavior: 'smooth'})">EXPLORE ↓</button>
  </div>

  <div id="articles" class="section">
    <h2>Top AI Insights</h2>

    <div class="article-block">
      <h3>🔥 GPT-5 is coming: What to expect</h3>
      <p>Explore the leaked capabilities and expected improvements in GPT-5 and what it means for your workflows.</p>
      <a href="#">Read more →</a>
    </div>

    <div class="article-block">
      <h3>Claude 3 vs GPT-4: Real-world test results</h3>
      <p>We benchmarked Claude and GPT in various business scenarios. Here’s what we found.</p>
      <a href="#">Read more →</a>
    </div>

    <div class="article-block">
      <h3>Multimodal AI: What it actually means in 2025</h3>
      <p>A simple explanation of vision+text+audio AI systems and how they’re being used by real teams today.</p>
      <a href="#">Read more →</a>
    </div>
  </div>

  <div class="cta">
    <p>MAGNA SED</p>
    <h2>Stay Updated</h2>
    <p>Get weekly insights on AI tools and real-world applications</p>
    <form>
      <input type="email" placeholder="Email" required>
      <br>
      <button type="submit">GET NOTIFIED →</button>
    </form>
    <div class="social-icons">
      <a href="#" aria-label="Twitter">🐦</a>
      <a href="#" aria-label="Instagram">📸</a>
      <a href="#" aria-label="Facebook">📘</a>
      <a href="#" aria-label="Email">✉️</a>
    </div>
  </div>

  <footer>
    &copy; 2025 Complete AI — completeapp.ai — contact@completeapp.ai
  </footer>
</body>
</html>
