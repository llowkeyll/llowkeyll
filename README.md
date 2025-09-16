<!--
  GitHub README - HTML template
  Copy the HTML below into your README.md on GitHub. GitHub will render HTML inside markdown files.
  Replace placeholders: YOUR_NAME, SHORT_BIO, TECH STACK, PROJECT links, and social links.
  Do not forget to update the badges URLs with your GitHub username and project names.
-->

<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width,initial-scale=1">
    <title>README</title>
    <style>
      :root{
        --bg:#0f1724;
        --card:#0b1220;
        --muted:#9aa4b2;
        --accent:#00bcd4;
        --glass: rgba(255,255,255,0.03);
        --radius:14px;
        font-family: Inter, ui-sans-serif, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
      }
      body{background:var(--bg);color:#e6eef6;margin:0;padding:24px}
      .container{max-width:900px;margin:0 auto;padding:28px;background:linear-gradient(180deg, rgba(255,255,255,0.02), transparent);border-radius:18px;box-shadow:0 8px 30px rgba(2,6,23,0.75);}
      .header{display:flex;gap:18px;align-items:center}
      .avatar{width:104px;height:104px;border-radius:16px;overflow:hidden;flex:0 0 104px;border:1px solid rgba(255,255,255,0.04);}
      .avatar img{width:100%;height:100%;object-fit:cover;display:block}
      .title h1{margin:0;font-size:28px;letter-spacing:-0.4px}
      .subtitle{color:var(--muted);margin-top:6px}
      .badges{margin-top:10px;display:flex;flex-wrap:wrap;gap:8px}

      .grid{display:grid;grid-template-columns:1fr 280px;gap:20px;margin-top:22px}
      .card{background:var(--card);padding:16px;border-radius:12px;border:1px solid var(--glass)}
      .card h3{margin:0 0 10px 0}
      .bio{color:var(--muted);line-height:1.5}

      .tech-list{display:flex;flex-wrap:wrap;gap:10px}
      .tech{padding:8px 10px;border-radius:10px;background:rgba(255,255,255,0.02);color:var(--muted);font-weight:600;font-size:13px}

      .projects{display:flex;flex-direction:column;gap:12px}
      .project{display:flex;flex-direction:column;padding:12px;border-radius:10px;background:linear-gradient(180deg, rgba(255,255,255,0.012), transparent)}
      .project a{color:var(--accent);text-decoration:none;font-weight:700}
      .meta{color:var(--muted);font-size:13px;margin-top:8px}

      .right-col .section{margin-bottom:12px}
      .stats img{width:100%;border-radius:10px}

      .contact{display:flex;flex-wrap:wrap;gap:8px}
      .pill{background:rgba(255,255,255,0.02);padding:8px 10px;border-radius:999px;color:var(--muted);font-weight:600}

      footer{margin-top:18px;color:var(--muted);font-size:13px}

      @media (max-width:880px){
        .grid{grid-template-columns:1fr;}
        .right-col{order:2}
      }
    </style>
  </head>
  <body>
    <div class="container">
      <header class="header">
        <div class="avatar">
          <!-- Replace src with your avatar or remove the img tag to show no avatar -->
          <img src="https://avatars.githubusercontent.com/u/YOUR_GITHUB_ID?s=400&v=4" alt="avatar">
        </div>
        <div class="title">
          <h1>YOUR_NAME</h1>
          <div class="subtitle">Software developer - focused on full-stack web, tools, automation, and game server tooling</div>
          <div class="badges">
            <!-- Example shields - replace USERNAME / repo where needed -->
            <img src="https://img.shields.io/badge/GitHub-Profile-181717?logo=github" alt="github badge">
            <img src="https://img.shields.io/badge/TopLangs-Web%20Dev-blueviolet" alt="top langs">
            <img src="https://img.shields.io/badge/Status-Open%20to%20collab-blue" alt="status badge">
          </div>
        </div>
      </header>

      <div class="grid">
        <main>
          <section class="card">
            <h3>About me</h3>
            <p class="bio">SHORT_BIO. I build reliable tooling, polished web apps, and server-side automations. I like clean code, practical UX, and shipping things that scale. Currently exploring game modding tools and Discord automations.</p>
          </section>

          <section class="card" style="margin-top:14px">
            <h3>Featured projects</h3>
            <div class="projects">
              <div class="project">
                <div style="display:flex;justify-content:space-between;align-items:center">
                  <div>
                    <a href="https://github.com/YOUR_USERNAME/PROJECT_ONE">PROJECT_ONE</a>
                    <div class="meta">Short one-line summary of the project; tech used: Node.js, Express, PostgreSQL.</div>
                  </div>
                </div>
              </div>

              <div class="project">
                <div style="display:flex;justify-content:space-between;align-items:center">
                  <div>
                    <a href="https://github.com/YOUR_USERNAME/PROJECT_TWO">PROJECT_TWO</a>
                    <div class="meta">Short one-line summary; tech used: React, Tailwind, Vite.</div>
                  </div>
                </div>
              </div>

              <div class="project">
                <div>
                  <a href="https://github.com/YOUR_USERNAME/PROJECT_THREE">PROJECT_THREE</a>
                  <div class="meta">Short one-line summary; tech used: FiveM, Lua, server scripting.</div>
                </div>
              </div>
            </div>
          </section>

          <section class="card" style="margin-top:14px">
            <h3>What I work on</h3>
            <div style="margin-top:10px" class="tech-list">
              <span class="tech">Full-stack web apps</span>
              <span class="tech">REST APIs and microservices</span>
              <span class="tech">Discord bots and automation</span>
              <span class="tech">FiveM server scripts</span>
              <span class="tech">Chrome extensions and tools</span>
              <span class="tech">DevOps - CI/CD and Docker</span>
              <span class="tech">Game mod tooling and RP systems</span>
            </div>
          </section>

          <section class="card" style="margin-top:14px">
            <h3>Open to</h3>
            <p class="bio">Freelance contracts, collaboration on long-term projects, and contributions to open source. If you have a project that needs production-ready engineering, let me know.</p>
          </section>
        </main>

        <aside class="right-col">
          <div class="card section">
            <h3>Skills</h3>
            <div style="margin-top:10px">
              <div class="tech-list">
                <span class="tech">JavaScript</span>
                <span class="tech">TypeScript</span>
                <span class="tech">Node.js</span>
                <span class="tech">Discord.js</span>
                <span class="tech">React</span>
                <span class="tech">Tailwind</span>
                <span class="tech">Lua</span>
                <span class="tech">SQL</span>
                <span class="tech">Docker</span>
              </div>
            </div>
          </div>

          <div class="card section stats">
            <h3>GitHub stats</h3>
            <!-- Replace USERNAME in the image URLs below -->
            <img src="https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=radical" alt="stats">
            <div style="height:10px"></div>
            <img src="https://github-readme-streak-stats.herokuapp.com/?user=YOUR_USERNAME&theme=radical" alt="streak">
          </div>

          <div class="card section">
            <h3>Contact</h3>
            <div class="contact" style="margin-top:10px">
              <a class="pill" href="mailto:youremail@example.com">Email</a>
              <a class="pill" href="https://twitter.com/YOUR_HANDLE">Twitter</a>
              <a class="pill" href="https://www.linkedin.com/in/YOUR_LINKEDIN">LinkedIn</a>
              <a class="pill" href="https://github.com/YOUR_USERNAME">GitHub</a>
            </div>
          </div>

        </aside>
      </div>

      <footer>
        Pro tip: edit the top of this file and replace placeholders to make the README your own. Use badges from shields.io and the GitHub Readme Stats service to show dynamic info.
      </footer>
    </div>
  </body>
</html>
