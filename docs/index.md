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
    <div class="store-badge-wrap active">
      <a href="https://apps.apple.com/de/app/ankerketten-rechner/id6769848459" target="_blank" rel="noopener">
        <img src="https://tools.applemediaservices.com/api/badges/download-on-the-app-store/black/de-de" alt="Im App Store laden">
      </a>
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
  <div class="app-header">
    <img class="app-icon" src="{{ '/assets/icon_marine_vhf_assistant.png' | relative_url }}" alt="Marine VHF Assistant Icon">
    <div>
      <div class="app-name">Marine VHF Assistant</div>
      <div class="app-tagline">Seefunk sicher und verständlich vorbereiten.</div>
    </div>
  </div>

  <p class="app-description">
    Der Marine VHF Assistant unterstützt Segler und Motorbootfahrer beim Vorbereiten klarer Seefunk-Sprüche.
    Die App erstellt Notfall- und Dringlichkeitssprüche wie Mayday, Pan Pan, Mayday Relay und Securité,
    bindet Bootsdaten und GPS-Position ein und hilft auch im Bordalltag mit Routine-Sprüchen für Marina,
    Schleuse, Brücke und andere Kontakte.
  </p>

  <ul class="features">
    <li>Mayday, Pan Pan &amp; Securité</li>
    <li>GPS-Position automatisch einbinden</li>
    <li>NATO-Alphabet und Vorlesen</li>
    <li>Routine-Sprüche und Kontakte</li>
  </ul>

  <div class="store-badges">
    <div class="store-badge-wrap active">
      <a href="https://apps.apple.com/de/app/marine-vhf-assistant/id6772940401" target="_blank" rel="noopener">
        <img src="https://tools.applemediaservices.com/api/badges/download-on-the-app-store/black/de-de" alt="Im App Store laden">
      </a>
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
