SUREBETS – MOBIELE UPDATE (2 november 2026)

Publiceren met GitHub Pages:
1. Maak in de oude Surebets-app EERST een JSON-back-up.
2. Pak dit ZIP-bestand uit en upload de inhoud (niet het ZIP-bestand) naar de ingestelde GitHub Pages map.
3. Vervang index.html, sw.js, manifest.webmanifest, icon-192.png en icon-512.png. Upload ook de volledige map assets.
4. Controleer GitHub Actions -> pages build and deployment. Open je website opnieuw in Safari. Bij oude cache: sluit de app volledig af en open de gepubliceerde site opnieuw.
5. Verwijder de oude app en websitegegevens niet voordat je de JSON-back-up en saldi hebt gecontroleerd.

Nieuwe functies:
- Oude rekentool terug: 2-way/3-way, freebets, eigen geld en afronding.
- Logo alleen linksboven; geen grote afbeelding op Dashboard.
- Mobiele kaartweergave van bets, snelle resultaatkeuze, vaste onderste navigatie.
- Donkere modus in Instellingen: automatisch/licht/donker.
- 2+3 is geen optie voor nieuwe bets; oude 2+3-bets blijven leesbaar en bewerkbaar.
- Verbeterde formulierfeedback, grotere invoervelden en kleurcontrast.
- Alle bookmakers blijven opgenomen in winstoverzicht.

Gegevens:
De app gebruikt dezelfde localStorage-sleutel (surebet-pwa-personal-v1) en hetzelfde JSON-back-upformaat als de vorige versie. Publiceer geen privé-JSON op GitHub.

Let op: op een NIEUWE GitHub Pages URL beginnen de lokaal opgeslagen gegevens leeg; gebruik Back-up herstellen om bestaande gegevens over te zetten. Zoom met twee vingers blijft uit toegankelijkheidsoverwegingen beschikbaar; automatisch iOS-invoerzoom wordt vermeden met 16px-velden. De in-app herinnering werkt niet betrouwbaar wanneer de app helemaal gesloten is.
