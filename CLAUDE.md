# Signal in the Static — CLAUDE.md

## Projektin kuvaus

Quarto-pohjainen blogi GitHub Pagesissa. Spekulatiivinen fiktio ja sarjakuva-arvostelut suomeksi.
GitHub: vkauppine/signal-in-the-static

## Kieli ja tyyli

- Kaikki julkaistu sisältö **suomeksi**
- Analyyttinen mutta luettava ote — ei akateeminen, ei popkulttuuri-fanikirjoitus
- Esseemuoto ensisijainen nopean arvostelukierron sijaan
- Älä käytä swedes­ismiä "toimesta" äläkä finglish-verbejä (esim. "plottas")

## Sisältöstrategia (kolme tasoa)

1. **Pitkät temaattiset esseet ja sarjanalyysit** — pääformaatti
2. **Kohdennetut arvostelut + suomalaisen spekulatiivisen fiktion nostot**
3. **Klassikkokirjallisuuden nostot**

## Analyyttinen linssi

- Teknologinen ja taloudellinen uskottavuus teoksissa
- Markkinatalouden näkökulma, joka tunnistaa rakenteelliset ongelmat
- Tavallisen ihmisen perspektiivi

## Tiedostorakenne

- Postit: `.qmd`-formaatti YAML-headereineen
- Nimeämiskäytäntö: `aihe_indeksi.qmd` (esim. `absolute_batman_01.qmd`)
- Kaikki postit hakemistossa `posts/`

## YAML-header malli

```yaml
---
title: "Otsikko tähän"
date: "YYYY-MM-DD"
categories: [sarjakuvat, dc, absolute-universe]   # tai: [kirjallisuus, scifi]
description: "Lyhyt kuvaus."
image: cover.jpg
---
```

## Julkaistuja arvosteluja (referenssi tyylille)

Sarjakuvat: Absolute Green Lantern Vol. 1, Absolute Superman Vol. 1, Absolute Batman Vol. 1,
Absolute Wonder Woman Vol. 1, Absolute Flash Vol. 1, Ultramega, Where the Body Was, Pulp,
Scumbag vol. 1–3, Demon in a Bottle, Supergirl: Woman of Tomorrow

Kirjallisuus: Hawksbill Station, Flowers for Algernon, Concrete Island, The Folding Knife

## Tekniset huomiot

- GoatCounter-analytiikka: signal-in-the-static.goatcounter.com
- Giscus-kommentit käytössä
- RSS-syöte konfiguroitu

## Tyypilliset tehtävät

- Uuden postauksen luominen: tee `.qmd`-tiedosto oikealla YAML-headerilla
- Tyylitarkistus: tarkista kieliasu, vältä toimesta/finglish-ongelmat
- Rakenteen tarkistus: varmista että categories-tagit ovat johdonmukaisia aiempien kanssa
