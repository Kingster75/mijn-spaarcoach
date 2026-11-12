# Mijn Spaarcoach – Android PWA

## Wat zit erin?
- Installeren als webapp op Android via Chrome.
- CSV-import van meerdere banken (bank kiezen per bestand).
- Herkenning van veelvoorkomende kolomnamen voor datum, omschrijving en bedrag.
- Dubbele transacties zoveel mogelijk overslaan.
- Handmatige transacties, categorieën, spaardoel, maandtotalen.
- CSV-export en JSON-back-up/herstel.
- Gegevens worden lokaal in de browser opgeslagen.

## Android installeren
Een PWA moet via een beveiligde HTTPS-website worden geopend om installeerbaar en offline bruikbaar te zijn.
1. Upload de inhoud van deze map naar een HTTPS-hostingdienst (bijvoorbeeld GitHub Pages of Netlify).
2. Open de website in Chrome op je Android-telefoon.
3. Kies in het Chrome-menu **Installeren** of **Toevoegen aan startscherm**.

## CSV-import
Exporteer bij je bank een CSV-bestand met minimaal datum, omschrijving en bedrag. De app herkent veel voorkomende Nederlandse en Engelse kolomnamen. Bij bestanden met aparte af- en bij-kolommen probeert de app die te combineren. Kies bij elk bestand de juiste bank.
Controleer na iedere import de datums en bedragen. Bankexports verschillen en sommige exports kunnen extra instellingen of kolomkoppen hebben.

## Privacy en beperkingen
- Geen directe bankkoppeling; je importeert zelf de CSV-bestanden.
- Geen inloggegevens, pincodes of TAN-codes invoeren.
- Data wordt lokaal opgeslagen in de browser op het apparaat. Browsergegevens wissen kan de opgeslagen gegevens verwijderen; maak daarom back-ups.
- Dit is een eerste bruikbare versie/prototype, geen gecertificeerde financiële administratie.
