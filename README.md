# MAiNS International prototype

Statische prototypewebsite op basis van het aangeleverde Wix/Excel-bestand.

## Inhoud

- `index.html` — moderne one-page prototypeversie
- `assets/styles.css` — responsive styling
- `assets/reference-screenshots/` — selectie oude Wix-screenshots uit Excel als referentie
- `robots.txt` — prototype staat standaard op noindex

## Nog bevestigen vóór livegang

- Correct Nederlands kantooradres: Amsterdamsestraatweg 19 C1 of Kobaltstraat 31
- Actuele teamleden en e-mailadressen
- Of eerste versie alleen Nederlands is of direct NL/EN/CN
- Formulieroplossing: mailto, Formspree, FormSubmit of eigen Cloudflare Worker + mailprovider

## Lokaal testen

```bash
python3 -m http.server 8080
```

Open daarna `http://127.0.0.1:8080/`.

## GitHub Pages preview

Deze repo is voorbereid voor GitHub Pages branch deploy vanaf `main` en `/root`:

- `index.html` staat in de root
- `.nojekyll` is toegevoegd zodat GitHub Pages niets met Jekyll probeert te builden
- `robots.txt` en de meta tag staan voorlopig op `noindex`, zodat dit een klantpreview blijft en niet actief geïndexeerd hoeft te worden

Verwachte preview URL:

```text
https://siyao1993-maker.github.io/mains-international-site/
```
