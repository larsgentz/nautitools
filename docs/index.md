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
    width: 80px;
    height: 80px;
    border-radius: 18px;
    flex-shrink: 0;
    box-shadow: 0 2px 8px rgba(0,0,0,0.15);
    object-fit: cover;
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
    gap: 0.75rem;
    flex-wrap: wrap;
    align-items: center;
  }

  .store-badge-wrap {
    display: inline-flex;
    flex-direction: column;
    align-items: center;
    gap: 0.4rem;
  }

  .store-badge-wrap a {
    display: block;
    opacity: 0.4;
    pointer-events: none;
    cursor: default;
  }

  .store-badge-wrap img {
    height: 44px;
    width: auto;
    display: block;
  }

  .store-badge-wrap .coming-soon-label {
    font-size: 0.65rem;
    color: #718096;
    background: #edf2f7;
    border-radius: 4px;
    padding: 0.15rem 0.5rem;
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
      <img class="app-icon" src="{{ '/assets/icon_chain_calculator.png' | relative_url }}" alt="Ankerkettenrechner Icon">
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
      <div class="store-badge-wrap">
        <a href="#">
          <img src="https://tools.applemediaservices.com/api/badges/download-on-the-app-store/black/de-de" alt="Im App Store laden">
        </a>
        <span class="coming-soon-label">bald verfügbar</span>
      </div>
      <div class="store-badge-wrap">
        <a href="#">
          <img src="https://play.google.com/intl/en_us/badges/static/images/badges/de_badge_web_generic.png" alt="Jetzt bei Google Play">
        </a>
        <span class="coming-soon-label">bald verfügbar</span>
      </div>
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
