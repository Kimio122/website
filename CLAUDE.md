# Kims Website – Projektübersicht

Sprich mit mir (Kim) auf Deutsch, einfach und Schritt für Schritt. Ich habe noch nie programmiert.

## Über mich (nur diese Fakten verwenden – nichts dazuerfinden!)
- Kim, 31, aus Bergkamen (NRW). Instagram & TikTok: @kimvibesnow
- Komme aus der Pflege, habe im **ambulanten Pflegedienst** gearbeitet (KEINE Ausbildung erwähnen)
- Will keinen 9-to-5, nicht von einem Arbeitgeber abhängig sein, fertig mit dem System in der Pflege
- Seit Oktober 2026 selbstständig als UGC Creatorin (Beauty, Lifestyle, Fitness); erste Kooperation steht
- Mache den Kurs **„From Chaos to System“** (FCTS) und zusätzlich das 1:1-Mentoring **„Unleashed“** von Nathalie Lück – das sind ZWEI verschiedene Angebote, bei beiden bin ich selbst dabei
- Routine: jeden Morgen Zitronenwasser, 10.000 Schritte mit meinem Hund Louie, Sport, täglich mind. 30 Min. lesen
- Harry-Potter-Fan (damit hat mein Content angefangen), liebe Mode, Content immer ohne Filter

## Ziel
Statische HTML-Website, gehostet bei **Netlify**, mit **eigener Domain**. Link kommt in die Insta- und TikTok-Bio.

## Dateien
- `index.html` – Startseite: Über mich (ganz oben, lang) → „Ein bisschen mehr von mir“ (Louie, Bücher, Harry Potter, Mode + 3 Fotos) → Empfehlungen („Das nutze ich selbst“: FCTS + Unleashed) → Für Marken (Portfolio + Mail) → Footer
- `impressum.html`, `datenschutz.html`
- `style.css` – alle Farben/Schriften
- `images/` – kim.jpg, louie.jpg, alltag.jpg, drehen.jpg (noch Platzhalter)
- `fonts/` – fraunces.ttf, fraunces-italic.ttf, dmsans.ttf (müssen noch rein, siehe ANLEITUNG.txt)

## Design
- Farben: Petrol #1F4E5A (Haupt), Terrakotta #E07A5F (Akzent), Creme #FAF6F1 (Hintergrund)
- Schriften: Fraunces (Überschriften), DM Sans (Text) – **selbst gehostet**, NICHT von Google laden (Datenschutz)
- Keine Cookies, kein Tracking, keine externen Einbindungen

## Entscheidungen
- Über mich steht zuerst, Empfehlungen danach
- Texte bei FCTS und Unleashed kurz halten (je ein Satz)
- Keine leere „Bald hier“-Karte; Rabattcodes (z. B. Cabaïa) kommen NICHT auf die Website, sondern in die Insta-Bio/Story-Highlights, weil sie zeitlich begrenzt sind
- Affiliate-Links mit * kennzeichnen + Hinweis darunter
- Portfolio-Button bei „Für Marken“ (Portfolio wird separat erstellt)

## Noch offen (nach „ERSETZEN“ suchen)
1. Schriften in `fonts/` legen
2. Fotos in `images/` austauschen (gleiche Dateinamen)
3. Links: FCTS-Affiliate-Link, Unleashed-Link, Portfolio-Link, E-Mail
4. Impressum: Name, Adresse (Straße), Telefon; USt-ID-Abschnitt löschen, falls keine vorhanden
5. Datenschutzerklärung mit Generator (z. B. eRecht24) erstellen – Hosting Netlify, E-Mail-Kontakt, Links zu Social Media/Affiliate
6. Bei Netlify hochladen und eigene Domain verbinden
