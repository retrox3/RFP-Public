<!DOCTYPE html>
<html lang="en">
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Retros File Packs</title>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@600&family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <link rel="icon" type="image/png" href="images/RFP_favicon.ico">
    <style>
      :root {
      --color1: #1a1a2e;
      --color2: #16213e;
      --color3: #0f3460;
      --color4: #e94560;
      --color5: #f5f6fa;
      --color-accent: #17e9e0;
      }
      * {
      box-sizing: border-box;
      }
      body {
      margin: 0;
      font-family: 'Roboto', Arial, sans-serif;
      background: linear-gradient(135deg, var(--color2) 0%, var(--color3) 100%);
      color: var(--color5);
      min-height: 100vh;
      }
      header {
      background: linear-gradient(90deg, var(--color1) 60%, var(--color4) 100%);
      padding: 2rem 1rem;
      text-align: center;
      box-shadow: 0 2px 16px rgba(0,0,0,0.2);
      }
      header h1 {
      font-family: 'Montserrat', sans-serif;
      color: var(--color-accent);
      font-size: 2.8rem;
      letter-spacing: 2px;
      margin-bottom: 0.5rem;
      }
      header p {
      font-size: 1.2rem;
      color: var(--color5);
      letter-spacing: 1px;
      margin-top: 0;
      }
      main {
      display: flex;
      flex-wrap: wrap;
      gap: 2rem;
      justify-content: center;
      align-items: flex-start;
      padding: 2rem 1rem;
      }
      .card {
      background: linear-gradient(120deg, var(--color4) 10%, var(--color3) 100%);
      border-radius: 16px;
      box-shadow: 0 6px 24px rgba(17, 233, 224, 0.10);
      overflow: hidden;
      width: 340px;
      transition: transform 0.25s cubic-bezier(.4,2,.6,1), box-shadow 0.25s;
      position: relative;
      }
      .card:hover {
      transform: translateY(-8px) scale(1.04);
      box-shadow: 0 10px 32px rgba(17, 233, 224, 0.20);
      }
      .card img {
      display: block;
      width: 100%;
      height: 180px;
      object-fit: cover;
      background: var(--color2);
      }
      .card-content {
      padding: 1.2rem 1.2rem 1.6rem;
      }
      .card-title {
      font-family: 'Montserrat', sans-serif;
      color: var(--color-accent);
      font-size: 1.5rem;
      margin: 0 0 0.5rem;
      }
      .card-desc {
      color: #f8faff;
      font-size: 1rem;
      margin-bottom: 1rem;
      }
      .card-tag {
      display: inline-block;
      background: var(--color-accent);
      color: var(--color2);
      font-size: 0.8rem;
      font-weight: bold;
      border-radius: 12px;
      padding: 4px 12px;
      margin-right: 6px;
      margin-bottom: 5px;
      letter-spacing: 1px;
      }
      .bottom-buttons {
      position: fixed;
      left: 0;
      right: 0;
      bottom: 0;
      display: flex;
      justify-content: center;
      gap: 2rem;
      padding: 1.5rem 0 1.5rem 0;
      background: linear-gradient(90deg, var(--color1) 60%, var(--color3) 100%);
      z-index: 100;
      }
      .bottom-btn {
      font-family: 'Montserrat', sans-serif;
      font-size: 1.2rem;
      padding: 1rem 2.5rem;
      border: none;
      border-radius: 32px;
      background: var(--color-accent);
      color: var(--color2);
      font-weight: bold;
      cursor: pointer;
      box-shadow: 0 4px 16px rgba(17, 233, 224, 0.15);
      transition: background 0.2s, color 0.2s, transform 0.15s;
      }
      .bottom-btn:hover {
      background: var(--color4);
      color: #fff;
      transform: scale(1.05);
      }
      footer {
      background: var(--color1);
      color: var(--color-accent);
      text-align: center;
      padding: 1rem 0;
      font-size: 1rem;
      margin-top: 2rem;
      letter-spacing: 1px;
      }
      @media (max-width: 900px) {
      main { flex-direction: column; align-items: center; }
      .bottom-buttons { flex-direction: column; gap: 1rem; }
      }
      body { padding-bottom: 110px; }
    </style>
  </head>
  <body>
    <div class="bottom-buttons">
      <button class="bottom-btn" onclick="window.location.href='aboutme.html'">Go to About Me</button>
      <button class="bottom-btn" onclick="window.location.href='downloadspage.html'">Go to Downloads</button>
    </div>
<body>
  <header>
    <h1>Stuff Currently Listed</h1>
    <p>Download Or Learn below</p>
  </header>
  <main>
    <div class="card">
      <img src="images/foragung2.png" alt="Thumbnail 1">
      <div class="card-content">
        <span class="card-tag">Thumbnail Editing</span>
        <h2 class="card-title">How I Make My Thumbnails</h2>
        <p class="card-desc">
         I Will Teach You How I Make My Thumbnails For The Videos I Create.
        </p>
      </div>
    </div>
    <div class="card">
      <img src="images/3softwares.png" alt="Video 1">
      <div class="card-content">
        <span class="card-tag">Video Editing</span>
        <h2 class="card-title">Learn My Style Of Editing</h2>
        <p class="card-desc">
          This Will Teach You How I Edit My Videos And The Tools I Use To Create Them.
        </p>
      </div>
    </div>
    <div class="card">
      <img src="images/obs.jpeg" alt="Recording 1">
      <div class="card-content">
        <span class="card-tag">Recording</span>
        <h2 class="card-title">How I Record Videos</h2>
        <p class="card-desc">
          A Quick Guide On How I Record My Videos And What Software I Use, What I Also Recommend.
        </p>
      </div>
    </div>
    <!-- Add more cards or replace image src as needed -->
  </main>
  <footer>
    &copy; 2025 RetrosFilePacks | Designed BY Retro
  </footer>
</body>
</html>
