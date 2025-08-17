<!doctype html>
<html lang="de">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title><YOUR_NAME> · Full Stack Developer</title>
  <style>
    :root { --bg:#0f1222; --fg:#e9ecf1; --muted:#a6b0c3; --card:#161a2e; --acc:#6c8cff; }
    *{box-sizing:border-box} body{margin:0;font:16px/1.6 system-ui,Segoe UI,Roboto,Ubuntu,sans-serif;background:var(--bg);color:var(--fg)}
    .wrap{max-width:980px;margin:0 auto;padding:32px}
    header{display:flex;align-items:center;justify-content:space-between;gap:16px;margin-bottom:24px}
    .title{font-size:28px;font-weight:700}
    .tag{background:var(--card);padding:6px 10px;border-radius:999px;color:var(--acc);font-weight:600}
    .grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:16px}
    .card{background:var(--card);padding:18px;border-radius:16px;border:1px solid rgba(255,255,255,.06)}
    h2{margin:0 0 10px 0;font-size:18px}
    ul{margin:8px 0 0 18px;padding:0}
    a{color:var(--acc);text-decoration:none} a:hover{text-decoration:underline}
    footer{margin-top:28px;color:var(--muted);font-size:14px}
    .pill{display:inline-block;background:#212646;padding:4px 10px;border-radius:999px;margin:4px 6px 0 0;color:#c7d0ea;font-size:14px}
    .row{display:flex;flex-wrap:wrap;gap:8px}
  </style>
</head>
<body>
  <div class="wrap">
    <header>
      <div class="title">👋 Hi, ich bin <b><YOUR_NAME></b></div>
      <div class="tag">Full Stack Developer</div>
    </header>

    <div class="grid">
      <section class="card">
        <h2>Über mich</h2>
        <p>Ich entwickle komplette Anwendungen end-to-end: UI/UX, Frontend (Vue/React/HTML5), Backend (Node, Python, .NET/C#, PHP, Lua) und Deployment auf Linux (Debian 11). Datenbasis: MySQL, Versionskontrolle & Releases via Git.</p>
      </section>

      <section class="card">
        <h2>Frontend</h2>
        <div class="row">
          <span class="pill">UI/UX</span><span class="pill">React</span><span class="pill">Vue</span>
          <span class="pill">HTML5</span><span class="pill">CSS3</span><span class="pill">TypeScript</span><span class="pill">JavaScript</span>
        </div>
      </section>

      <section class="card">
        <h2>Backend</h2>
        <div class="row">
          <span class="pill">Node.js</span><span class="pill">Python</span><span class="pill">.NET Core (C#)</span>
          <span class="pill">PHP</span><span class="pill">Lua (FiveM)</span>
        </div>
      </section>

      <section class="card">
        <h2>Dev & Ops</h2>
        <div class="row">
          <span class="pill">Git</span><span class="pill">Linux (Debian 11)</span><span class="pill">Deployments</span>
          <span class="pill">MySQL</span>
        </div>
      </section>

      <section class="card">
        <h2>Projekte</h2>
        <ul>
          <li><b>Projekt A</b> – Kurzbeschreibung (React, Node, MySQL) – <a href="https://github.com/<user>/<repo-a>">Repo</a></li>
          <li><b>Projekt B</b> – Kurzbeschreibung (Vue, Python) – <a href="https://github.com/<user>/<repo-b>">Repo</a></li>
          <li><b>Projekt C</b> – Kurzbeschreibung (.NET, Lua) – <a href="https://github.com/<user>/<repo-c>">Repo</a></li>
        </ul>
      </section>

      <section class="card">
        <h2>Kontakt</h2>
        <p>📧 <a href="mailto:you@example.com">you@example.com</a><br>
           💼 <a href="https://www.linkedin.com/in/your-profile">LinkedIn</a><br>
           🌐 <a href="https://your-website.tld">Website/Portfolio</a></p>
      </section>
    </div>

    <footer>© <YOUR_NAME> — Open for collaborations.</footer>
  </div>
</body>
</html>
