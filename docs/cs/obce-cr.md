# Seznam obcí ČR s kódy (CSV, JSON)

Všechny obce České republiky s kódem obce (RÚIAN = ČSÚ, LAU 2), statusem, okresem, krajem, obcí s rozšířenou působností, PSČ, počtem adres a souřadnicemi středu.

Česko má 6 258 obcí: 27 statutárních měst včetně hlavního města Prahy, 583 dalších měst, 234 městysů a 4 vojenské újezdy.

V obcích je evidováno 3 022 397 adresních míst.

- **Stav dat:** září 2026
- **Řádků:** 6 258
- **Zdroj:** [ČÚZK (RÚIAN)](https://vdp.cuzk.gov.cz/)
- **Licence:** CC BY 4.0 (ČÚZK)
- **Jak citovat:** Zdroj: ČÚZK (RÚIAN); zpracoval czechdatasets.com, https://czechdatasets.com/otevrena-data/obce-cr
- **Ke stažení:** [CSV](https://czechdatasets.com/open/obce-cr.csv) · [JSON](https://czechdatasets.com/open/obce-cr.json) · [Markdown](https://czechdatasets.com/open/obce-cr.md)
- **Stránka tabulky:** https://czechdatasets.com/otevrena-data/obce-cr
- **Plná datová sada:** [RÚIAN s historií](https://czechdatasets.com/data/ruian)

Řazeno podle počtu adres od největší obce. Kód obce v RÚIAN je stejný jako kód obce ČSÚ (číselník CISOB).

## Sloupce

| Sloupec | Popis |
| --- | --- |
| `obec_kod` | Kód obce (RÚIAN, stejný jako kód obce ČSÚ) |
| `obec` | Název obce |
| `status` | Status obce: Obec, Město, Městys, Statutární město, Hlavní město, Vojenský újezd |
| `okres` | Okres |
| `okres_kod` | Kód okresu (RÚIAN) |
| `kraj` | Kraj |
| `kraj_kod` | Kód kraje (RÚIAN) |
| `orp` | Obec s rozšířenou působností (správní obvod) |
| `pou` | Obec s pověřeným obecním úřadem |
| `lau` | Kód LAU 2 (CZ + okres + kód obce) |
| `psc` | PSČ v obci, více hodnot odděluje středník |
| `pocet_adres` | Počet adresních míst |
| `lat` | Zeměpisná šířka (WGS84) |
| `lon` | Zeměpisná délka (WGS84) |

## Data

Prvních 100 z 6 258 řádků. Celá tabulka: https://czechdatasets.com/open/obce-cr.csv

| obec_kod | obec | status | okres | okres_kod | kraj | kraj_kod | orp | pou | lau | psc | pocet_adres | lat | lon |
| ---: | --- | --- | --- | ---: | --- | ---: | --- | --- | --- | --- | ---: | ---: | ---: |
| 554782 | Praha | Hlavní město | Hlavní město Praha |  | Hlavní město Praha | 19 | Hlavní město Praha | Hlavní město Praha | CZ0100554782 | 10000;10100;10200;10300;10400;10600;10700;10800;10900;11000;11101;11800;11900;12000;12800;13000;14000;14100;14200;14300;14700;14800;14900;15000;15200;15300;15400;15500;15521;15531;15600;15800;15900;16000;16100;16200;16300;16400;16500;16900;17000;17100;18000;18100;18200;18400;18600;19000;19011;19012;19014;19015;19016;19017;19300;19600;19700;19800;19900;25226;25228 | 134676 | 50.084552 | 14.417781 |
| 582786 | Brno | Statutární město | Brno-město | 3702 | Jihomoravský kraj | 116 | Brno | Brno | CZ0642582786 | 60200;60300;61200;61300;61400;61500;61600;61700;61800;61900;62000;62100;62300;62400;62500;62700;62800;63400;63500;63600;63700;63800;63900;64100;64200;64300;64400;66442;66471;66481 | 62524 | 49.191859 | 16.611091 |
| 554821 | Ostrava | Statutární město | Ostrava-město | 3807 | Moravskoslezský kraj | 132 | Ostrava | Ostrava | CZ0806554821 | 70030;70200;70300;70800;70900;71000;71100;71200;71300;71500;71600;71700;71800;71900;72000;72100;72200;72300;72400;72525;72526;72527;72528;72529;73924;73932;73934 | 34079 | 49.834645 | 18.282043 |
| 554791 | Plzeň | Statutární město | Plzeň-město | 3405 | Plzeňský kraj | 43 | Plzeň | Plzeň | CZ0323554791 | 30100;31200;31600;31800;32100;32200;32300;32600 | 27587 | 49.747475 | 13.377587 |
| 585068 | Zlín | Statutární město | Zlín | 3705 | Zlínský kraj | 141 | Zlín | Zlín | CZ0724585068 | 76001;76005;76302;76311;76314;76351 | 18167 | 49.226653 | 17.666343 |
| 554804 | Ústí nad Labem | Statutární město | Ústí nad Labem | 3510 | Ústecký kraj | 60 | Ústí nad Labem | Ústí nad Labem | CZ0427554804 | 40001;40002;40003;40007;40010;40011;40302;40321;40322;40331;40340 | 16973 | 50.660488 | 14.040692 |
| 563889 | Liberec | Statutární město | Liberec | 3505 | Liberecký kraj | 78 | Liberec | Liberec | CZ0513563889 | 46001;46005;46006;46007;46008;46010;46014;46015;46311;46312 | 16341 | 50.769997 | 15.058449 |
| 569810 | Hradec Králové | Statutární město | Hradec Králové | 3602 | Královéhradecký kraj | 86 | Hradec Králové | Hradec Králové | CZ0521569810 | 50002;50003;50004;50006;50008;50009;50011;50012;50301;50302;50311;50321;50332;50341 | 16316 | 50.209228 | 15.832768 |
| 500496 | Olomouc | Statutární město | Olomouc | 3805 | Olomoucký kraj | 124 | Olomouc | Olomouc | CZ0712500496 | 77900;78301;78335 | 14782 | 49.593867 | 17.250875 |
| 586846 | Jihlava | Statutární město | Jihlava | 3707 | Kraj Vysočina | 108 | Jihlava | Jihlava | CZ0632586846 | 58601 | 13232 | 49.3961 | 15.591244 |
| 544256 | České Budějovice | Statutární město | České Budějovice | 3301 | Jihočeský kraj | 35 | České Budějovice | České Budějovice | CZ0311544256 | 37001;37004;37005;37006;37007;37008;37010;37011 | 13181 | 48.974469 | 14.47434 |
| 555134 | Pardubice | Statutární město | Pardubice | 3606 | Pardubický kraj | 94 | Pardubice | Pardubice | CZ0532555134 | 53002;53003;53006;53009;53012;53301;53333;53351;53352;53353 | 12911 | 50.038538 | 15.780205 |
| 555088 | Havířov | Statutární město | Karviná | 3803 | Moravskoslezský kraj | 132 | Havířov | Havířov | CZ0803555088 | 73564;73601 | 11002 | 49.779844 | 18.436879 |
| 562335 | Děčín | Statutární město | Děčín | 3502 | Ústecký kraj | 60 | Děčín | Děčín | CZ0421562335 | 40502;40505;40711 | 10481 | 50.782153 | 14.214781 |
| 532053 | Kladno | Statutární město | Kladno | 3203 | Středočeský kraj | 27 | Kladno | Kladno | CZ0203532053 | 27201;27203;27204;27309 | 9722 | 50.147336 | 14.10285 |
| 505927 | Opava | Statutární město | Opava | 3806 | Moravskoslezský kraj | 132 | Opava | Opava | CZ0805505927 | 74601;74705;74706;74707;74728;74770;74773;74795 | 9030 | 49.938663 | 17.902569 |
| 552046 | Tábor | Město | Tábor | 3308 | Jihočeský kraj | 35 | Tábor | Tábor | CZ0317552046 | 39001;39002;39003;39005;39131;39137;39156 | 8383 | 49.414413 | 14.657803 |
| 598917 | Karviná | Statutární město | Karviná | 3803 | Moravskoslezský kraj | 132 | Karviná | Karviná | CZ0803598917 | 73301;73401;73503;73506 | 8244 | 49.854003 | 18.541689 |
| 593711 | Znojmo | Město | Znojmo | 3713 | Jihomoravský kraj | 116 | Znojmo | Znojmo | CZ0647593711 | 66902;66904;67128;67151;67181;67182 | 8009 | 48.855499 | 16.048797 |
| 589250 | Prostějov | Statutární město | Prostějov | 3709 | Olomoucký kraj | 124 | Prostějov | Prostějov | CZ0713589250 | 79601;79603;79604;79811 | 7761 | 49.471876 | 17.111845 |
| 563510 | Jablonec nad Nisou | Statutární město | Jablonec nad Nisou | 3504 | Liberecký kraj | 78 | Jablonec nad Nisou | Jablonec nad Nisou | CZ0512563510 | 46601;46602;46604;46605;46606;46801;46804 | 7458 | 50.724308 | 15.171077 |
| 554481 | Cheb | Město | Cheb | 3402 | Karlovarský kraj | 51 | Cheb | Cheb | CZ0411554481 | 35002;35134 | 7403 | 50.079635 | 12.373921 |
| 598003 | Frýdek-Místek | Statutární město | Frýdek-Místek | 3802 | Moravskoslezský kraj | 132 | Frýdek-Místek | Frýdek-Místek | CZ0802598003 | 73801;73942 | 7329 | 49.68537 | 18.348383 |
| 511382 | Přerov | Statutární město | Přerov | 3808 | Olomoucký kraj | 124 | Přerov | Přerov | CZ0714511382 | 75002;75124;75127 | 7104 | 49.455108 | 17.450908 |
| 567027 | Most | Statutární město | Most | 3508 | Ústecký kraj | 60 | Most | Most | CZ0425567027 | 43401;43502 | 6998 | 50.503007 | 13.636174 |
| 598810 | Třinec | Statutární město | Frýdek-Místek | 3802 | Moravskoslezský kraj | 132 | Třinec | Třinec | CZ0802598810 | 73955;73961;73994 | 6682 | 49.677637 | 18.670788 |
| 567442 | Teplice | Statutární město | Teplice | 3509 | Ústecký kraj | 60 | Teplice | Teplice | CZ0426567442 | 41501;41503;41510 | 6574 | 50.640398 | 13.824507 |
| 590266 | Třebíč | Město | Třebíč | 3710 | Kraj Vysočina | 108 | Třebíč | Třebíč | CZ0634590266 | 67401 | 6569 | 49.214923 | 15.881656 |
| 554961 | Karlovy Vary | Statutární město | Karlovy Vary | 3403 | Karlovarský kraj | 51 | Karlovy Vary | Karlovy Vary | CZ0412554961 | 36001;36004;36005;36006;36007;36010;36017;36018;36464 | 6511 | 50.221317 | 12.886072 |
| 586021 | Hodonín | Město | Hodonín | 3706 | Jihomoravský kraj | 116 | Hodonín | Hodonín | CZ0645586021 | 69501 | 6213 | 48.84893 | 17.132456 |
| 588296 | Kroměříž | Město | Kroměříž | 3708 | Zlínský kraj | 141 | Kroměříž | Kroměříž | CZ0721588296 | 76701 | 6183 | 49.29785 | 17.393124 |
| 592889 | Vyškov | Město | Vyškov | 3712 | Jihomoravský kraj | 116 | Vyškov | Vyškov | CZ0646592889 | 68201 | 5909 | 49.277466 | 16.998981 |
| 562971 | Chomutov | Statutární město | Chomutov | 3503 | Ústecký kraj | 60 | Chomutov | Chomutov | CZ0422562971 | 43001;43003;43004 | 5903 | 50.460476 | 13.417785 |
| 545881 | Jindřichův Hradec | Město | Jindřichův Hradec | 3303 | Jihočeský kraj | 35 | Jindřichův Hradec | Jindřichův Hradec | CZ0313545881 | 37701 | 5821 | 49.144045 | 15.003007 |
| 568414 | Havlíčkův Brod | Město | Havlíčkův Brod | 3601 | Kraj Vysočina | 108 | Havlíčkův Brod | Havlíčkův Brod | CZ0631568414 | 58001 | 5686 | 49.607849 | 15.580686 |
| 581283 | Blansko | Město | Blansko | 3701 | Jihomoravský kraj | 116 | Blansko | Blansko | CZ0641581283 | 67801;67903 | 5670 | 49.36313 | 16.643155 |
| 598933 | Český Těšín | Město | Karviná | 3803 | Moravskoslezský kraj | 132 | Český Těšín | Český Těšín | CZ0803598933 | 73562;73701 | 5579 | 49.746133 | 18.62613 |
| 592005 | Uherské Hradiště | Město | Uherské Hradiště | 3711 | Zlínský kraj | 141 | Uherské Hradiště | Uherské Hradiště | CZ0722592005 | 68601;68605;68606;68609 | 5435 | 49.069747 | 17.459696 |
| 573868 | Náchod | Město | Náchod | 3605 | Královéhradecký kraj | 86 | Náchod | Náchod | CZ0523573868 | 54701 | 5430 | 50.416704 | 16.162888 |
| 533165 | Kolín | Město | Kolín | 3204 | Středočeský kraj | 27 | Kolín | Kolín | CZ0204533165 | 28002 | 5320 | 50.028136 | 15.200567 |
| 535419 | Mladá Boleslav | Statutární město | Mladá Boleslav | 3207 | Středočeský kraj | 27 | Mladá Boleslav | Mladá Boleslav | CZ0207535419 | 29301 | 5316 | 50.411351 | 14.903184 |
| 584291 | Břeclav | Město | Břeclav | 3704 | Jihomoravský kraj | 116 | Břeclav | Břeclav | CZ0644584291 | 69002;69003;69006;69141;69146 | 5234 | 48.758963 | 16.882041 |
| 547492 | Pelhřimov | Město | Pelhřimov | 3304 | Kraj Vysočina | 108 | Pelhřimov | Pelhřimov | CZ0633547492 | 39301 | 5127 | 49.431337 | 15.223356 |
| 538728 | Říčany | Město | Praha-východ | 3209 | Středočeský kraj | 27 | Říčany | Říčany | CZ0209538728 | 25101 | 5072 | 49.991676 | 14.654269 |
| 539911 | Příbram | Město | Příbram | 3211 | Středočeský kraj | 27 | Příbram | Příbram | CZ020B539911 | 26101;26231;26241 | 4994 | 49.689878 | 14.010424 |
| 599051 | Bohumín | Město | Karviná | 3803 | Moravskoslezský kraj | 132 | Bohumín | Bohumín | CZ0803599051 | 73531;73551;73552;73581 | 4981 | 49.904106 | 18.357545 |
| 579025 | Trutnov | Město | Trutnov | 3610 | Královéhradecký kraj | 86 | Trutnov | Trutnov | CZ0525579025 | 54101;54102;54103;54232 | 4967 | 50.561007 | 15.912703 |
| 555771 | Klatovy | Město | Klatovy | 3404 | Plzeňský kraj | 43 | Klatovy | Klatovy | CZ0322555771 | 33901 | 4935 | 49.39552 | 13.295054 |
| 561380 | Česká Lípa | Město | Česká Lípa | 3501 | Liberecký kraj | 78 | Česká Lípa | Česká Lípa | CZ0511561380 | 47001;47006;47111;47121 | 4830 | 50.685513 | 14.537641 |
| 549240 | Písek | Město | Písek | 3305 | Jihočeský kraj | 35 | Písek | Písek | CZ0314549240 | 39701 | 4751 | 49.308795 | 14.147502 |
| 592731 | Uherský Brod | Město | Uherské Hradiště | 3711 | Zlínský kraj | 141 | Uherský Brod | Uherský Brod | CZ0722592731 | 68734;68801 | 4731 | 49.025128 | 17.647162 |
| 567256 | Litvínov | Město | Most | 3508 | Ústecký kraj | 60 | Litvínov | Litvínov | CZ0425567256 | 43542;43601;43603 | 4728 | 50.600687 | 13.61111 |
| 566985 | Žatec | Město | Louny | 3507 | Ústecký kraj | 60 | Žatec | Žatec | CZ0424566985 | 43801 | 4655 | 50.327169 | 13.545772 |
| 533955 | Kutná Hora | Město | Kutná Hora | 3205 | Středočeský kraj | 27 | Kutná Hora | Kutná Hora | CZ0205533955 | 28401;28403;28404 | 4455 | 49.948388 | 15.268164 |
| 571164 | Chrudim | Město | Chrudim | 3603 | Pardubický kraj | 94 | Chrudim | Chrudim | CZ0531571164 | 53701;53703;53705;53821;53831 | 4385 | 49.951092 | 15.795575 |
| 580031 | Česká Třebová | Město | Ústí nad Orlicí | 3611 | Pardubický kraj | 94 | Česká Třebová | Česká Třebová | CZ0534580031 | 56002 | 4377 | 49.901884 | 16.447279 |
| 538094 | Brandýs nad Labem-Stará Boleslav | Město | Praha-východ | 3209 | Středočeský kraj | 27 | Brandýs nad Labem-Stará Boleslav | Brandýs nad Labem-Stará Boleslav | CZ0209538094 | 25001 | 4348 | 50.187091 | 14.663256 |
| 534676 | Mělník | Město | Mělník | 3206 | Středočeský kraj | 27 | Mělník | Mělník | CZ0206534676 | 27601;27741 | 4331 | 50.350497 | 14.474107 |
| 583120 | Ivančice | Město | Brno-venkov | 3703 | Jihomoravský kraj | 116 | Ivančice | Ivančice | CZ0643583120 | 66491 | 4161 | 49.101445 | 16.377517 |
| 563102 | Kadaň | Město | Chomutov | 3503 | Ústecký kraj | 60 | Kadaň | Kadaň | CZ0422563102 | 43201 | 4155 | 50.375984 | 13.271307 |
| 597007 | Velké Meziříčí | Město | Žďár nad Sázavou | 3714 | Kraj Vysočina | 108 | Velké Meziříčí | Velké Meziříčí | CZ0635597007 | 59401 | 4117 | 49.355217 | 16.012242 |
| 545058 | Valašské Meziříčí | Město | Vsetín | 3810 | Zlínský kraj | 141 | Valašské Meziříčí | Valašské Meziříčí | CZ0723545058 | 75642;75701 | 4110 | 49.471806 | 17.971135 |
| 531057 | Beroun | Město | Beroun | 3202 | Středočeský kraj | 27 | Beroun | Beroun | CZ0202531057 | 26601 | 4085 | 49.963824 | 14.071996 |
| 579203 | Dvůr Králové nad Labem | Město | Trutnov | 3610 | Královéhradecký kraj | 86 | Dvůr Králové nad Labem | Dvůr Králové nad Labem | CZ0525579203 | 54401;54404 | 4026 | 50.431722 | 15.814021 |
| 565971 | Louny | Město | Louny | 3507 | Ústecký kraj | 60 | Louny | Louny | CZ0424565971 | 44001 | 3909 | 50.356989 | 13.796674 |
| 599069 | Orlová | Město | Karviná | 3803 | Moravskoslezský kraj | 132 | Orlová | Orlová | CZ0803599069 | 73511;73514 | 3843 | 49.845266 | 18.430109 |
| 541630 | Vsetín | Město | Vsetín | 3810 | Zlínský kraj | 141 | Vsetín | Vsetín | CZ0723541630 | 75501 | 3778 | 49.33871 | 17.996199 |
| 554499 | Aš | Město | Cheb | 3402 | Karlovarský kraj | 51 | Aš | Aš | CZ0411554499 | 35201 | 3747 | 50.223868 | 12.194991 |
| 597520 | Krnov | Město | Bruntál | 3801 | Moravskoslezský kraj | 132 | Krnov | Krnov | CZ0801597520 | 79401 | 3743 | 50.089668 | 17.703846 |
| 547999 | Humpolec | Město | Pelhřimov | 3304 | Kraj Vysočina | 108 | Humpolec | Humpolec | CZ0633547999 | 39601 | 3721 | 49.541522 | 15.359318 |
| 577731 | Svitavy | Město | Svitavy | 3609 | Pardubický kraj | 94 | Svitavy | Svitavy | CZ0533577731 | 56802 | 3717 | 49.755937 | 16.468291 |
| 577626 | Turnov | Město | Semily | 3608 | Liberecký kraj | 78 | Turnov | Turnov | CZ0514577626 | 51101 | 3712 | 50.587285 | 15.156801 |
| 505188 | Šternberk | Město | Olomouc | 3805 | Olomoucký kraj | 124 | Šternberk | Šternberk | CZ0712505188 | 78501 | 3671 | 49.730443 | 17.298887 |
| 532819 | Slaný | Město | Kladno | 3203 | Středočeský kraj | 27 | Slaný | Slaný | CZ0203532819 | 27379;27401 | 3641 | 50.230458 | 14.086934 |
| 564567 | Litoměřice | Město | Litoměřice | 3506 | Ústecký kraj | 60 | Litoměřice | Litoměřice | CZ0423564567 | 41201 | 3619 | 50.533478 | 14.131802 |
| 537683 | Poděbrady | Město | Nymburk | 3208 | Středočeský kraj | 27 | Poděbrady | Poděbrady | CZ0208537683 | 29001 | 3578 | 50.142419 | 15.118811 |
| 513750 | Hranice | Město | Přerov | 3808 | Olomoucký kraj | 124 | Hranice | Hranice | CZ0714513750 | 75301;75354;75361 | 3548 | 49.547965 | 17.734698 |
| 599191 | Nový Jičín | Město | Nový Jičín | 3804 | Moravskoslezský kraj | 132 | Nový Jičín | Nový Jičín | CZ0804599191 | 74101 | 3483 | 49.594377 | 18.010282 |
| 585599 | Otrokovice | Město | Zlín | 3705 | Zlínský kraj | 141 | Otrokovice | Otrokovice | CZ0724585599 | 76502 | 3430 | 49.209915 | 17.530776 |
| 539139 | Černošice | Město | Praha-západ | 3210 | Středočeský kraj | 27 | Černošice | Černošice | CZ020A539139 | 25226;25228 | 3393 | 49.96008 | 14.319794 |
| 563099 | Jirkov | Město | Chomutov | 3503 | Ústecký kraj | 60 | Chomutov | Jirkov | CZ0422563099 | 43111 | 3373 | 50.499793 | 13.447689 |
| 583251 | Kuřim | Město | Brno-venkov | 3703 | Jihomoravský kraj | 116 | Kuřim | Kuřim | CZ0643583251 | 66434 | 3370 | 49.298517 | 16.53144 |
| 505587 | Uničov | Město | Olomouc | 3805 | Olomoucký kraj | 124 | Uničov | Uničov | CZ0712505587 | 78391 | 3370 | 49.770915 | 17.121436 |
| 550787 | Strakonice | Město | Strakonice | 3307 | Jihočeský kraj | 35 | Strakonice | Strakonice | CZ0316550787 | 38601 | 3361 | 49.261407 | 13.90237 |
| 567639 | Krupka | Město | Teplice | 3509 | Ústecký kraj | 60 | Teplice | Krupka | CZ0426567639 | 40317;41741;41742 | 3357 | 50.68449 | 13.85815 |
| 599565 | Kopřivnice | Město | Nový Jičín | 3804 | Moravskoslezský kraj | 132 | Kopřivnice | Kopřivnice | CZ0804599565 | 74221 | 3324 | 49.599474 | 18.144808 |
| 581372 | Boskovice | Město | Blansko | 3701 | Jihomoravský kraj | 116 | Boskovice | Boskovice | CZ0641581372 | 67901;68001 | 3311 | 49.487508 | 16.659974 |
| 567451 | Bílina | Město | Teplice | 3509 | Ústecký kraj | 60 | Bílina | Bílina | CZ0426567451 | 41801 | 3294 | 50.548542 | 13.775346 |
| 598143 | Frýdlant nad Ostravicí | Město | Frýdek-Místek | 3802 | Moravskoslezský kraj | 132 | Frýdlant nad Ostravicí | Frýdlant nad Ostravicí | CZ0802598143 | 73911 | 3274 | 49.592806 | 18.359673 |
| 596230 | Nové Město na Moravě | Město | Žďár nad Sázavou | 3714 | Kraj Vysočina | 108 | Nové Město na Moravě | Nové Město na Moravě | CZ0635596230 | 59231 | 3272 | 49.561443 | 16.074182 |
| 586307 | Kyjov | Město | Hodonín | 3706 | Jihomoravský kraj | 116 | Kyjov | Kyjov | CZ0645586307 | 69655;69701 | 3267 | 49.010173 | 17.122538 |
| 523704 | Šumperk | Město | Šumperk | 3809 | Olomoucký kraj | 124 | Šumperk | Šumperk | CZ0715523704 | 78701 | 3263 | 49.965284 | 16.970607 |
| 571393 | Hlinsko | Město | Chrudim | 3603 | Pardubický kraj | 94 | Hlinsko | Hlinsko | CZ0531571393 | 53901;53962 | 3261 | 49.762131 | 15.907556 |
| 544841 | Rožnov pod Radhoštěm | Město | Vsetín | 3810 | Zlínský kraj | 141 | Rožnov pod Radhoštěm | Rožnov pod Radhoštěm | CZ0723544841 | 75661 | 3252 | 49.458529 | 18.143029 |
| 562882 | Varnsdorf | Město | Děčín | 3502 | Ústecký kraj | 60 | Varnsdorf | Varnsdorf | CZ0421562882 | 40747;40752 | 3245 | 50.911544 | 14.618235 |
| 541656 | Rakovník | Město | Rakovník | 3212 | Středočeský kraj | 27 | Rakovník | Rakovník | CZ020C541656 | 26901;27036 | 3244 | 50.103701 | 13.733399 |
| 595209 | Žďár nad Sázavou | Město | Žďár nad Sázavou | 3714 | Kraj Vysočina | 108 | Žďár nad Sázavou | Žďár nad Sázavou | CZ0635595209 | 59101;59102 | 3157 | 49.562633 | 15.93924 |
| 565555 | Roudnice nad Labem | Město | Litoměřice | 3506 | Ústecký kraj | 60 | Roudnice nad Labem | Roudnice nad Labem | CZ0423565555 | 41301 | 3135 | 50.425283 | 14.261749 |
| 534951 | Kralupy nad Vltavou | Město | Mělník | 3206 | Středočeský kraj | 27 | Kralupy nad Vltavou | Kralupy nad Vltavou | CZ0206534951 | 27801 | 3131 | 50.241071 | 14.311494 |
| 563129 | Klášterec nad Ohří | Město | Chomutov | 3503 | Ústecký kraj | 60 | Kadaň | Klášterec nad Ohří | CZ0422563129 | 43151 | 3130 | 50.384452 | 13.171277 |
