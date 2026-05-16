---
title: Nautitools – Apps für Segler
description: Praktische Apps für Segler und Motorbootfahrer
layout: default
---

<style>
  * { box-sizing: border-box; margin: 0; padding: 0; }

  body {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
    background: #f0f4f8;
    color: #1a202c;
    min-height: 100vh;
    display: flex;
    flex-direction: column;
  }

  header {
    background: linear-gradient(135deg, #1a365d 0%, #2b6cb0 100%);
    color: white;
    padding: 3rem 1.5rem 4rem;
    text-align: center;
  }

  header .logo {
    font-size: 2.5rem;
    font-weight: 700;
    letter-spacing: -0.5px;
    margin-bottom: 0.5rem;
  }

  header .logo span {
    color: #90cdf4;
  }

  header p {
    font-size: 1.1rem;
    opacity: 0.85;
    max-width: 480px;
    margin: 0 auto;
  }

  main {
    max-width: 860px;
    margin: -2rem auto 3rem;
    padding: 0 1.25rem;
    flex: 1;
  }

  .section-title {
    font-size: 0.75rem;
    font-weight: 600;
    text-transform: uppercase;
    letter-spacing: 0.1em;
    color: #718096;
    margin-bottom: 1rem;
  }

  .card {
    background: white;
    border-radius: 16px;
    box-shadow: 0 4px 20px rgba(0,0,0,0.08);
    padding: 2rem;
    margin-bottom: 1.5rem;
  }

  .app-header {
    display: flex;
    align-items: center;
    gap: 1.25rem;
    margin-bottom: 1.25rem;
  }

  .app-icon {
    width: 72px;
    height: 72px;
    border-radius: 16px;
    background: linear-gradient(135deg, #2b6cb0, #63b3ed);
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 2rem;
    flex-shrink: 0;
  }

  .app-name {
    font-size: 1.4rem;
    font-weight: 700;
    color: #1a365d;
    margin-bottom: 0.2rem;
  }

  .app-tagline {
    font-size: 0.9rem;
    color: #718096;
  }

  .app-description {
    font-size: 0.95rem;
    line-height: 1.7;
    color: #4a5568;
    margin-bottom: 1.5rem;
  }

  .features {
    list-style: none;
    margin-bottom: 1.75rem;
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 0.5rem;
  }

  .features li {
    font-size: 0.875rem;
    color: #4a5568;
    display: flex;
    align-items: center;
    gap: 0.5rem;
  }

  .features li::before {
    content: "✓";
    color: #3182ce;
    font-weight: 700;
    font-size: 0.8rem;
  }

  .store-badges {
    display: flex;
    gap: 1rem;
    flex-wrap: wrap;
    align-items: center;
  }

  .store-badge {
    display: inline-flex;
    align-items: center;
    gap: 0.6rem;
    background: #1a202c;
    color: white;
    border-radius: 10px;
    padding: 0.55rem 1.1rem;
    text-decoration: none;
    font-size: 0.8rem;
    transition: background 0.15s;
    opacity: 0.45;
    cursor: default;
    pointer-events: none;
  }

  .store-badge .store-icon {
    font-size: 1.4rem;
    line-height: 1;
  }

  .store-badge .store-text {
    display: flex;
    flex-direction: column;
    line-height: 1.2;
  }

  .store-badge .store-label {
    font-size: 0.65rem;
    opacity: 0.8;
    text-transform: uppercase;
    letter-spacing: 0.04em;
  }

  .store-badge .store-name {
    font-size: 0.9rem;
    font-weight: 600;
  }

  .store-badge.coming-soon::after {
    content: "bald verfügbar";
    font-size: 0.65rem;
    background: #e2e8f0;
    color: #4a5568;
    border-radius: 4px;
    padding: 0.15rem 0.4rem;
  }

  footer {
    text-align: center;
    padding: 2rem 1.25rem;
    font-size: 0.85rem;
    color: #718096;
    border-top: 1px solid #e2e8f0;
    background: white;
  }

  footer a {
    color: #4a5568;
    text-decoration: none;
    margin: 0 0.75rem;
  }

  footer a:hover {
    color: #2b6cb0;
    text-decoration: underline;
  }

  footer .separator {
    margin: 0 0.25rem;
    color: #cbd5e0;
  }

  @media (max-width: 520px) {
    .features { grid-template-columns: 1fr; }
    .app-header { flex-direction: column; align-items: flex-start; }
    header .logo { font-size: 2rem; }
  }
</style>

<header>
  <div class="logo">⚓ Nauti<span>tools</span></div>
  <p>Praktische Apps für Segler und Motorbootfahrer</p>
</header>

<main>
  <p class="section-title">Unsere Apps</p>

  <div class="card">
    <div class="app-header">
      <div class="app-icon">⚓</div>
      <div>
        <div class="app-name">Ankerkettenrechner</div>
        <div class="app-tagline">Die richtige Kettenlänge. Immer.</div>
      </div>
    </div>

    <p class="app-description">
      Der Ankerkettenrechner hilft dir, die optimale Kettenlänge beim Ankern schnell und zuverlässig zu bestimmen.
      Gib einfach die aktuelle Wassertiefe und den Freibord deines Bootes ein – die App berechnet automatisch
      die empfohlene Ankerkettenlänge anhand gängiger Seemannschaft-Formeln. So liegst du sicher und entspannt
      vor Anker, egal ob in einer geschützten Bucht oder bei auffrischendem Wind.
    </p>

    <ul class="features">
      <li>Wassertiefe &amp; Freibord eingeben</li>
      <li>Empfohlene Kettenlänge sofort</li>
      <li>Verschiedene Sicherheitsfaktoren</li>
      <li>Offline nutzbar, kein Login</li>
    </ul>

    <div class="store-badges">
      <a class="store-badge coming-soon" href="#">
        <span class="store-icon">🍎</span>
        <span class="store-text">
          <span class="store-label">Laden im</span>
          <span class="store-name">App Store</span>
        </span>
      </a>
      <a class="store-badge coming-soon" href="#">
        <span class="store-icon">▶</span>
        <span class="store-text">
          <span class="store-label">Jetzt bei</span>
          <span class="store-name">Google Play</span>
        </span>
      </a>
    </div>
  </div>
</main>

<footer>
  &copy; {{ site.time | date: "%Y" }} Lars Gentz
  <span class="separator">·</span>
  <a href="https://larsgentz.github.io/nautitools/impressum/">Impressum</a>
  <span class="separator">·</span>
  <a href="https://larsgentz.github.io/nautitools/datenschutz/">Datenschutz</a>
</footer>
