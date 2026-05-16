---
title: Nautitools – Apps für Segler
description: Praktische Apps für Segler und Motorbootfahrer
layout: default
---

<p class="section-title">Meine Apps</p>

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

<div class="card">
  <div class="support-header">
    <div class="support-icon">✉️</div>
    <div>
      <div class="app-name">Support</div>
      <div class="app-tagline">Ich helfe gerne weiter</div>
    </div>
  </div>
  <p class="app-description">
    Fragen, Feedback oder Probleme mit einer meiner Apps? Schreib mir einfach eine E-Mail –
    ich melde mich bei dir. Bitte beachte, dass das Erstellen dieser Apps in meiner Freizeit passiert - danke für Deine Geduld.
  </p>
  <a class="support-link" id="support-email" href="#">E-Mail wird geladen…</a>
</div>

<script>
  (function () {
    var u = 'apps', d = 'larsgentz' + '.' + 'de';
    var el = document.getElementById('support-email');
    el.href = 'mai' + 'lto:' + u + '@' + d;
    el.textContent = u + '@' + d;
  })();
</script>
