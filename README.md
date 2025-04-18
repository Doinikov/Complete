<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Complete AI — Official Site</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: #1e1f22;
      color: #fff;
    }
    a {
      color: #0af;
      text-decoration: none;
    }
    header {
      display: flex;
      align-items: center;
      padding: 20px 40px;
    }
    header img {
      height: 48px;
      width: auto;
    }
    .hero {
      text-align: center;
      padding: 40px 20px 20px;
    }
    .hero p.description {
      max-width: 800px;
      margin: 0 auto;
      font-size: 16px;
      line-height: 1.7;
      opacity: 0.9;
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
      text-align: center;
      padding: 60px 20px;
    }
    .section h2 {
      font-size: 36px;
      margin-bottom: 40px;
    }
    .article-block {
      margin-bottom: 40px;
    }
    .article-block h3 {
      font-size: 22px;
      margin-bottom: 10px;
    }
    .article-block p {
      font-size: 16px;
      line-height: 1.5;
      opacity: 0.85;
    }
    .article-block a {
      display: inline-block;
      margin-top: 8px;
      font-weight: bold;
    }
    .cta {
      text-align: center;
      padding: 60px 20px;
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
    footer {
      font-size: 13px;
      background: #000;
      color: #777;
      text-align: center;
      padding: 30px 20px;
    }
  </style>
</head>
<body>

  <!-- ЛОГОТИП -->
  <header>
    <img src="Screenshot 2025-04-16 222227.png" alt="Complete Logo" />
  </header>

  <!-- HERO + описание -->
  <div class="hero">
    <p class="description">
      <strong>SOLUTION (WHAT MAKES US UNIQUE)</strong><br><br>
      Freedom to Choose AI Models Without Leaving the Interface — Multiple platforms (GPT, Claude, Mistral, etc.) in a single workspace, with quick switching and no loss of context—whether in Prompt mode or Classic Chat.<br><br>
      <strong>Adapted Interface for Prompts and Chat + Flowchart-Based Script Editor</strong><br>
      Prompt Mode featuring a “static” text window (open/close at will), making it easier to revise and resend queries. Script Selection available right in the Prompt interface, alongside model switching. Classic Chatbot working with the same AI models. Flowchart Editor on Desktop for visually building complex scripts, which remain accessible in the mobile version.<br><br>
      <strong>Convenient Storage and Reusability</strong><br>
      Library for structured storage of prompts, chats, and scripts. Sharing options, favorites, and a corporate mode that lets you easily share and reuse your resources.<br><br>
      The refined AI workspace for all your text workflows.
    </p>
    <button onclick="document.getElementById('articles').scrollIntoView({behavior: 'smooth'})">EXPLORE ↓</button>
  </div>

  <!-- СТАТЬИ -->
  <div id="articles" class="section">
    <h2>Latest AI Insights</h2>

    <div class="article-block">
      <h3>GPT-5 Release Date & Features: Everything we know</h3>
      <p>Overview of expected capabilities and release date for GPT-5.</p>
      <a href="https://blog.promptlayer.com/gpt-5/" target="_blank">Read more →</a>
    </div>
    <div class="article-block">
      <h3>Claude 3 vs GPT-4: Who's ranking better?</h3>
      <p>Performance comparison between Claude 3 and GPT-4 in different tasks.</p>
      <a href="https://www.proxet.com/blog/claude-3-vs-gpt-4-the-competitive-ai-landscape-weve-all-been-waiting-for" target="_blank">Read more →</a>
    </div>
    <div class="article-block">
      <h3>Sora: Creating video from text</h3>
      <p>OpenAI introduces Sora – a video generation model powered by text input.</p>
      <a href="https://openai.com/sora" target="_blank">Read more →</a>
    </div>
    <div class="article-block">
      <h3>Google's Gemini 1.5: Smarter and faster</h3>
      <p>Deep dive into Gemini 1.5’s capabilities and architecture.</p>
      <a href="https://blog.google/technology/ai/google-gemini-1-5/" target="_blank">Read more →</a>
    </div>
    <div class="article-block">
      <h3>The 50 Best AI Tools in 2025 (Tried & Tested)</h3>
      <p>Collection of top AI tools and platforms to boost productivity in 2025.</p>
      <a href="https://www.synthesia.io/post/ai-tools" target="_blank">Read more →</a>
    </div>
    <div class="article-block">
      <h3>AI in the Workplace: Report 2025</h3>
      <p>McKinsey’s analysis on the impact of AI on workplace efficiency.</p>
      <a href="https://www.mckinsey.com/capabilities/mckinsey-digital/our-insights/superagency-in-the-workplace" target="_blank">Read more →</a>
    </div>
    <div class="article-block">
      <h3>Open-source AI: What’s real in 2025</h3>
      <p>How open-source models are being used in real business scenarios.</p>
      <a href="https://venturebeat.com/ai/open-source-ai-growth-2025/" target="_blank">Read more →</a>
    </div>
    <div class="article-block">
      <h3>Best AI startups to watch this year</h3>
      <p>A curated list of AI startups that are disrupting their industries.</p>
      <a href="https://techcrunch.com/2025/03/ai-startups-to-watch/" target="_blank">Read more →</a>
    </div>
  </div>

  <!-- ПОДПИСКА -->
  <div class="cta">
    <h2>Stay Updated</h2>
    <p>Get weekly insights on AI tools and real-world applications</p>
    <form>
      <input type="email" placeholder="Email" required>
      <br>
      <button type="submit">GET NOTIFIED →</button>
    </form>
  </div>

  <!-- ФУТЕР -->
  <footer>
    &copy; 2025 Complete AI — <a href="https://completeapp.ai" target="_blank">completeapp.ai</a> — contact@completeapp.ai
  </footer>

</body>
</html>
