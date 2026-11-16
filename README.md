# OVL vzw – website

Statische site (HTML/CSS, geen build nodig) voor GitHub Pages.

## Publiceren
1. Maak op GitHub een (privé of openbare) repository, bv. `ovl-website`.
2. Upload de INHOUD van deze map (index.html, privacy.html, style.css, fonts/, assets/, favicon.svg, .nojekyll).
3. Repository → Settings → Pages → Source: "Deploy from a branch" → branch `main`, map `/ (root)`.
4. Eigen domein: Settings → Pages → Custom domain → `www.ovlvzw.be`; maak bij je DNS een CNAME `www` → `<gebruikersnaam>.github.io`. Vink daarna "Enforce HTTPS" aan.

## Aanpassen
- Teksten: index.html (secties staan in volgorde: over, historiek, bestuur, agenda, documenten, contact).
- Bestuur: blokken `<div class="card person">` in sectie #bestuur.
- Ledenmap-link: knop in sectie #documenten.
- Agenda: kalender-ID staat in het script onderaan index.html.
- Contactformulier: `ENDPOINT` onderaan index.html (Apps Script-URL; toegang "Iedereen").
