# Výpadky léků v ČR podle let: počet přerušení dodávek a jejich délka

Počet přerušení a ukončení dodávek léčivých přípravků nahlášených SÚKL v každém roce od roku 2007, medián délky přerušení ve dnech a počet přerušení, která stále trvají.

- **Stav dat:** 9. 11. 2026
- **Řádků:** 22
- **Zdroj:** [SÚKL (hlášení o dodávkách léčivých přípravků)](https://opendata.sukl.gov.cz/katalog-otevrenych-dat/hlaseni-o-uvedeni-preruseni-ukonceni-obnoveni-dodavek-leciveho-pripravku-na-trh)
- **Licence:** Podmínky SÚKL, komerční užití povoleno
- **Jak citovat:** Zdroj: SÚKL (hlášení o dodávkách léčivých přípravků); zpracoval czechdatasets.com, https://czechdatasets.com/otevrena-data/vypadky-leku-podle-let
- **Ke stažení:** [CSV](https://czechdatasets.com/open/vypadky-leku-podle-let.csv) · [JSON](https://czechdatasets.com/open/vypadky-leku-podle-let.json) · [Markdown](https://czechdatasets.com/open/vypadky-leku-podle-let.md)
- **Stránka tabulky:** https://czechdatasets.com/otevrena-data/vypadky-leku-podle-let
- **Plná datová sada:** [Výpadky a dostupnost léků](https://czechdatasets.com/data/sukl-vypadky)

Výpadek = interval od hlášení přerušení nebo ukončení dodávek do hlášení obnovení. Počítá se po kódech SÚKL (variantách balení), jeden lék může mít více výpadků. Poslední rok není úplný.

## Sloupce

| Sloupec | Popis |
| --- | --- |
| `rok` | Rok začátku výpadku |
| `preruseni` | Počet přerušení dodávek |
| `ukonceni` | Počet ukončení dodávek |
| `median_dni_preruseni` | Medián délky ukončených přerušení ve dnech |
| `preruseni_trva` | Počet přerušení z daného roku, která ke dni stavu trvají |

## Data

| rok | preruseni | ukonceni | median_dni_preruseni | preruseni_trva |
| ---: | ---: | ---: | ---: | ---: |
| 2026 | 1910 | 623 | 42 | 678 |
| 2025 | 2034 | 765 | 52 | 137 |
| 2024 | 2567 | 910 | 50 | 70 |
| 2023 | 3054 | 1008 | 42 | 98 |
| 2022 | 2353 | 1017 | 48 | 34 |
| 2021 | 1548 | 908 | 37 | 21 |
| 2020 | 1744 | 754 | 45 | 29 |
| 2019 | 2039 | 1180 | 51 | 28 |
| 2018 | 1625 | 866 | 36 | 17 |
| 2017 | 1372 | 623 | 40 | 60 |
| 2016 | 1040 | 879 | 37 | 11 |
| 2015 | 1144 | 735 | 48 | 37 |
| 2014 | 906 | 681 | 50 | 31 |
| 2013 | 820 | 704 | 55 | 30 |
| 2012 | 852 | 568 | 77 | 71 |
| 2011 | 524 | 589 | 65 | 50 |
| 2010 | 416 | 495 | 183 | 81 |
| 2009 | 138 | 329 | 354 | 30 |
| 2008 | 56 | 123 | 161 | 11 |
| 2007 | 1 | 5 | 811 | 0 |
| 2006 | 0 | 2 |  | 0 |
| 2001 | 2 | 0 | 5691 | 0 |
