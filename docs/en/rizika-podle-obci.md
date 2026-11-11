# Flood risk by municipality in the Czech Republic: share of addresses in the 100-year flood zone

For every Czech municipality: number and share of addresses in the 5-, 20- and 100-year flood zones (Q5, Q20, Q100), in the active flood zone, on undermined land, with a high radon index and on landslide areas.

134,253 Czech addresses (4.4% of all) lie in the 100-year flood zone (Q100), in 2,657 municipalities.

113,908 addresses are on undermined land and 234,287 addresses have a high bedrock radon index.

- **Data as of:** 11 November 2026
- **Rows:** 6,258
- **Source:** [VÚV TGM, Czech Geological Survey, AOPK ČR, ČHMÚ and ČÚZK](https://heis.vuv.cz/isvs/zapluz)
- **Licence:** CC BY 4.0 (VÚV TGM, ČGS, AOPK ČR, ČHMÚ, ČÚZK), MŽP
- **How to cite:** Source: VÚV TGM, Czech Geological Survey, AOPK ČR, ČHMÚ and ČÚZK; processed by czechdatasets.com, https://czechdatasets.com/en/otevrena-data/rizika-podle-obci
- **Download:** [CSV](https://czechdatasets.com/open/rizika-podle-obci.csv) · [JSON](https://czechdatasets.com/open/rizika-podle-obci.json) · [Markdown](https://czechdatasets.com/open/en/rizika-podle-obci.md)
- **Table page:** https://czechdatasets.com/en/otevrena-data/rizika-podle-obci
- **Full dataset:** [Address risks](https://czechdatasets.com/en/data/rizika-adres)

Computed from the position of each RÚIAN address point against layers of VÚV TGM (flood zones) and the Czech Geological Survey (undermining, radon, landslides). Flood zones are not designated on all watercourses, so zero does not mean a municipality cannot flood.

## Columns

| Column | Description |
| --- | --- |
| `obec_kod` | Municipality code (RÚIAN, same as the Czech Statistical Office code) |
| `obec` | Municipality name |
| `okres` | District (okres) |
| `kraj` | Region (kraj) |
| `pocet_adres` | Number of address points |
| `adres_q5` | Addresses in the 5-year flood zone (Q5) |
| `adres_q20` | Addresses in the 20-year flood zone (Q20) |
| `adres_q100` | Addresses in the 100-year flood zone (Q100) |
| `podil_q100_pct` | Share of the municipality's addresses in the Q100 flood zone, percent |
| `adres_aktivni_zona` | Addresses in the active flood zone |
| `adres_poddolovani` | Addresses on undermined land |
| `podil_poddolovani_pct` | Share of addresses on undermined land, percent |
| `adres_radon_vysoky` | Addresses with a high radon index of the bedrock |
| `podil_radon_vysoky_pct` | Share of addresses with a high radon index, percent |
| `adres_svahova_nestabilita` | Addresses on a landslide area |

## Data

First 100 of 6,258 rows. Full table: https://czechdatasets.com/open/rizika-podle-obci.csv

| obec_kod | obec | okres | kraj | pocet_adres | adres_q5 | adres_q20 | adres_q100 | podil_q100_pct | adres_aktivni_zona | adres_poddolovani | podil_poddolovani_pct | adres_radon_vysoky | podil_radon_vysoky_pct | adres_svahova_nestabilita |
| ---: | --- | --- | --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| 582786 | Brno | Brno-město | Jihomoravský kraj | 62524 | 81 | 314 | 5256 | 8.43 | 135 | 1 | 0.0 | 0 | 0.0 | 1936 |
| 500496 | Olomouc | Olomouc | Olomoucký kraj | 14782 | 278 | 2454 | 3880 | 26.25 | 0 | 0 | 0.0 | 0 | 0.0 | 15 |
| 554782 | Praha | Hlavní město Praha | Hlavní město Praha | 134676 | 483 | 1152 | 2457 | 1.82 | 379 | 191 | 0.14 | 2507 | 1.86 | 23 |
| 511382 | Přerov | Přerov | Olomoucký kraj | 7104 | 151 | 413 | 2224 | 31.31 | 403 | 0 | 0.0 | 0 | 0.0 | 0 |
| 503444 | Litovel | Olomouc | Olomoucký kraj | 2797 | 237 | 980 | 1844 | 65.93 | 0 | 0 | 0.0 | 0 | 0.0 | 0 |
| 588296 | Kroměříž | Kroměříž | Zlínský kraj | 6183 | 2 | 303 | 1755 | 28.38 | 99 | 0 | 0.0 | 0 | 0.0 | 0 |
| 584291 | Břeclav | Břeclav | Jihomoravský kraj | 5234 | 1 | 5 | 1752 | 33.47 | 5 | 0 | 0.0 | 0 | 0.0 | 0 |
| 569810 | Hradec Králové | Hradec Králové | Královéhradecký kraj | 16316 | 333 | 559 | 1237 | 7.58 | 47 | 0 | 0.0 | 0 | 0.0 | 21 |
| 597520 | Krnov | Bruntál | Moravskoslezský kraj | 3743 | 8 | 69 | 1149 | 30.7 | 39 | 0 | 0.0 | 0 | 0.0 | 3 |
| 588491 | Hulín | Kroměříž | Zlínský kraj | 1663 | 18 | 608 | 1033 | 62.12 | 1 | 0 | 0.0 | 0 | 0.0 | 0 |
| 554804 | Ústí nad Labem | Ústí nad Labem | Ústecký kraj | 16973 | 16 | 219 | 813 | 4.79 | 102 | 25 | 0.15 | 94 | 0.55 | 1407 |
| 544256 | České Budějovice | České Budějovice | Jihočeský kraj | 13181 | 7 | 125 | 795 | 6.03 | 10 | 23 | 0.17 | 0 | 0.0 | 0 |
| 585068 | Zlín | Zlín | Zlínský kraj | 18167 | 2 | 24 | 788 | 4.34 | 2 | 0 | 0.0 | 0 | 0.0 | 769 |
| 592731 | Uherský Brod | Uherské Hradiště | Zlínský kraj | 4731 | 0 | 45 | 787 | 16.63 | 0 | 0 | 0.0 | 0 | 0.0 | 727 |
| 554821 | Ostrava | Ostrava-město | Moravskoslezský kraj | 34079 | 105 | 319 | 786 | 2.31 | 399 | 16408 | 48.15 | 0 | 0.0 | 247 |
| 533165 | Kolín | Kolín | Středočeský kraj | 5320 | 2 | 11 | 756 | 14.21 | 3 | 0 | 0.0 | 0 | 0.0 | 0 |
| 519651 | Troubky | Přerov | Olomoucký kraj | 728 | 0 | 666 | 725 | 99.59 | 0 | 0 | 0.0 | 0 | 0.0 | 0 |
| 550744 | Kunovice | Uherské Hradiště | Zlínský kraj | 1916 | 6 | 366 | 723 | 37.73 | 2 | 0 | 0.0 | 0 | 0.0 | 2 |
| 505927 | Opava | Opava | Moravskoslezský kraj | 9030 | 9 | 41 | 717 | 7.94 | 53 | 48 | 0.53 | 0 | 0.0 | 0 |
| 599051 | Bohumín | Karviná | Moravskoslezský kraj | 4981 | 0 | 114 | 712 | 14.29 | 62 | 322 | 6.46 | 0 | 0.0 | 51 |
| 562335 | Děčín | Děčín | Ústecký kraj | 10481 | 24 | 202 | 660 | 6.3 | 35 | 1 | 0.01 | 0 | 0.0 | 2341 |
| 539139 | Černošice | Praha-západ | Středočeský kraj | 3393 | 386 | 570 | 659 | 19.42 | 148 | 0 | 0.0 | 5 | 0.15 | 5 |
| 563889 | Liberec | Liberec | Liberecký kraj | 16341 | 95 | 314 | 639 | 3.91 | 75 | 0 | 0.0 | 15597 | 95.45 | 0 |
| 565717 | Terezín | Litoměřice | Ústecký kraj | 967 | 26 | 346 | 639 | 66.08 | 28 | 0 | 0.0 | 0 | 0.0 | 0 |
| 592005 | Uherské Hradiště | Uherské Hradiště | Zlínský kraj | 5435 | 0 | 8 | 636 | 11.73 | 1 | 0 | 0.0 | 0 | 0.0 | 21 |
| 513750 | Hranice | Přerov | Olomoucký kraj | 3548 | 116 | 369 | 632 | 17.81 | 80 | 0 | 0.0 | 0 | 0.0 | 266 |
| 534951 | Kralupy nad Vltavou | Mělník | Středočeský kraj | 3131 | 50 | 304 | 623 | 19.9 | 230 | 71 | 2.27 | 0 | 0.0 | 2 |
| 571164 | Chrudim | Chrudim | Pardubický kraj | 4385 | 8 | 223 | 617 | 14.07 | 36 | 0 | 0.0 | 0 | 0.0 | 0 |
| 557153 | Sušice | Klatovy | Plzeňský kraj | 2681 | 36 | 181 | 601 | 22.42 | 30 | 0 | 0.0 | 2 | 0.07 | 0 |
| 573868 | Náchod | Náchod | Královéhradecký kraj | 5430 | 1 | 230 | 593 | 10.92 | 0 | 0 | 0.0 | 8 | 0.15 | 140 |
| 554791 | Plzeň | Plzeň-město | Plzeňský kraj | 27587 | 75 | 187 | 584 | 2.12 | 87 | 903 | 3.27 | 9 | 0.03 | 0 |
| 555134 | Pardubice | Pardubice | Pardubický kraj | 12911 | 85 | 352 | 573 | 4.44 | 26 | 0 | 0.0 | 0 | 0.0 | 7 |
| 564974 | Káraný | Praha-východ | Středočeský kraj | 1207 | 25 | 497 | 567 | 47.01 | 49 | 0 | 0.0 | 0 | 0.0 | 0 |
| 550752 | Staré Město | Uherské Hradiště | Zlínský kraj | 2107 | 0 | 28 | 565 | 26.82 | 3 | 0 | 0.0 | 0 | 0.0 | 0 |
| 583120 | Ivančice | Brno-venkov | Jihomoravský kraj | 4161 | 22 | 285 | 547 | 13.15 | 58 | 2 | 0.05 | 0 | 0.0 | 59 |
| 564095 | Hrádek nad Nisou | Liberec | Liberecký kraj | 2196 | 49 | 373 | 522 | 23.77 | 48 | 7 | 0.32 | 0 | 0.0 | 0 |
| 565971 | Louny | Louny | Ústecký kraj | 3909 | 391 | 422 | 475 | 12.15 | 317 | 0 | 0.0 | 0 | 0.0 | 0 |
| 505587 | Uničov | Olomouc | Olomoucký kraj | 3370 | 219 | 363 | 464 | 13.77 | 128 | 10 | 0.3 | 0 | 0.0 | 0 |
| 586307 | Kyjov | Hodonín | Jihomoravský kraj | 3267 | 0 | 5 | 456 | 13.96 | 0 | 227 | 6.95 | 0 | 0.0 | 13 |
| 540862 | Rapotín | Šumperk | Olomoucký kraj | 931 | 0 | 12 | 441 | 47.37 | 0 | 0 | 0.0 | 13 | 1.4 | 0 |
| 553271 | Veselí nad Lužnicí | Tábor | Jihočeský kraj | 1759 | 16 | 34 | 424 | 24.1 | 27 | 0 | 0.0 | 1 | 0.06 | 0 |
| 539198 | Dobřichovice | Praha-západ | Středočeský kraj | 1209 | 2 | 22 | 420 | 34.74 | 2 | 0 | 0.0 | 0 | 0.0 | 0 |
| 561380 | Česká Lípa | Česká Lípa | Liberecký kraj | 4830 | 12 | 93 | 418 | 8.65 | 20 | 0 | 0.0 | 0 | 0.0 | 87 |
| 569445 | Vikýřovice | Šumperk | Olomoucký kraj | 755 | 0 | 13 | 408 | 54.04 | 0 | 0 | 0.0 | 0 | 0.0 | 5 |
| 579203 | Dvůr Králové nad Labem | Trutnov | Královéhradecký kraj | 4026 | 33 | 171 | 405 | 10.06 | 37 | 0 | 0.0 | 0 | 0.0 | 0 |
| 579891 | Ústí nad Orlicí | Ústí nad Orlicí | Pardubický kraj | 3123 | 23 | 167 | 396 | 12.68 | 15 | 0 | 0.0 | 0 | 0.0 | 261 |
| 592749 | Uherský Ostroh | Uherské Hradiště | Zlínský kraj | 1556 | 0 | 0 | 396 | 25.45 | 1 | 0 | 0.0 | 0 | 0.0 | 0 |
| 570877 | Smiřice | Hradec Králové | Královéhradecký kraj | 756 | 0 | 1 | 395 | 52.25 | 1 | 0 | 0.0 | 0 | 0.0 | 0 |
| 564591 | Bohušovice nad Ohří | Litoměřice | Ústecký kraj | 530 | 6 | 98 | 395 | 74.53 | 6 | 0 | 0.0 | 0 | 0.0 | 0 |
| 567451 | Bílina | Teplice | Ústecký kraj | 3294 | 0 | 16 | 385 | 11.69 | 12 | 210 | 6.38 | 0 | 0.0 | 0 |
| 564371 | Raspenava | Liberec | Liberecký kraj | 923 | 109 | 270 | 385 | 41.71 | 128 | 0 | 0.0 | 193 | 20.91 | 0 |
| 545058 | Valašské Meziříčí | Vsetín | Zlínský kraj | 4110 | 10 | 71 | 384 | 9.34 | 2 | 0 | 0.0 | 0 | 0.0 | 60 |
| 552828 | Planá nad Lužnicí | Tábor | Jihočeský kraj | 1945 | 159 | 207 | 381 | 19.59 | 176 | 0 | 0.0 | 8 | 0.41 | 0 |
| 535087 | Neratovice | Mělník | Středočeský kraj | 2353 | 2 | 113 | 380 | 16.16 | 38 | 0 | 0.0 | 418 | 17.77 | 0 |
| 592412 | Nedakonice | Uherské Hradiště | Zlínský kraj | 560 | 0 | 2 | 373 | 66.61 | 1 | 0 | 0.0 | 0 | 0.0 | 0 |
| 505161 | Štěpánov | Olomouc | Olomoucký kraj | 1032 | 1 | 134 | 372 | 36.05 | 1 | 0 | 0.0 | 0 | 0.0 | 0 |
| 584860 | Rakvice | Břeclav | Jihomoravský kraj | 842 | 0 | 0 | 368 | 43.71 | 0 | 0 | 0.0 | 0 | 0.0 | 0 |
| 534676 | Mělník | Mělník | Středočeský kraj | 4331 | 12 | 26 | 365 | 8.43 | 21 | 4 | 0.09 | 0 | 0.0 | 0 |
| 581259 | Žamberk | Ústí nad Orlicí | Pardubický kraj | 1657 | 11 | 208 | 362 | 21.86 | 4 | 0 | 0.0 | 0 | 0.0 | 3 |
| 592889 | Vyškov | Vyškov | Jihomoravský kraj | 5909 | 0 | 2 | 347 | 5.93 | 2 | 0 | 0.0 | 0 | 0.0 | 0 |
| 599701 | Odry | Nový Jičín | Moravskoslezský kraj | 2057 | 3 | 15 | 337 | 16.38 | 12 | 0 | 0.0 | 0 | 0.0 | 538 |
| 564621 | Brozany nad Ohří | Litoměřice | Ústecký kraj | 627 | 88 | 265 | 336 | 53.59 | 141 | 0 | 0.0 | 0 | 0.0 | 0 |
| 514055 | Kojetín | Přerov | Olomoucký kraj | 1656 | 3 | 157 | 330 | 19.93 | 2 | 0 | 0.0 | 0 | 0.0 | 0 |
| 571041 | Třebechovice pod Orebem | Hradec Králové | Královéhradecký kraj | 2104 | 118 | 155 | 324 | 15.4 | 30 | 0 | 0.0 | 0 | 0.0 | 0 |
| 537683 | Poděbrady | Nymburk | Středočeský kraj | 3578 | 22 | 127 | 319 | 8.92 | 10 | 0 | 0.0 | 0 | 0.0 | 0 |
| 582441 | Svitávka | Blansko | Jihomoravský kraj | 724 | 2 | 20 | 316 | 43.83 | 1 | 0 | 0.0 | 0 | 0.0 | 0 |
| 502545 | Horka nad Moravou | Olomouc | Olomoucký kraj | 792 | 2 | 19 | 312 | 39.39 | 0 | 0 | 0.0 | 0 | 0.0 | 0 |
| 545392 | Český Krumlov | Český Krumlov | Jihočeský kraj | 2359 | 2 | 83 | 307 | 13.01 | 5 | 400 | 16.96 | 0 | 0.0 | 3 |
| 578576 | Polička | Svitavy | Pardubický kraj | 2485 | 135 | 271 | 306 | 12.31 | 12 | 0 | 0.0 | 73 | 2.94 | 3 |
| 589161 | Záříčí | Kroměříž | Zlínský kraj | 297 | 0 | 4 | 297 | 100.0 | 2 | 0 | 0.0 | 0 | 0.0 | 0 |
| 514705 | Lipník nad Bečvou | Přerov | Olomoucký kraj | 2655 | 47 | 93 | 295 | 11.12 | 40 | 0 | 0.0 | 0 | 0.0 | 214 |
| 564028 | Frýdlant | Liberec | Liberecký kraj | 1731 | 3 | 163 | 290 | 16.75 | 60 | 0 | 0.0 | 7 | 0.4 | 0 |
| 576964 | Semily | Semily | Liberecký kraj | 1689 | 3 | 162 | 287 | 17.06 | 61 | 0 | 0.0 | 67 | 3.98 | 141 |
| 523704 | Šumperk | Šumperk | Olomoucký kraj | 3263 | 0 | 146 | 277 | 8.49 | 0 | 16 | 0.49 | 1851 | 56.73 | 0 |
| 513491 | Horní Moštěnice | Přerov | Olomoucký kraj | 683 | 0 | 189 | 276 | 40.41 | 3 | 0 | 0.0 | 0 | 0.0 | 0 |
| 584100 | Veverská Bítýška | Brno-venkov | Jihomoravský kraj | 1300 | 26 | 62 | 274 | 21.08 | 53 | 0 | 0.0 | 0 | 0.0 | 12 |
| 589250 | Prostějov | Prostějov | Olomoucký kraj | 7761 | 0 | 16 | 268 | 3.45 | 0 | 0 | 0.0 | 0 | 0.0 | 0 |
| 541630 | Vsetín | Vsetín | Zlínský kraj | 3778 | 0 | 18 | 265 | 7.01 | 1 | 1 | 0.03 | 0 | 0.0 | 215 |
| 590029 | Smržice | Prostějov | Olomoucký kraj | 612 | 79 | 173 | 265 | 43.3 | 5 | 0 | 0.0 | 0 | 0.0 | 0 |
| 592943 | Bučovice | Vyškov | Jihomoravský kraj | 2428 | 0 | 29 | 264 | 10.87 | 1 | 0 | 0.0 | 0 | 0.0 | 1 |
| 565083 | Křešice | Litoměřice | Ústecký kraj | 546 | 1 | 21 | 264 | 48.35 | 5 | 0 | 0.0 | 0 | 0.0 | 56 |
| 534935 | Kostelec nad Labem | Mělník | Středočeský kraj | 1689 | 22 | 214 | 259 | 15.33 | 6 | 0 | 0.0 | 0 | 0.0 | 0 |
| 583952 | Šlapanice | Brno-venkov | Jihomoravský kraj | 2604 | 0 | 48 | 256 | 9.83 | 4 | 0 | 0.0 | 0 | 0.0 | 179 |
| 539643 | Řevnice | Praha-západ | Středočeský kraj | 1459 | 37 | 85 | 256 | 17.55 | 35 | 0 | 0.0 | 0 | 0.0 | 0 |
| 590266 | Třebíč | Třebíč | Kraj Vysočina | 6569 | 44 | 66 | 253 | 3.85 | 1 | 46 | 0.7 | 5777 | 87.96 | 2 |
| 583588 | Oslavany | Brno-venkov | Jihomoravský kraj | 1764 | 1 | 101 | 251 | 14.23 | 0 | 886 | 50.23 | 0 | 0.0 | 6 |
| 563129 | Klášterec nad Ohří | Chomutov | Ústecký kraj | 3130 | 143 | 203 | 247 | 7.89 | 136 | 9 | 0.29 | 0 | 0.0 | 10 |
| 519146 | Tovačov | Přerov | Olomoucký kraj | 947 | 9 | 104 | 241 | 25.45 | 6 | 0 | 0.0 | 0 | 0.0 | 0 |
| 598933 | Český Těšín | Karviná | Moravskoslezský kraj | 5579 | 4 | 28 | 236 | 4.23 | 24 | 8 | 0.14 | 0 | 0.0 | 5 |
| 567256 | Litvínov | Most | Ústecký kraj | 4728 | 0 | 13 | 235 | 4.97 | 11 | 1547 | 32.72 | 284 | 6.01 | 1 |
| 597210 | Brantice | Bruntál | Moravskoslezský kraj | 567 | 13 | 94 | 234 | 41.27 | 9 | 0 | 0.0 | 0 | 0.0 | 0 |
| 588512 | Chropyně | Kroměříž | Zlínský kraj | 935 | 4 | 102 | 231 | 24.71 | 9 | 0 | 0.0 | 0 | 0.0 | 0 |
| 525804 | Bohdíkov | Šumperk | Olomoucký kraj | 532 | 78 | 195 | 228 | 42.86 | 0 | 0 | 0.0 | 0 | 0.0 | 0 |
| 582352 | Sloup | Blansko | Jihomoravský kraj | 395 | 0 | 152 | 227 | 57.47 | 25 | 0 | 0.0 | 0 | 0.0 | 0 |
| 501476 | Dlouhá Loučka | Olomouc | Olomoucký kraj | 745 | 2 | 75 | 226 | 30.34 | 0 | 0 | 0.0 | 0 | 0.0 | 0 |
| 517607 | Rokytnice | Přerov | Olomoucký kraj | 579 | 0 | 4 | 226 | 39.03 | 0 | 0 | 0.0 | 0 | 0.0 | 0 |
| 553697 | Trmice | Ústí nad Labem | Ústecký kraj | 937 | 0 | 3 | 224 | 23.91 | 19 | 10 | 1.07 | 0 | 0.0 | 31 |
| 533700 | Starý Kolín | Kolín | Středočeský kraj | 615 | 0 | 10 | 213 | 34.63 | 0 | 0 | 0.0 | 0 | 0.0 | 0 |
| 577731 | Svitavy | Svitavy | Pardubický kraj | 3717 | 14 | 14 | 212 | 5.7 | 11 | 0 | 0.0 | 0 | 0.0 | 0 |
| 558419 | Držovice | Prostějov | Olomoucký kraj | 648 | 0 | 6 | 211 | 32.61 | 0 | 0 | 0.0 | 0 | 0.0 | 0 |
