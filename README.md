# EvohealthAI.github.io

[EvoHealthAI_gradient.html](https://github.com/user-attachments/files/23583203/EvoHealthAI_gradient.html)
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>EvoHealth AI — Predict. Prevent. Evolve.</title>
<style>
  :root{
    --bg:#fbfcff;
    --card:#ffffff;
    --muted:#566270;
    --accent1:#7b61ff;
    --accent2:#4bb6ff;
    --accent3:#ff7ab6;
  }
  *{box-sizing:border-box}
  body{
    margin:0;
    font-family:Inter, "Segoe UI", Roboto, Arial, sans-serif;
    background:linear-gradient(180deg, #f7fbff 0%, #ffffff 100%);
    color:#17202a;
    -webkit-font-smoothing:antialiased;
  }
  header.hero{
    padding:48px 20px;
    text-align:center;
    background:linear-gradient(90deg, rgba(123,97,255,0.12), rgba(75,182,255,0.08));
    border-bottom:1px solid rgba(10,10,10,0.03);
  }
  .brand{
    display:inline-block;
    padding:10px 18px;
    border-radius:999px;
    background:linear-gradient(90deg,var(--accent1),var(--accent2));
    color:white;
    font-weight:700;
    letter-spacing:0.4px;
    box-shadow:0 6px 18px rgba(75,109,255,0.18), inset 0 -4px 12px rgba(255,122,182,0.06);
  }
  h1.title{
    margin:18px 0 6px;
    font-size:clamp(22px,4.5vw,36px);
    line-height:1.05;
    background: linear-gradient(90deg,var(--accent1), var(--accent2), var(--accent3));
    -webkit-background-clip: text;
    background-clip: text;
    color: transparent;
    font-weight:800;
    text-wrap: balance;
    text-shadow: 0 4px 20px rgba(123,97,255,0.08);
  }
  p.lead{
    margin:10px auto 0;
    max-width:820px;
    color:var(--muted);
    font-size:16px;
  }
  .cta{
    margin-top:20px;
  }
  .btn{
    display:inline-block;
    padding:12px 20px;
    border-radius:12px;
    font-weight:700;
    color:white;
    text-decoration:none;
    background:linear-gradient(90deg,var(--accent2),var(--accent1));
    box-shadow:0 8px 24px rgba(75,182,255,0.16);
  }
  main.container{
    max-width:980px;
    margin:28px auto;
    padding:0 20px 80px;
  }
  .grid{
    display:grid;
    grid-template-columns:repeat(2,1fr);
    gap:20px;
  }
  .card{
    background:var(--card);
    border-radius:12px;
    padding:20px;
    box-shadow:0 6px 30px rgba(15,23,42,0.04);
  }
  h3{ margin:0 0 12px; color:#1b2b40 }
  ul{ margin:0; padding-left:18px; color:var(--muted) }
  .full{ grid-column:1/-1 }
  .heart {
    display:inline-block;
    margin-left:8px;
    transform:translateY(1px);
    color:#ff5f9e;
    filter: drop-shadow(0 6px 18px rgba(255,95,158,0.12));
    animation:beat 1.3s infinite;
  }
  @keyframes beat{
    0%{ transform:scale(1) translateY(1px) }
    40%{ transform:scale(1.12) translateY(-2px) }
    80%{ transform:scale(1) translateY(1px) }
  }
  footer{
    text-align:center;
    padding:28px 20px;
    color:var(--muted);
    font-size:14px;
  }
  @media(max-width:880px){
    .grid{ grid-template-columns:1fr }
  }
</style>
</head>
<body>
  <header class="hero">
    <div class="brand">EvoHealth AI</div>
    <h1 class="title">🟣 EvoHealth AI — Predict. Prevent. Evolve.<span class="heart">❤</span></h1>
    <p class="lead">We help you understand how daily habits shape your future health. Get gentle, science-backed nudges to stay well — because your health deserves care and love.</p>
    <div class="cta"><a class="btn" href="#contact">Get Early Access</a></div>
  </header>

  <main class="container">
    <div class="grid">
      <div class="card">
        <h3>What is EvoHealth?</h3>
        <p style="color:var(--muted)">An AI-powered prediction platform that uses lifestyle data — sleep, diet, activity, and stress — to forecast risks for diabetes, heart disease, neurological and cancer-related conditions. We focus on prevention and personalized guidance.</p>
      </div>

      <div class="card">
        <h3>Why it feels like care</h3>
        <p style="color:var(--muted)">Warm, easy-to-understand scores, gentle alerts, and human-centered recommendations — designed to feel supportive, not clinical.</p>
      </div>

      <div class="card">
        <h3>How it works</h3>
        <ul>
          <li>Enter basic lifestyle & health metrics</li>
          <li>AI analyzes patterns and predicts risk</li>
          <li>Receive personalized preventive tips</li>
          <li>Track trends and get timely nudges</li>
        </ul>
      </div>

      <div class="card">
        <h3>Key features</h3>
        <ul>
          <li>Personalized risk scores</li>
          <li>Health trend visualizations</li>
          <li>Preventive recommendations</li>
          <li>Privacy-first design</li>
        </ul>
      </div>

      <div class="card full">
        <h3 id="contact">Contact & Get Early Access</h3>
        <p style="color:var(--muted)">Email: <a href="mailto:evohealth.ai.team@gmail.com">evohealth.ai.team@gmail.com</a> • Instagram: <a href="https://instagram.com/evohealth.ai" target="_blank">@evohealth.ai</a></p>
        <p style="color:var(--muted)">GitHub: <a href="https://github.com/EvohealthAI" target="_blank">github.com/EvohealthAI</a></p>
        <p style="color:var(--muted)">© 2025 EvoHealth AI — Because every life deserves tomorrow.</p>
      </div>
    </div>
  </main>

  <footer>
    Crafted with care ❤️ · Predict • Prevent • Evolve
  </footer>
</body>
</html>
