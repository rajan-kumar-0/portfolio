# portfolio

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Rajan Kumar | Split-Screen Portfolio</title>

  <!-- Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&family=Playfair+Display:wght@500;600&display=swap" rel="stylesheet">

  <style>
    :root {
      --dark: #0b0f14;
      --dark-soft: #121821;
      --neon: #00e5a8;
      --text: #e6e6e6;
      --muted: #a1a1aa;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      background: var(--dark);
      color: var(--text);
      font-family: 'Inter', sans-serif;
    }

    /* MASTER BIO */
    .master-bio {
      padding: 80px 12%;
      text-align: center;
      border-bottom: 1px solid #1f2933;
    }

    .master-bio h1 {
      font-size: 3.2rem;
      margin-bottom: 15px;
    }

    .master-bio span { color: var(--neon); }

    .master-bio p {
      max-width: 800px;
      margin: 0 auto;
      color: var(--muted);
      font-size: 1.1rem;
    }

    /* SPLIT SCREEN */
    .split {
      display: grid;
      grid-template-columns: 1fr 1fr;
      min-height: 100vh;
    }

    section {
      padding: 70px 10%;
    }

    /* LEFT: PROFESSIONAL */
    .professional {
      background: linear-gradient(180deg, #0b0f14, #05080d);
      border-right: 1px solid #1f2933;
    }

    .professional h2 {
      color: var(--neon);
      margin-bottom: 25px;
      font-size: 2rem;
    }

    .block {
      background: var(--dark-soft);
      padding: 24px;
      border-radius: 14px;
      margin-bottom: 25px;
    }

    .block h3 { margin-bottom: 8px; }

    .block p { color: var(--muted); font-size: 0.95rem; }

    /* RIGHT: PERSONAL */
    .personal {
      background: radial-gradient(circle at top, #0f172a, #020617);
      font-family: 'Playfair Display', serif;
    }

    .personal h2 {
      font-size: 2.2rem;
      margin-bottom: 25px;
      color: #ffffff;
    }

    .personal .block {
      background: rgba(255,255,255,0.04);
      border: 1px dashed rgba(255,255,255,0.15);
    }

    footer {
      padding: 30px;
      text-align: center;
      color: #71717a;
      border-top: 1px solid #1f2933;
    }

    @media (max-width: 900px) {
      .split { grid-template-columns: 1fr; }
      .professional { border-right: none; border-bottom: 1px solid #1f2933; }
    }
  </style>
</head>
<body>

  <!-- MASTER BIO -->
  <div class="master-bio">
    <h1>Rajan <span>Kumar</span></h1>
    <p>
      A Computer Science Engineering student balancing structured problem-solving
      with human curiosity — building software with discipline while living life
      beyond the desk.
    </p>

    <!-- SOCIAL CONNECTIONS -->
    <div style="margin-top:30px; display:flex; justify-content:center; gap:25px;">
      <a href="https://www.linkedin.com/in/rajan-kumar-6900ba2aa" target="_blank" style="color:#00e5a8; font-weight:600;">LinkedIn</a>
      <a href="https://github.com/rajan-kumar-0" target="_blank" style="color:#00e5a8; font-weight:600;">GitHub</a>
      <a href="mailto:rajank0464@gmail.com" style="color:#00e5a8; font-weight:600;">Email</a>
    </div>
  </div>

  <!-- SPLIT CONTENT -->
  <div class="split">

    <!-- PROFESSIONAL IDENTITY -->
    <section class="professional">
      <h2>Professional Identity</h2>

      <div class="block">
        <h3>Resume Snapshot</h3>
        <p>B.Tech CSE | Jagannath University, Jaipur</p>
      </div>

      <div class="block">
        <h3>Technical Skills</h3>
        <p>C, C++, Java, Python (learning)<br>DSA, OOPS, Git, GitHub, Linux</p>
      </div>

      <div class="block">
        <h3>Projects</h3>
        <p>Academic and self-learning projects focused on problem-solving and core CS.</p>
      </div>
    </section>

    <!-- PERSONAL IDENTITY -->
    <section class="personal">
      <h2>Personal Identity</h2>

      <div class="block">
        <h3>Beyond the Desk</h3>
        <p>
          [Hobby] helps me slow down, reflect, and stay grounded outside of code.
        </p>
      </div>

      <div class="block">
        <h3>Travels & Roots</h3>
        <p>Originally from Siwan, Bihar — currently living and studying in Jaipur.</p>
      </div>

      <div class="block">
        <h3>Personal Notes</h3>
        <p>Curious by nature, disciplined by choice, and always learning.</p>
      </div>
    </section>

  </div>

  <footer>
    © 2026 Rajan Kumar • Two worlds, one identity
  </footer>

</body>
</html>
