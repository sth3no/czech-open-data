# Počet praktických lékařů, zubařů a nemocnic podle okresů

Počet míst poskytování zdravotní péče v každém okrese podle Národního registru poskytovatelů zdravotních služeb: ordinace praktických lékařů, praktických lékařů pro děti a dorost, zubních lékařů, gynekologie, nemocnice a všechna místa celkem.

- **Stav dat:** 1. 11. 2026
- **Řádků:** 78
- **Zdroj:** [ÚZIS ČR (Národní registr poskytovatelů zdravotních služeb)](https://datanzis.uzis.gov.cz/data/NR-01-NRPZS/NR-01-06/Otevrena-data-NR-01-06-nrpzs-mista-poskytovani-zdravotnich-sluzeb.csv)
- **Licence:** CC BY 4.0 (ÚZIS, ČÚZK)
- **Jak citovat:** Zdroj: ÚZIS ČR (Národní registr poskytovatelů zdravotních služeb); zpracoval czechdatasets.com, https://czechdatasets.com/otevrena-data/ordinace-podle-okresu
- **Ke stažení:** [CSV](https://czechdatasets.com/open/ordinace-podle-okresu.csv) · [JSON](https://czechdatasets.com/open/ordinace-podle-okresu.json) · [Markdown](https://czechdatasets.com/open/ordinace-podle-okresu.md)
- **Stránka tabulky:** https://czechdatasets.com/otevrena-data/ordinace-podle-okresu
- **Plná datová sada:** [Zdravotnická zařízení (NRPZS)](https://czechdatasets.com/data/poskytovatele-zdravotni-pece)

Jednotkou je místo poskytování péče (adresa zařízení) s daným oborem, ne lékař ani úvazek: v jedné ordinaci může pracovat více lékařů a nemocnice mají obor také.

## Sloupce

| Sloupec | Popis |
| --- | --- |
| `okres` | Okres (Česko = celá republika) |
| `kraj` | Kraj |
| `prakticky_lekar` | Míst s oborem všeobecné praktické lékařství |
| `detsky_lekar` | Míst s oborem praktické lékařství pro děti a dorost |
| `zubni_lekar` | Míst s oborem zubní lékařství |
| `gynekologie` | Míst s oborem gynekologie a porodnictví |
| `nemocnice` | Nemocnice |
| `mist_celkem` | Všechna místa poskytování péče |

## Data

| okres | kraj | prakticky_lekar | detsky_lekar | zubni_lekar | gynekologie | nemocnice | mist_celkem |
| --- | --- | ---: | ---: | ---: | ---: | ---: | ---: |
| Česko |  | 6013 | 2066 | 5919 | 2008 | 138 | 41136 |
| Hlavní město Praha | Hlavní město Praha | 824 | 260 | 1179 | 321 | 6 | 7010 |
| Brno-město | Jihomoravský kraj | 230 | 70 | 335 | 88 | 7 | 2213 |
| Ostrava-město | Moravskoslezský kraj | 159 | 53 | 211 | 69 | 2 | 1386 |
| Olomouc | Olomoucký kraj | 147 | 60 | 184 | 50 | 2 | 1113 |
| Plzeň-město | Plzeňský kraj | 107 | 37 | 165 | 48 | 5 | 993 |
| Zlín | Zlínský kraj | 120 | 28 | 137 | 33 | 2 | 900 |
| České Budějovice | Jihočeský kraj | 102 | 34 | 139 | 29 | 1 | 782 |
| Karviná | Moravskoslezský kraj | 116 | 42 | 100 | 49 | 6 | 776 |
| Frýdek-Místek | Moravskoslezský kraj | 107 | 44 | 107 | 31 | 3 | 730 |
| Hradec Králové | Královéhradecký kraj | 88 | 35 | 122 | 27 | 1 | 710 |
| Karlovy Vary | Karlovarský kraj | 64 | 23 | 69 | 38 | 2 | 656 |
| Pardubice | Pardubický kraj | 99 | 31 | 90 | 27 | 1 | 647 |
| Brno-venkov | Jihomoravský kraj | 106 | 38 | 70 | 31 | 1 | 595 |
| Liberec | Liberecký kraj | 98 | 33 | 100 | 25 | 5 | 593 |
| Opava | Moravskoslezský kraj | 105 | 30 | 75 | 33 | 1 | 592 |
| Uherské Hradiště | Zlínský kraj | 94 | 26 | 95 | 29 | 1 | 558 |
| Vsetín | Zlínský kraj | 78 | 33 | 79 | 35 | 2 | 533 |
| Hodonín | Jihomoravský kraj | 85 | 31 | 90 | 29 | 2 | 505 |
| Nový Jičín | Moravskoslezský kraj | 77 | 27 | 64 | 19 | 3 | 491 |
| Ústí nad Orlicí | Pardubický kraj | 77 | 28 | 54 | 23 | 1 | 488 |
| Kladno | Středočeský kraj | 81 | 28 | 76 | 29 | 2 | 477 |
| Přerov | Olomoucký kraj | 79 | 23 | 62 | 26 | 2 | 461 |
| Cheb | Karlovarský kraj | 52 | 15 | 39 | 22 | 1 | 456 |
| Šumperk | Olomoucký kraj | 71 | 19 | 64 | 21 | 1 | 456 |
| Trutnov | Královéhradecký kraj | 64 | 27 | 61 | 21 | 3 | 442 |
| Praha-západ | Středočeský kraj | 57 | 25 | 54 | 15 | 0 | 438 |
| Praha-východ | Středočeský kraj | 79 | 28 | 59 | 18 | 2 | 437 |
| Žďár nad Sázavou | Kraj Vysočina | 64 | 28 | 64 | 20 | 2 | 430 |
| Kroměříž | Zlínský kraj | 66 | 21 | 51 | 24 | 1 | 427 |
| Děčín | Ústecký kraj | 75 | 27 | 44 | 22 | 2 | 424 |
| Prostějov | Olomoucký kraj | 70 | 24 | 69 | 25 | 1 | 423 |
| Jihlava | Kraj Vysočina | 74 | 25 | 57 | 27 | 1 | 422 |
| Ústí nad Labem | Ústecký kraj | 54 | 21 | 49 | 37 | 3 | 406 |
| Litoměřice | Ústecký kraj | 66 | 22 | 46 | 19 | 1 | 405 |
| Mladá Boleslav | Středočeský kraj | 72 | 28 | 65 | 16 | 2 | 397 |
| Tábor | Jihočeský kraj | 61 | 15 | 46 | 18 | 1 | 392 |
| Chrudim | Pardubický kraj | 62 | 22 | 42 | 18 | 1 | 384 |
| Náchod | Královéhradecký kraj | 68 | 20 | 52 | 17 | 4 | 379 |
| Benešov | Středočeský kraj | 63 | 28 | 49 | 16 | 1 | 376 |
| Teplice | Ústecký kraj | 55 | 23 | 53 | 23 | 2 | 373 |
| Příbram | Středočeský kraj | 57 | 19 | 55 | 19 | 2 | 372 |
| Nymburk | Středočeský kraj | 52 | 18 | 52 | 20 | 2 | 369 |
| Jindřichův Hradec | Jihočeský kraj | 51 | 21 | 50 | 20 | 1 | 368 |
| Třebíč | Kraj Vysočina | 65 | 22 | 46 | 23 | 1 | 368 |
| Chomutov | Ústecký kraj | 65 | 27 | 53 | 22 | 2 | 359 |
| Znojmo | Jihomoravský kraj | 67 | 10 | 61 | 20 | 2 | 358 |
| Havlíčkův Brod | Kraj Vysočina | 63 | 17 | 50 | 14 | 1 | 351 |
| Břeclav | Jihomoravský kraj | 69 | 22 | 45 | 22 | 2 | 346 |
| Svitavy | Pardubický kraj | 60 | 28 | 34 | 15 | 3 | 341 |
| Mělník | Středočeský kraj | 60 | 14 | 45 | 14 | 1 | 334 |
| Most | Ústecký kraj | 55 | 26 | 45 | 18 | 1 | 326 |
| Blansko | Jihomoravský kraj | 56 | 17 | 54 | 17 | 2 | 321 |
| Bruntál | Moravskoslezský kraj | 50 | 21 | 35 | 20 | 3 | 317 |
| Jablonec nad Nisou | Liberecký kraj | 54 | 20 | 46 | 17 | 2 | 315 |
| Beroun | Středočeský kraj | 51 | 14 | 44 | 15 | 1 | 314 |
| Rychnov nad Kněžnou | Královéhradecký kraj | 46 | 20 | 27 | 16 | 1 | 305 |
| Česká Lípa | Liberecký kraj | 51 | 23 | 46 | 12 | 1 | 300 |
| Vyškov | Jihomoravský kraj | 44 | 18 | 39 | 8 | 1 | 295 |
| Kolín | Středočeský kraj | 50 | 23 | 43 | 17 | 1 | 293 |
| Klatovy | Plzeňský kraj | 51 | 20 | 41 | 23 | 2 | 291 |
| Sokolov | Karlovarský kraj | 43 | 12 | 22 | 16 | 1 | 279 |
| Kutná Hora | Středočeský kraj | 52 | 13 | 35 | 10 | 2 | 275 |
| Louny | Ústecký kraj | 43 | 17 | 33 | 10 | 1 | 274 |
| Jičín | Královéhradecký kraj | 49 | 17 | 28 | 12 | 2 | 267 |
| Pelhřimov | Kraj Vysočina | 48 | 11 | 32 | 14 | 1 | 265 |
| Semily | Liberecký kraj | 45 | 21 | 31 | 14 | 3 | 261 |
| Tachov | Plzeňský kraj | 38 | 11 | 24 | 10 | 0 | 261 |
| Strakonice | Jihočeský kraj | 44 | 13 | 27 | 13 | 1 | 230 |
| Písek | Jihočeský kraj | 47 | 17 | 29 | 12 | 1 | 228 |
| Český Krumlov | Jihočeský kraj | 38 | 17 | 34 | 11 | 1 | 221 |
| Plzeň-sever | Plzeňský kraj | 39 | 18 | 27 | 12 | 0 | 220 |
| Plzeň-jih | Plzeňský kraj | 46 | 15 | 23 | 10 | 1 | 207 |
| Domažlice | Plzeňský kraj | 28 | 11 | 22 | 11 | 1 | 183 |
| Prachatice | Jihočeský kraj | 36 | 13 | 16 | 8 | 1 | 169 |
| Rokycany | Plzeňský kraj | 29 | 11 | 19 | 9 | 1 | 164 |
| Rakovník | Středočeský kraj | 34 | 8 | 21 | 8 | 1 | 161 |
| Jeseník | Olomoucký kraj | 21 | 9 | 18 | 8 | 1 | 152 |
