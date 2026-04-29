# Mijn Eigen Plan — Demo voor De Schaapskooi Stellendam (v2)

Een werkende voorbeeldversie van een digitaal dagprogramma voor mensen met een lichte tot matige verstandelijke beperking. Gemaakt als onderbouwing voor een schoolopdracht over zorgtechnologie aan het Hoornbeeck College.

## Wat kan deze demo?

### Voor de bewoner
- **Persoonlijk dagscherm** met grote pictogrammen
- **Analoge klokken** bij elke taak (geen digitale tijd, want bewoners kunnen wel een analoge klok lezen)
- **Kleurcodering**: groen = klaar, oranje = nu bezig, grijs = komt nog, rood = gemist
- **Sclera-stijl pictogrammen**: 23 verschillende picto's (wit op zwart, sober en duidelijk)
- **Stappenplan per taak** dat los aangevinkt kan worden
- **Aftelklok** bij de taak die nu bezig is
- **Voorleesfunctie** in het Nederlands (Web Speech API)
- **Emotiethermometer** met 5 niveaus
- **Hulpknoppen** ("Hulp nodig" en "Bel begeleider")
- **Voortgangsbalk** van de hele dag
- **Dagstrip** bovenaan met 7 dagen, vandaag uitgelicht
- **Begeleidersbar** met foto's van wie er vandaag werkt

### Voor de begeleider (4 panelen)

**📋 Taken**
- Taken aanmaken, bewerken, verwijderen per bewoner
- Tijd, naam en pictogram aanpassen
- **Stappenplan bewerken** met stap-voor-stap volgorde, picto per stap, omhoog/omlaag verplaatsen
- 23 verschillende pictogrammen om uit te kiezen, inclusief werkgerichte: stofzuigen, dweilen, ramen, koken, oven, mixen, knutselen, tekenen, muziek, vouwen, inpakken

**👥 Begeleiders**
- Standaardlijst met 5 begeleiders (Sofie, Jet, Mirthe, Klaas, Anneke)
- Per dag aanvinken wie er aanwezig is — vinkjes resetten elke nacht
- Naam, rol, initialen aanpassen
- Begeleiders toevoegen of verwijderen

**📊 Inzichten**
- Per bewoner inzicht in hoe ze zich voelden
- **Staafdiagram** per emotie
- **Lijngrafiek** met trend over de tijd
- **Tijdlijn-lijst** wanneer welke emotie
- **Periode**: vandaag / afgelopen week / afgelopen maand
- **Gemiddelde score** (1-5)

**⚙️ Instellingen**
- Reset-knop om alle data te wissen

### Algemeen
- 3 voorbeeldbewoners: Marieke, Tim, Sanne — elk met eigen taken passend bij hun dag
- Alles in **localStorage** — blijft bewaard, ook na sluiten browser
- Werkt op iPad, telefoon en computer
- Volledig offline na eerste keer laden
- Eén HTML-bestand zonder externe afhankelijkheden

## Hosten op GitHub Pages

1. Maak een GitHub-account aan op github.com (gratis).
2. Klik rechtsboven op **+** → **New repository**.
3. Geef hem een naam, bijvoorbeeld `mijn-eigen-plan-demo`. Zet hem op **Public**. Klik **Create**.
4. Klik op **uploading an existing file** (linkje midden op pagina).
5. **Upload `index.html`** (let op: dit is de versie 2, hernoem het bestand zo nodig naar `index.html`).
6. Klik **Commit changes**.
7. Ga naar **Settings** (boven in de repo) → **Pages** (linkermenu).
8. Bij **Source**: kies **Deploy from a branch**.
9. Kies branch **main** en map **/ (root)**, klik **Save**.
10. Wacht 1-2 minuten. Bovenaan verschijnt je URL: `https://jouw-naam.github.io/mijn-eigen-plan-demo/`

## Op de iPad gebruiken

1. Open de URL in Safari op de iPad.
2. Tik op het deelknopje (vierkant met pijltje omhoog).
3. Kies "Zet op beginscherm".
4. De app staat nu als icoon op het beginscherm en opent fullscreen.

## Snelstart-tip voor je werkbegeleider

Wanneer je de app voor het eerst toont, doe dit even:
1. Klik op **Begeleider** (rechtsboven)
2. Ga naar **Begeleiders** (tab)
3. Vink de begeleiders aan die vandaag werken
4. Klik terug op **Bewoner**
5. Wissel tussen Marieke, Tim en Sanne om de verschillen te zien

## Voor in het voorstel

Deze demo laat zien:
- Hoe het er visueel uitziet voor zowel bewoner als begeleider
- Hoe een werkdag eruit zou kunnen zien op De Schaapskooi
- Hoe begeleiders kunnen monitoren hoe bewoners zich voelen (inzichten)
- Hoe taken makkelijk aangepast kunnen worden zonder technische kennis

In je voorstel kun je verwijzen naar de live URL zodat de werkbegeleider en docent zelf kunnen ervaren hoe het werkt voordat de échte Mijn Eigen Plan-software wordt aangeschaft.

## Licentie en gebruik

Dit is een schoolproject van Mirthe (4e jaars MZ niveau 4, Hoornbeeck College, stage De Schaapskooi Stellendam). De Sclera-pictogrammen-stijl is geïnspireerd op het werk van Sclera vzw (sclera.be). Voor een echte uitrol gebruik je de officiële Mijn Eigen Plan-software van mijneigenplan.nl.
