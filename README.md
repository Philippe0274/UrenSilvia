# Urenregistratie Kuisvrouw

Webapp voor het bijhouden van werkuren, verlof en kostprijs van een kuisvrouw.
Alle gegevens worden lokaal in de browser bewaard (localStorage).

## Installeren op GitHub Pages

1. Maak een GitHub-repository en upload **alle bestanden uit deze map** in de root:
   - `index.html`
   - `manifest.json`
   - `icon.png`
   - `icon-192.png`
   - `icon-512.png`
   - `icon-180.png`

2. Ga in de repo naar **Settings → Pages**

3. Bij *Source*, kies branch **main** en folder **/ (root)**, en klik Save

4. Na een paar minuten is de site bereikbaar op
   `https://<jouw-gebruikersnaam>.github.io/<repo-naam>/`

## Op homescreen zetten (zodat het icoon verschijnt)

**iPhone (Safari):**
- Open de site in Safari
- Tik op het deel-icoon onderaan
- Kies "Zet op beginscherm"
- Het icoon verschijnt op je homescreen

**Android (Chrome):**
- Open de site in Chrome
- Tik op de drie puntjes rechtsboven
- Kies "Toevoegen aan startscherm" of "App installeren"
- Het icoon verschijnt op je homescreen

De app opent dan in volledig scherm, zonder browserbalk.

## Gebruik

- **Default werkdag:** 09:00 – 14:00 (= 5 uur)
- Vul per dag aankomst- en vertrekuur in
- Bij minder dan 5 uur verschijnt een rode waarschuwing
- Kostprijs wordt automatisch berekend aan €12/uur
- Gegevens blijven bewaard bij het wisselen tussen maanden/jaren
- Export naar CSV (Excel-compatibel met BOM, puntkomma-gescheiden)
