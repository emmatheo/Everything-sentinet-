# Sentient Spark — Learn

**SentientAGI — The World's Largest Network of Intelligence.**  
Lightweight landing page and starter README for the Sentient Spark / SentientAGI learning hub. Live demo: https://sentient-spark-learn.lovable.app/ :contentReference[oaicite:1]{index=1}

---

## About

This repository hosts a simple landing page and starter content for **Sentient Spark — Learn**, a SentientAGI learning hub / landing experience. The original site appears to be a modern single-page JS site (served as a minimal HTML shell). Use this repo as a clean, versioned GitHub source for the project.

> Note: The live site is a JS-heavy landing page. This repo contains a static fallback markup and README for GitHub pages or as project documentation. :contentReference[oaicite:2]{index=2}

---

## Features

- Simple, responsive hero section with headline, sub-headline and CTAs.
- Quick-start HTML file (index.html) you can host on GitHub Pages.
- Placeholder areas for screenshots, resources, and roadmap.
- Contribution instructions and license.

---

## Quick start (deploy to GitHub Pages)

1. Clone this repo:
   ```bash
   git clone <your-repo-url>
   cd <your-repo-name>
   /
├─ index.html
├─ README.md
├─ assets/
│  ├─ logo.png
│  └─ hero.jpg
├─ docs/
│  └─ guide.md
└─ LICENSE
---

# index.html (Simple static markup)
Drop this `index.html` in your repo root (or use as GitHub Pages entry point). Update links, images, and copy as needed.

```html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Sentient Spark — Learn</title>
  <meta name="description" content="SentientAGI — The World's Largest Network of Intelligence." />
  <style>
    /* Minimal, clean styles - change to Tailwind or your framework as desired */
    :root{--bg:#0f1724;--card:#0b1220;--accent:#7c3aed;--muted:#9aa4b2}
    body{margin:0;font-family:Inter,system-ui,Segoe UI,Roboto,'Helvetica Neue',Arial;background:linear-gradient(180deg,#071022 0%, #071a2b 100%);color:#fff;line-height:1.5}
    .container{max-width:1000px;margin:48px auto;padding:24px}
    header{display:flex;align-items:center;justify-content:space-between}
    .logo{display:flex;gap:12px;align-items:center}
    .logo img{height:42px}
    .hero{display:grid;grid-template-columns:1fr 420px;gap:32px;align-items:center;margin-top:36px}
    h1{font-size:2.1rem;margin:0 0 8px}
    p.lead{color:var(--muted);margin:0 0 20px}
    .cta{display:flex;gap:12px}
    .btn{padding:12px 18px;border-radius:10px;text-decoration:none;font-weight:600}
    .btn-primary{background:linear-gradient(90deg,var(--accent),#5b21b6);color:#fff;box-shadow:0 6px 20px rgba(124,58,237,0.18)}
    .btn-ghost{border:1px solid rgba(255,255,255,0.08);color:#fff;background:transparent}
    .card{background:rgba(255,255,255,0.02);padding:18px;border-radius:14px;box-shadow:0 6px 18px rgba(2,6,23,0.6)}
    footer{margin-top:46px;color:var(--muted);font-size:0.9rem;text-align:center}
    @media (max-width:900px){.hero{grid-template-columns:1fr;}.logo img{height:36px}}
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="logo">
        <img src="assets/logo.png" alt="Sentient Spark logo" />
        <div>
          <strong>Sentient Spark</strong><br/>
          <small style="color:var(--muted)">SentientAGI — The World's Largest Network of Intelligence</small>
        </div>
      </div>
      <nav>
        <a class="btn btn-ghost" href="#learn">Learn</a>
        <a class="btn btn-ghost" href="#docs">Docs</a>
      </nav>
    </header>

    <main class="hero">
      <section>
        <h1>Learn. Build. Connect with Sentient Intelligence</h1>
        <p class="lead">A concise learning hub and sandbox for building on SentientAGI. Explore guides, tutorials and community resources.</p>

        <div class="cta">
          <a class="btn btn-primary" href="#get-started">Get Started</a>
          <a class="btn btn-ghost" href="https://sentient-spark-learn.lovable.app/" target="_blank" rel="noopener">Open Live Site</a>
        </div>

        <div style="margin-top:24px" class="card">
          <h3 style="margin:0 0 6px">Quick links</h3>
          <ul style="margin:10px 0 0;padding-left:18px;color:var(--muted)">
            <li><a href="#docs">Documentation</a></li>
            <li><a href="#examples">Starter examples</a></li>
            <li><a href="#contributing">Contribute</a></li>
          </ul>
        </div>
      </section>

      <aside class="card">
        <h3 style="margin-top:0">Preview</h3>
        <p style="color:var(--muted)">Add a screenshot named <code>assets/hero.jpg</code> to display the hero preview here.</p>
        <div style="height:220px;border-radius:10px;background:linear-gradient(180deg,rgba(255,255,255,0.02),transparent);display:flex;align-items:center;justify-content:center;color:var(--muted)">Hero screenshot placeholder</div>
      </aside>
    </main>

    <section id="get-started" style="margin-top:40px" class="card">
      <h2>Get started</h2>
      <ol>
        <li>Clone the repo and add assets in <code>/assets</code>.</li>
        <li>Edit copy and CTA links in <code>index.html</code>.</li>
        <li>Deploy via GitHub Pages or any static host.</li>
      </ol>
    </section>

    <footer>
      <div>Original live site: <a href="https://sentient-spark-learn.lovable.app/" target="_blank" rel="noopener">sentient-spark-learn.lovable.app</a>. Note: live site appears to be JS-driven; this static page is a fallback / GitHub presentation. :contentReference[oaicite:4]{index=4}</div>
      <div style="margin-top:8px">MIT · Built for SentientAGI presentation</div>
    </footer>
  </div>
</body>
</html>

