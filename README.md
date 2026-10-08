# DaheimSmart

**Smarte Technik. Einfach erklärt.**

DaheimSmart ist eine unabhängige, verständlich aufgebaute Plattform rund um Smart-Home-Technik, Energie, Sicherheit und Komfort.

Das Ziel: Menschen sollen technische Lösungen besser verstehen und fundierte Entscheidungen treffen können – **ohne Technik-Hype und ohne unnötige Kaufempfehlungen**.

## Unser Prinzip

**Messen statt raten.**

Die zentrale Vorgehensweise von DaheimSmart:

**Problem → Ziel → Lösung → Technologie → Daten → Kriterien → Vergleich → Entscheidung**

Erst wird das konkrete Problem verstanden. Danach wird erklärt, welche Lösung sinnvoll sein kann. Erst am Ende kommen konkrete Produkte oder Kaufmöglichkeiten ins Spiel.

## Was DaheimSmart aktuell bietet

- ⚡ **Energie:** Verbrauch und Stromkosten verständlich betrachten
- 🔐 **Sicherheit:** Sensoren, Benachrichtigungen und praktische Lösungen
- 🏠 **Komfort:** Automationen und Smart-Home-Lösungen für den Alltag
- 💶 **Kosten:** Anschaffung, Verbrauch und Nutzen gemeinsam betrachten
- 🔎 **Vergleiche:** technische Unterschiede anhand nachvollziehbarer Kriterien
- 📚 **Ratgeber:** zentral nach Themen organisiert
- 🧭 **Werkzeuge:** zentraler Einstieg zu Rechnern und Energievergleich
- 🧮 **Stromkosten-Rechner:** interaktive Berechnung direkt im Browser
- 📊 **Produktvergleich:** interaktiver Vergleich verschiedener Geräte

## Aktueller Projektstand

DaheimSmart befindet sich aktuell in der Phase eines **funktionalen statischen Web-Prototyps mit zentraler Inhaltsarchitektur (2.8)**.

Die technische Basis steht und die wichtigsten Inhalte und Werkzeuge sind bereits integriert.

Aktuell vorhanden:

- responsive Startseite
- DaheimSmart-Hero-Bild
- Bereiche für Energie, Sicherheit, Komfort und Kosten
- Lösungswege vom Problem zur passenden Technologie
- Erklärungen zu Smart-Home-Technologien
- Kriterien für die Geräteauswahl
- Ratgeberartikel
- interaktiver Stromkosten-Rechner
- interaktiver Produktvergleich
- realer Produktvergleich mit Herstellerangaben
- Impressum
- Datenschutzerklärung
- barrierearmer „Zum Inhalt springen“-Link
- automatische Veröffentlichung über GitHub Actions

## Technischer Aufbau

DaheimSmart ist derzeit eine schlanke statische Website auf Basis von HTML, CSS und JavaScript.

```text
DaheimSmart/
├── index.html
├── ratgeber.html
├── werkzeuge.html
├── vergleiche.html
├── hub.css
├── ratgeber-stromverbrauch.html
├── ratgeber-matter.html
├── ratgeber-intelligente-steckdose.html
├── ratgeber.css
├── impressum.html
├── datenschutz.html
├── daheimsmart-house-hero.png
├── README.md
├── robots.txt
├── sitemap.xml
└── .github/
    └── workflows/
        └── static.yml
