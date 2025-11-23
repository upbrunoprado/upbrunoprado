<!doctype html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Bruno Prado — Perfil</title>
  <style>
    :root{--bg:#0f1724;--card:#0b1220;--muted:#94a3b8;--accent:#7c3aed;--glass:rgba(255,255,255,0.04)}
    *{box-sizing:border-box}
    body{margin:0;font-family:Inter, ui-sans-serif, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;color:#e6eef8;background:linear-gradient(180deg,#071025 0%, #071326 60%);-webkit-font-smoothing:antialiased}
    .wrap{max-width:920px;margin:36px auto;padding:28px;border-radius:16px;background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));box-shadow:0 10px 30px rgba(2,6,23,0.6);backdrop-filter:blur(6px)}
    header{display:flex;gap:20px;align-items:center}
    .avatar{width:96px;height:96px;border-radius:14px;background:linear-gradient(135deg,var(--accent),#0ea5a4);display:flex;align-items:center;justify-content:center;color:white;font-weight:700;font-size:34px}
    h1{margin:0;font-size:22px}
    p.lead{margin:6px 0 0;color:var(--muted)}
    .grid{display:grid;grid-template-columns:1fr 320px;gap:20px;margin-top:22px}
    .card{background:var(--card);padding:18px;border-radius:12px;border:1px solid rgba(255,255,255,0.02)}
    .bio{line-height:1.6;color:#d7e7fb}
    .badges{display:flex;flex-wrap:wrap;gap:8px;margin-top:12px}
    .badge{padding:6px 10px;border-radius:999px;background:var(--glass);color:var(--muted);font-size:13px;border:1px solid rgba(255,255,255,0.02)}
    .section-title{font-weight:700;margin:0 0 10px;color:#cfe6ff}
    .project{margin-bottom:12px}
    a.link{color:var(--accent);text-decoration:none}
    .stats{display:flex;gap:10px;flex-wrap:wrap;margin-top:12px}
    .stat{background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));padding:8px 12px;border-radius:10px;font-size:13px;color:var(--muted);border:1px solid rgba(255,255,255,0.02)}
    footer{margin-top:18px;color:var(--muted);font-size:13px}
    /* mobile */
    @media (max-width:880px){.grid{grid-template-columns:1fr;}.avatar{width:86px;height:86px}}
  </style>
</head>
<body>
  <div class="wrap">
    <header>
      <div class="avatar">BP</div>
      <div>
        <h1>Bruno Prado <span style="color:var(--muted);font-weight:600;font-size:14px">— Desenvolvimento, EdTech & Maker</span></h1>
        <p class="lead">Desenvolvedor full‑stack e educador técnico: Flutter Web, Python, Supabase, FastAPI, robótica e cultura maker.</p>
      </div>
    </header>

    <div class="grid">
      <main class="card">
        <h2 class="section-title">Sobre</h2>
        <p class="bio">Crio plataformas e soluções para empreendedores e para a educação. Tenho experiência em desenvolvimento web com Flutter Web, backend em Python (incluindo FastAPI), e integrações com Supabase. Trabalho com design de produtos educacionais, robótica e cultura maker, sempre buscando aplicar tecnologia de forma prática para escolas e professores.</p>

        <div style="margin-top:14px">
          <h3 class="section-title">Projetos em destaque</h3>
          <div class="project">
            <strong>AcordarCedo — acordarcedo.com</strong>
            <p style="margin:6px 0;color:var(--muted)">Plataforma hub de soluções para empreendedores e também soluções para a área da educação. Integra ferramentas, cursos práticos e conteúdos que ajudam a transformar ideias em projetos reais.</p>
            <p><a class="link" href="https://acordarcedo.com" target="_blank">acordarcedo.com</a></p>
          </div>

          <div style="margin-top:10px">
            <h3 class="section-title">O que eu faço</h3>
            <ul style="margin:6px 0 0 18px;color:var(--muted);line-height:1.7">
              <li>Plataformas web com Flutter Web + Supabase</li>
              <li>APIs e microserviços em Python / FastAPI</li>
              <li>Design e material didático técnico para escolas e professores</li>
              <li>Projetos de robótica, automação e cultura maker</li>
              <li>Integração de IA para relatórios e funcionalidades educacionais</li>
            </ul>
          </div>

          <div style="margin-top:12px">
            <h3 class="section-title">Skills</h3>
            <div class="badges">
              <span class="badge">Flutter Web</span>
              <span class="badge">Dart</span>
              <span class="badge">Python</span>
              <span class="badge">FastAPI</span>
              <span class="badge">Supabase</span>
              <span class="badge">SQL</span>
              <span class="badge">HTML</span>
              <span class="badge">CSS</span>
              <span class="badge">JavaScript</span>
              <span class="badge">Robótica</span>
              <span class="badge">Cultura maker</span>
              <span class="badge">Educação digital</span>
              <span class="badge">Material didático técnico</span>
              <span class="badge">IA aplicada</span>
            </div>
          </div>

        </div>
      </main>

      <aside>
        <div class="card">
          <h3 class="section-title">Contatos</h3>
          <p style="margin:6px 0;color:var(--muted)">GitHub: <a class="link" href="https://github.com/brunoprado" target="_blank">@brunoprado</a></p>
          <p style="margin:6px 0;color:var(--muted)">Site / Hub: <a class="link" href="https://acordarcedo.com" target="_blank">acordarcedo.com</a></p>
          <p style="margin:6px 0;color:var(--muted)">Email: <span style="color:#9fbef7">seu-email@exemplo.com</span></p>

          <div style="margin-top:12px">
            <h4 class="section-title">Mini stats</h4>
            <div class="stats">
              <div class="stat">Plataformas: Flutter Web</div>
              <div class="stat">Back-end: Python / FastAPI</div>
              <div class="stat">Banco: Supabase / Postgres</div>
            </div>
          </div>

          <div style="margin-top:12px">
            <h4 class="section-title">Disponível para</h4>
            <div class="badges">
              <span class="badge">Consultoria</span>
              <span class="badge">Desenvolvimento</span>
              <span class="badge">Cursos & Formação</span>
            </div>
          </div>
        </div>

        <div style="margin-top:12px" class="card">
          <h4 class="section-title">Notas</h4>
          <p style="margin:6px 0;color:var(--muted)">Se quiser, adapto este HTML para o formato README.md do GitHub ou para uma página estática pronta para hospedagem (GitHub Pages).</p>
        </div>
      </aside>
    </div>

    <footer>
      Feito com ♥ — Bruno Prado
    </footer>
  </div>
</body>
</html>
