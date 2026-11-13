# Jacklete Recipes · Fasting cena-pranzo

Aggiornamento: **13 novembre 2026**.

Il catalogo principale comprende **26 ricette nuove** per digiuno serale/notturno fino al pranzo, allenamento indicativamente a mezzogiorno, snack dolci e cena. Le **45 ricette precedenti restano accessibili** da `archivio.html` e dalle rispettive pagine `ricette/`.

## Target di riferimento

| Giorno | kcal | Proteine | Carboidrati | Grassi |
|---|---:|---:|---:|---:|
| ON | 2050 | 125 g | 241 g | 65 g |
| OFF | 1950 | 125 g | 216 g | 65 g |

## Struttura

- `index.html`: nuovo catalogo e compositore interattivo del menu.
- `ricette/fast_*.html`: ricette individuali, con JSON-LD Schema.org `Recipe` per l'importazione da URL in Cronometer Gold.
- `data/piano-fasting-nov2026.json`: ingredienti e calcolo stime nutrizionali, modificabile come sorgente di riferimento.
- `archivio.html`: indice storico delle 45 ricette.
- `assets/style.css`: stile condiviso.

Le 26 nuove ricette comprendono 6 primi pasti ON salati, 5 primi pasti OFF (3 dolci, 2 salati), 7 snack dolci, 3 mini snack e 5 cene di riferimento.

## Regole dei pesi e dei valori

- Cereali, pasta, couscous e quinoa: peso a crudo/secco.
- Carne e pesce: peso a crudo. Piselli e ceci: cotti e sgocciolati.
- Le stime dei macro derivano da valori generici per 100 g definiti in `data/piano-fasting-nov2026.json`; kcal da 4/4/9 kcal per grammo P/C/G.
- **Non** sono valori certificati o ricavati da etichette di marchi specifici. Dopo l'importazione in Cronometer scegliere ingredienti corrispondenti, verificando confezioni acquistate in Spagna, grassi dello yogurt e stato crudo/cotto.
- Per l'importazione usare l'indirizzo pubblico della pagina della ricetta, non il link al file su github.com.

## Sicurezza

Il sito è una raccolta di ricette e non sostituisce consigli clinici. Digiuno prolungato e allenamento a digiuno in presenza di terapia farmacologica richiedono valutazione medica individuale. Non contiene dati sanitari personali.

Fonti generali: [ISSN Protein and Exercise](https://pmc.ncbi.nlm.nih.gov/articles/PMC5477153/), [Cronometer Recipe Importer](https://support.cronometer.com/hc/en-us/articles/4403966087828-Mobile-Recipe-Importer), [EMA Forxiga EPAR](https://www.ema.europa.eu/en/medicines/human/EPAR/forxiga).
