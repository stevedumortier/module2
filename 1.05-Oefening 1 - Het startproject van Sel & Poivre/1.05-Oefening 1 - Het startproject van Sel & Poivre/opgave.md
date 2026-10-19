## 1.5 · Oefening 1 — Het startproject van Sel & Poivre

*Rechtstreeks toepassen · leerstof uit 1.1 · oplossing: Oplossing 1.5*

### De situatie

**Sel & Poivre** is een kookatelier in Gent. Chefs geven er workshops in kleine groepen: brood bakken, verse pasta, sushi, chocolade. Het atelier wil een eigen website, in het Nederlands, met een warme maar frisse huisstijl. Jij bouwt die site, naast Roast & Co., de hele module lang.

### Wat je maakt

Een nieuw project `sel-et-poivre`, opgezet zoals Roast & Co. in 1.1, maar met de huisstijl van het kookatelier.

1. Maak de map `sel-et-poivre` met een `index.html` en een lege map `img/`. Maak er een Git-repository van.
2. Het HTML-skelet is **Nederlandstalig**: kies de juiste waarde voor `lang`. Titel: *Sel & Poivre – kookatelier in Gent*. Schrijf zelf een beschrijving van één zin voor de `description`.
3. Koppel Tailwind 4.3.3 via de Play CDN en Bootstrap Icons 1.13.1.
4. Koppel deze lettertypes van Google Fonts:

   ```none
   https://fonts.googleapis.com/css2?family=DM+Serif+Display:ital@0;1&family=Source+Sans+3:wght@400;600;700&display=swap
   ```

5. Leg de huisstijl vast in `@theme`:

   | Naam | Waarde | Gebruik |
   |---|---|---|
   | `basil` | `#2f5d50` | hoofdkleur, groen |
   | `basil-dark` | `#1f3f36` | donkere variant |
   | `tomato` | `#d0532f` | accent, alleen voor iconen en grote tekst |
   | `tomato-dark` | `#a63d20` | knoppen en accenten in tekst |
   | `flour` | `#fbf8f2` | achtergrond van de pagina |
   | `linen` | `#f0e8da` | achtergrond van secties |
   | `pepper` | `#22262a` | tekstkleur |

   Titels in *DM Serif Display*, gewone tekst in *Source Sans 3*.
6. Geef de `<body>` de achtergrond `flour`, de tekstkleur `pepper` en het tekstlettertype.
7. Zet een testblok in `<main>`: een titel, een korte zin en een tomatenrode knop die groen wordt bij hover. Gebruik als container **`max-w-5xl`** in plaats van `max-w-6xl`: Sel & Poivre is een smallere site dan Roast & Co.

### Zo controleer je

- De titel staat in een schreefletter, de tekst niet.
- De knop is tomatenrood en wordt basilicumgroen bij hover.
- De achtergrond is gebroken wit, niet zuiver wit.
- In de DevTools (<kbd>F12</kbd> › *Elements*) staat `lang="nl"` op het `<html>`-element.
- Je eerste commit staat in de repository.

> [!TIP]
> Je kan de `<head>` van Roast & Co. als vertrekpunt kopiëren. Kijk dan wel elke regel na: alles wat over koffie gaat, moet weg.
