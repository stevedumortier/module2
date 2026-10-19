## 1.7 · Challenge — Binnenkort in het atelier

*Eigen keuzes · leerstof uit stap 1 · oplossing: Oplossing 1.7*

### De situatie

Onder de hero wil Sel & Poivre de drie eerstvolgende workshops in de kijker zetten. Het atelier heeft het ontwerp beschreven, niet getekend. Hoe je het bouwt, beslis je zelf.

| Workshop | Datum | Keuken · niveau | Prijs | Bijzonder |
|---|---|---|---|---|
| Brood bakken met desem | 3 oktober | Belgisch · beginner | €85 | |
| Verse pasta van begin tot bord | 11 oktober | Italiaans · beginner | €79 | **volzet** |
| Chocolade tempereren | 28 november | Belgisch · gevorderd | €95 | |

### De wensen van het atelier

1. Een sectie met `id="binnenkort"` op een `linen`-achtergrond, met een klein label in hoofdletters boven de titel. Maak daar een component `kicker` van: je hebt hem in elke volgende sectie nodig.
2. Elke workshop is een kaart met een foto in verhouding 4:3, de keuken en het niveau, de titel, één zin uitleg en onderaan de prijs met een knop *Inschrijven*. De prijzen staan in alle kaarten op dezelfde hoogte.
3. De **datum** staat als klein wit blokje **over de foto**, linksboven: de dag groot, de maand klein eronder.
4. Bij hover zoomt de foto lichtjes in. Wie animaties uitgeschakeld heeft, ziet geen beweging.
5. De **volzette** workshop valt meteen op als niet beschikbaar: de foto in grijstinten, een label *Volzet* rechtsboven op de foto, een gedempte prijs, en in plaats van de knop alleen het woord *Wachtlijst*.
6. Smartphone: één kaart per rij. Laptop: drie naast elkaar. **Tablet**: de eerste twee naast elkaar, en de derde **over de volle breedte** eronder, zodat er geen lege plek overblijft.

### Zo controleer je

- Bekijk de sectie op 390px, 800px en 1200px. Op 800px is er geen lege cel in het grid.
- Gebruik de DevTools om de hover te testen (*Elements* › rechtsklik op de kaart › *Force state* › `:hover`).
- Commit, en zet de repository van Sel & Poivre op GitHub.

> [!TIP]
> Wensen 3 en 6 vragen geen nieuwe leerstof, wel een combinatie. Voor 3: welk element wordt het kader voor het blokje? Voor 6: een kaart kan meer dan één kolom innemen (`col-span-2`), en dat kan per breakpoint verschillen. Voor de grijstinten: zoek *grayscale* op in de documentatie van Tailwind.
