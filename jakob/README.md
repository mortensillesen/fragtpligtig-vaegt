# Jakob tip en 13'er

En lille webside med 13 spørgsmål om Jakob, hvor man tipper 1, X eller 2.

- `index.html` er hele spillet. Ingen server, ingen afhængigheder.
- Hver spiller åbner siden i sin egen browser. Svar gemmes løbende i browserens localStorage.
- Afleverede resultater vises nederst på siden (kun i den browser, de er afleveret fra).

## Udfyld svarmuligheder og facit

Øverst i `<script>` i `index.html`:

- `SPOERGSMAAL[n].valg` er de tre svarmuligheder i rækkefølgen 1, X, 2. Tomme tekster viser kun 1 / X / 2.
- `FACIT` er en tekst på 13 tegn med 1, X eller 2, fx `"1X2X12X1221X1"`. Lad den være `null`, hvis der ikke skal regnes point.

## Sådan deles siden

Slå GitHub Pages til under Settings → Pages (branch `main`, mappe `/`). Siden ligger derefter på
`https://mortensillesen.github.io/JAKOB/`.
