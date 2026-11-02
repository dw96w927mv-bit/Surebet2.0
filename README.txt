SUREBETS WEBAPP - OKTOBER 2026 (V4)

1. Maak eerst een JSON-back-up in de huidige app via Back-up.
2. Pak dit ZIP-bestand uit.
3. Vervang op GitHub Pages de bestanden index.html, sw.js, manifest.webmanifest, icon-192.png, icon-512.png en de map assets/ met de nieuwe bestanden. Upload geen persoonlijke JSON.
4. Controleer Actions -> Pages build/deployment, en open daarna de gepubliceerde website.
5. Vernieuw Safari als de oude versie nog in de cache staat. De serviceworker-cache heet surebets-v4.

Nieuw:
- Alleen in Bets kun je een nieuwe bet starten; invoer via stappenplan met minimumwinstcontrole.
- Instellingen voor standaardfilter/-sortering, optionele dagelijkse herinnering voor open verlopen bets, cumulatieve winst-/verliesgrenzen per bookmaker.
- Dashboard met alle bookmakers en zonder recente-bets-lijst.
- Casino vervangen door Bijzondere mutaties, inclusief externe servicekosten.
- Behoud van de bestaande JSON-import/back-up en berekeningen; nieuwe settings worden mee geëxporteerd.

BELANGRIJK: Dagelijkse melding verschijnt in de app wanneer die wordt geopend/actief is. Zonder een push-backend kan een volledig gesloten iPhone-app niet gegarandeerd om een bepaald tijdstip een melding versturen. Alleen bets met einddatum/tijd kunnen als verlopen worden gedetecteerd.
