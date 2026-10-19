## 1.6 · Oefening 2 — Navbar en hero

*Combineren · leerstof uit 1.2 en 1.3 · oplossing: Oplossing 1.6*

### De situatie

Het testblok mag weg. Sel & Poivre wil bovenaan een **lichte** navigatiebalk, geen donkere zoals Roast & Co., en een hero waarin de **foto links** staat en de tekst rechts.

### Wat je maakt

**De navbar**

- Een balk die bovenaan blijft plakken, met een lichte achtergrond (`flour`), een dunne lijn eronder en een logo met het icoon `bi-fire` in tomatenrood.
- Vier links: *Binnenkort*, *Het atelier*, *Programma* en *Inschrijven* (naar `#binnenkort`, `#atelier`, `#programma`, `#inschrijven`). De secties bestaan nog niet; de links maak je nu al.
- Een knop *Schrijf je in* met je eigen componenten `btn` en `btn-tomato`. Een knop van Sel & Poivre is **volledig rond** (`rounded-full`).
- Het menu staat naast het logo vanaf **`md`** (768px), niet vanaf `lg`. Daaronder zie je een hamburgerknop, met een Nederlandstalig `aria-label`.

**De hero**

- Een sectie met `id="home"` en twee kolommen vanaf `md`. Op een smartphone staat de tekst **boven** de foto, vanaf `md` staat de foto **links**.
- In de tekstkolom: een label *Nieuw najaarsprogramma* met een icoon, de titel *Koken leer je met je handen* (de laatste drie woorden schuin en tomatenrood), een korte inleiding en twee knoppen: *Bekijk de workshops* (`btn-tomato`) en *Ons team* (een nieuwe component `btn-ghost` met een groene rand).
- Onder de knoppen drie cijfers in een definitielijst: *12 workshops per seizoen*, *8 chefs*, *max. 14 deelnemers per groep*. Het getal staat boven de omschrijving.
- De foto `hero.jpg` (uit `2-oefeningen-Sel-et-Poivre/afbeeldingen/`) is **vierkant**, met sterk afgeronde hoeken en een schaduw.

### Zo controleer je

- Op 390px: logo en hamburgerknop, daaronder de tekst en dan de foto. Geen horizontale scrollbalk.
- Op 768px en breder: de vier links en de knop staan naast het logo; de foto staat links van de tekst.
- De drie cijfers staan op elk scherm naast elkaar.
- Er is precies één `<h1>` op de pagina.

> [!TIP]
> Voor de foto links heb je één class nodig die je nog niet in de cursus zag, maar die je kan afleiden: kijk in de documentatie bij [Order](https://tailwindcss.com/docs/order). Waarom is het beter om de volgorde met een class om te draaien dan de HTML om te wisselen? Denk aan de volgorde waarin een schermlezer de pagina voorleest.

> [!NOTE]
> De foto's van Sel & Poivre komen van [Unsplash](https://unsplash.com/) en mogen gratis gebruikt worden. Wil je liever een eigen foto, zoek er dan een op Unsplash of [Pexels](https://www.pexels.com/). Let op de verhouding, en pas de `alt`-tekst aan zodat ze beschrijft wat er écht op jouw foto staat.
