# Czech open data tables

35 open tables about the Czech Republic, built from official open data: municipalities, postcodes and territorial units (RÚIAN), companies, data boxes, schools, healthcare providers, pharmacies, medicines, election results, wages, population and municipal statistics. 53,124 rows in total, as UTF-8 CSV with documented columns.

The tables are published and kept up to date at **[czechdatasets.com/en/otevrena-data](https://czechdatasets.com/en/otevrena-data)** (Czech: [czechdatasets.com/otevrena-data](https://czechdatasets.com/otevrena-data)). This repository is a mirror for people and tools that prefer Git, a raw file URL or a data package.

- **Format:** UTF-8 CSV, comma separated, header row, `.` as decimal point. Column names are Czech without diacritics; every column is described in English and Czech in `docs/`.
- **Sources:** Czech public authorities (ČÚZK, Czech Statistical Office, Digital and Information Agency, Ministry of Labour, Ministry of Education, SÚKL, ÚZIS, Czech National Bank and others). Each table names its source and the date the data refers to.
- **Machine-readable description:** [`datapackage.json`](datapackage.json) (Frictionless Data Package) and https://czechdatasets.com/open/index.json.
- **Free to use:** no registration and no API key. Licences differ by table, see [LICENSE.md](LICENSE.md).

## Tables

### RÚIAN with history ([full dataset](https://czechdatasets.com/en/data/ruian))

| Table | Rows | Data as of | Source | Licence | Files |
| --- | ---: | --- | --- | --- | --- |
| [List of Czech municipalities with codes (CSV, JSON)](https://czechdatasets.com/en/otevrena-data/obce-cr) | 6,258 | September 2026 | [ČÚZK, the Czech Office for Surveying, Mapping and Cadastre (RÚIAN register)](https://vdp.cuzk.gov.cz/) | [CC BY 4.0 (ČÚZK)](https://creativecommons.org/licenses/by/4.0/deed.cs) | [CSV](data/obce-cr.csv) · [columns](docs/en/obce-cr.md) |
| [How many municipalities, cadastral areas, streets and addresses are in the Czech Republic](https://czechdatasets.com/en/otevrena-data/pocty-uzemnich-prvku) | 14 | September 2026 | [ČÚZK, the Czech Office for Surveying, Mapping and Cadastre (RÚIAN register)](https://vdp.cuzk.gov.cz/) | [CC BY 4.0 (ČÚZK)](https://creativecommons.org/licenses/by/4.0/deed.cs) | [CSV](data/pocty-uzemnich-prvku.csv) · [columns](docs/en/pocty-uzemnich-prvku.md) |
| [Czech postcodes (PSČ) by municipality (CSV)](https://czechdatasets.com/en/otevrena-data/psc) | 7,846 | September 2026 | [ČÚZK, the Czech Office for Surveying, Mapping and Cadastre (RÚIAN register)](https://vdp.cuzk.gov.cz/) | [CC BY 4.0 (ČÚZK)](https://creativecommons.org/licenses/by/4.0/deed.cs) | [CSV](data/psc.csv) · [columns](docs/en/psc.md) |

### ČSÚ code lists ([full dataset](https://czechdatasets.com/en/data/csu-ciselniky))

| Table | Rows | Data as of | Source | Licence | Files |
| --- | ---: | --- | --- | --- | --- |
| [Czech regions and districts with CZ-NUTS 3 and LAU 1 codes](https://czechdatasets.com/en/otevrena-data/kraje-a-okresy) | 91 | 11 November 2026 | [Czech Statistical Office (ČSÚ)](https://apl.czso.cz/iSMS/) | [CC BY 4.0 (ČSÚ)](https://csu.gov.cz/podminky_pro_vyuzivani_a_dalsi_zverejnovani_statistickych_udaju_csu) | [CSV](data/kraje-a-okresy.csv) · [columns](docs/en/kraje-a-okresy.md) |
| [CZ-NACE 2025 classification of economic activities: codes and names in Czech and English (CSV, JSON)](https://czechdatasets.com/en/otevrena-data/cz-nace-2025) | 1,803 | 11 November 2026 | [Czech Statistical Office (ČSÚ)](https://apl.czso.cz/iSMS/) | [CC BY 4.0 (ČSÚ)](https://csu.gov.cz/podminky_pro_vyuzivani_a_dalsi_zverejnovani_statistickych_udaju_csu) | [CSV](data/cz-nace-2025.csv) · [columns](docs/en/cz-nace-2025.md) |
| [Czech legal forms code list (112 = s.r.o. limited liability company, 121 = a.s. joint-stock company)](https://czechdatasets.com/en/otevrena-data/pravni-formy) | 118 | 11 November 2026 | [Czech Statistical Office (ČSÚ)](https://apl.czso.cz/iSMS/) | [CC BY 4.0 (ČSÚ)](https://csu.gov.cz/podminky_pro_vyuzivani_a_dalsi_zverejnovani_statistickych_udaju_csu) | [CSV](data/pravni-formy.csv) · [columns](docs/en/pravni-formy.md) |

### Address geocoder and autocomplete ([full dataset](https://czechdatasets.com/en/data/geokoder))

| Table | Rows | Data as of | Source | Licence | Files |
| --- | ---: | --- | --- | --- | --- |
| [Number of address points in the Czech Republic by district](https://czechdatasets.com/en/otevrena-data/adresy-podle-okresu) | 78 | September 2026 | [ČÚZK, the Czech Office for Surveying, Mapping and Cadastre (RÚIAN register)](https://vdp.cuzk.gov.cz/) | [CC BY 4.0 (ČÚZK)](https://cuzk.gov.cz/Predpisy/Podminky-poskytovani-prostor-dat-a-sitovych-sluzeb/Podminky-poskytovani-prostorovych-dat-CUZK.aspx) | [CSV](data/adresy-podle-okresu.csv) · [columns](docs/en/adresy-podle-okresu.md) |

### Address risks ([full dataset](https://czechdatasets.com/en/data/rizika-adres))

| Table | Rows | Data as of | Source | Licence | Files |
| --- | ---: | --- | --- | --- | --- |
| [Flood risk by municipality in the Czech Republic: share of addresses in the 100-year flood zone](https://czechdatasets.com/en/otevrena-data/rizika-podle-obci) | 6,258 | 11 November 2026 | [VÚV TGM, Czech Geological Survey, AOPK ČR, ČHMÚ and ČÚZK](https://heis.vuv.cz/isvs/zapluz) | [CC BY 4.0 (VÚV TGM, ČGS, AOPK ČR, ČHMÚ, ČÚZK), MŽP](https://creativecommons.org/licenses/by/4.0/deed.cs) | [CSV](data/rizika-podle-obci.csv) · [columns](docs/en/rizika-podle-obci.md) |

### Companies and organisations (RES) ([full dataset](https://czechdatasets.com/en/data/firmy))

| Table | Rows | Data as of | Source | Licence | Files |
| --- | ---: | --- | --- | --- | --- |
| [Number of companies in the Czech Republic by legal form](https://czechdatasets.com/en/otevrena-data/firmy-podle-pravni-formy) | 67 | 31 October 2026 | [Czech Statistical Office (Register of Economic Subjects)](https://csu.gov.cz/registr-ekonomickych-subjektu-otevrena-data-dokumentace) | [CC BY 4.0 (ČSÚ, ČÚZK)](https://csu.gov.cz/podminky_pro_vyuzivani_a_dalsi_zverejnovani_statistickych_udaju_csu) | [CSV](data/firmy-podle-pravni-formy.csv) · [columns](docs/en/firmy-podle-pravni-formy.md) |
| [Number of Czech companies by region and CZ-NACE industry section](https://czechdatasets.com/en/otevrena-data/firmy-podle-kraju-a-odvetvi) | 297 | 31 October 2026 | [Czech Statistical Office (Register of Economic Subjects)](https://csu.gov.cz/registr-ekonomickych-subjektu-otevrena-data-dokumentace) | [CC BY 4.0 (ČSÚ, ČÚZK)](https://csu.gov.cz/podminky_pro_vyuzivani_a_dalsi_zverejnovani_statistickych_udaju_csu) | [CSV](data/firmy-podle-kraju-a-odvetvi.csv) · [columns](docs/en/firmy-podle-kraju-a-odvetvi.md) |

### Data boxes ([full dataset](https://czechdatasets.com/en/data/datove-schranky))

| Table | Rows | Data as of | Source | Licence | Files |
| --- | ---: | --- | --- | --- | --- |
| [Number of Czech data boxes (datové schránky) by type](https://czechdatasets.com/en/otevrena-data/datove-schranky-podle-typu) | 5 | 9 November 2026 | [Digital and Information Agency of the Czech Republic (list of data boxes)](https://www.datovka.gov.cz/sds/welcome?part=opendata) | [Free use (NKOD), addresses CC BY 4.0](https://data.gov.cz/podmínky-užití/neobsahuje-autorská-díla/) | [CSV](data/datove-schranky-podle-typu.csv) · [columns](docs/en/datove-schranky-podle-typu.md) |
| [Data box IDs of Czech public authorities and municipalities (downloadable list)](https://czechdatasets.com/en/otevrena-data/datove-schranky-uradu) | 7,554 | 9 November 2026 | [Digital and Information Agency of the Czech Republic (list of data boxes)](https://www.datovka.gov.cz/sds/welcome?part=opendata) | [Free use (NKOD), addresses CC BY 4.0](https://data.gov.cz/podmínky-užití/neobsahuje-autorská-díla/) | [CSV](data/datove-schranky-uradu.csv) · [columns](docs/en/datove-schranky-uradu.md) |

### Job vacancies ([full dataset](https://czechdatasets.com/en/data/volna-mista))

| Table | Rows | Data as of | Source | Licence | Files |
| --- | ---: | --- | --- | --- | --- |
| [Job vacancies in the Czech Republic by region](https://czechdatasets.com/en/otevrena-data/volna-mista-podle-kraju) | 16 | 11 November 2026 | [Czech Ministry of Labour and Social Affairs and the Labour Office](https://data.mpsv.cz/web/data/volna-mista-za-celou-cr) | [Free use (NKOD); RES and RÚIAN CC BY 4.0](https://data.mpsv.cz/web/data/podminky-uziti) | [CSV](data/volna-mista-podle-kraju.csv) · [columns](docs/en/volna-mista-podle-kraju.md) |
| [Most in-demand occupations and offered wages in the Czech Republic (CZ-ISCO)](https://czechdatasets.com/en/otevrena-data/volna-mista-podle-profesi) | 518 | 11 November 2026 | [Czech Ministry of Labour and Social Affairs and the Labour Office](https://data.mpsv.cz/web/data/volna-mista-za-celou-cr) | [Free use (NKOD); RES and RÚIAN CC BY 4.0](https://data.mpsv.cz/web/data/podminky-uziti) | [CSV](data/volna-mista-podle-profesi.csv) · [columns](docs/en/volna-mista-podle-profesi.md) |

### Schools and school facilities ([full dataset](https://czechdatasets.com/en/data/skoly))

| Table | Rows | Data as of | Source | Licence | Files |
| --- | ---: | --- | --- | --- | --- |
| [Number of schools in the Czech Republic by region and type](https://czechdatasets.com/en/otevrena-data/skoly-podle-kraju) | 15 | 9 November 2026 | [Czech Ministry of Education (school register)](https://lkod-ftp.msmt.gov.cz/00022985/88a7c12b-6084-4e47-8b50-46097c6e683f/RSSZ-cela-CR.jsonld) | [Free use (NKOD), addresses CC BY 4.0](https://data.gov.cz/zdroj/datové-sady/00022985/1c063ba63b80cbb7b0e600dfcd9a47d9/distribuce/f3888446f0df12416de8d94a0cbb3e36/podmínky-užití) | [CSV](data/skoly-podle-kraju.csv) · [columns](docs/en/skoly-podle-kraju.md) |

### Medicinal products (SÚKL) ([full dataset](https://czechdatasets.com/en/data/sukl-leciva))

| Table | Rows | Data as of | Source | Licence | Files |
| --- | ---: | --- | --- | --- | --- |
| [Number of medicinal products in the Czech Republic by ATC group](https://czechdatasets.com/en/otevrena-data/leciva-podle-atc) | 110 | 1 November 2026 | [SÚKL, the Czech State Institute for Drug Control (medicinal products database)](https://opendata.sukl.cz/katalog-otevrenych-dat/databaze-lecivych-pripravku-dlp) | [SÚKL terms, commercial use allowed](https://opendata.sukl.cz/podminky-uziti-otevrenych-dat) | [CSV](data/leciva-podle-atc.csv) · [columns](docs/en/leciva-podle-atc.md) |

### Medicine shortages and availability ([full dataset](https://czechdatasets.com/en/data/sukl-vypadky))

| Table | Rows | Data as of | Source | Licence | Files |
| --- | ---: | --- | --- | --- | --- |
| [Drug shortages in the Czech Republic by year: supply interruptions and their length](https://czechdatasets.com/en/otevrena-data/vypadky-leku-podle-let) | 22 | 9 November 2026 | [SÚKL, the Czech State Institute for Drug Control (supply reports)](https://opendata.sukl.gov.cz/katalog-otevrenych-dat/hlaseni-o-uvedeni-preruseni-ukonceni-obnoveni-dodavek-leciveho-pripravku-na-trh) | [SÚKL terms, commercial use allowed](https://opendata.sukl.gov.cz/podminky-uziti-otevrenych-dat) | [CSV](data/vypadky-leku-podle-let.csv) · [columns](docs/en/vypadky-leku-podle-let.md) |
| [Currently unavailable medicines in the Czech Republic by ATC group](https://czechdatasets.com/en/otevrena-data/nedostupne-leky-podle-atc) | 14 | 9 November 2026 | [SÚKL, the Czech State Institute for Drug Control (supply reports)](https://opendata.sukl.gov.cz/katalog-otevrenych-dat/hlaseni-o-uvedeni-preruseni-ukonceni-obnoveni-dodavek-leciveho-pripravku-na-trh) | [SÚKL terms, commercial use allowed](https://opendata.sukl.gov.cz/podminky-uziti-otevrenych-dat) | [CSV](data/nedostupne-leky-podle-atc.csv) · [columns](docs/en/nedostupne-leky-podle-atc.md) |

### Pharmacies with opening hours and GPS ([full dataset](https://czechdatasets.com/en/data/lekarny))

| Table | Rows | Data as of | Source | Licence | Files |
| --- | ---: | --- | --- | --- | --- |
| [How many pharmacies are in the Czech Republic: pharmacies by district and region](https://czechdatasets.com/en/otevrena-data/lekarny-podle-okresu) | 78 | 1 November 2026 | [SÚKL, the Czech State Institute for Drug Control (list of pharmacies)](https://opendata.sukl.gov.cz/katalog-otevrenych-dat/seznam-lekaren) | [SÚKL terms, commercial use allowed; addresses CC BY 4.0 (ČÚZK)](https://opendata.sukl.gov.cz/podminky-uziti-otevrenych-dat) | [CSV](data/lekarny-podle-okresu.csv) · [columns](docs/en/lekarny-podle-okresu.md) |

### Healthcare facilities (NRPZS) ([full dataset](https://czechdatasets.com/en/data/poskytovatele-zdravotni-pece))

| Table | Rows | Data as of | Source | Licence | Files |
| --- | ---: | --- | --- | --- | --- |
| [Number of GP, dental and paediatric practices and hospitals by Czech district](https://czechdatasets.com/en/otevrena-data/ordinace-podle-okresu) | 78 | 1 November 2026 | [ÚZIS ČR (National Register of Healthcare Providers)](https://datanzis.uzis.gov.cz/data/NR-01-NRPZS/NR-01-06/Otevrena-data-NR-01-06-nrpzs-mista-poskytovani-zdravotnich-sluzeb.csv) | [CC BY 4.0 (ÚZIS, ČÚZK)](https://creativecommons.org/licenses/by/4.0/) | [CSV](data/ordinace-podle-okresu.csv) · [columns](docs/en/ordinace-podle-okresu.md) |
| [List of hospitals in the Czech Republic with location and GPS coordinates](https://czechdatasets.com/en/otevrena-data/nemocnice) | 138 | 1 November 2026 | [ÚZIS ČR (National Register of Healthcare Providers)](https://datanzis.uzis.gov.cz/data/NR-01-NRPZS/NR-01-06/Otevrena-data-NR-01-06-nrpzs-mista-poskytovani-zdravotnich-sluzeb.csv) | [CC BY 4.0 (ÚZIS, ČÚZK)](https://creativecommons.org/licenses/by/4.0/) | [CSV](data/nemocnice.csv) · [columns](docs/en/nemocnice.md) |

### Election results 1996–2026 ([full dataset](https://czechdatasets.com/en/data/volby))

| Table | Rows | Data as of | Source | Licence | Files |
| --- | ---: | --- | --- | --- | --- |
| [Voter turnout in Czech elections since 1996: overview of all elections](https://czechdatasets.com/en/otevrena-data/volby-prehled) | 84 | 17 October 2026 | [Czech Statistical Office (volby.gov.cz)](https://www.volby.cz/opendata/opendata.htm) | [CC BY 4.0 (ČSÚ, ČÚZK)](https://csu.gov.cz/podminky_pro_vyuzivani_a_dalsi_zverejnovani_statistickych_udaju_csu) | [CSV](data/volby-prehled.csv) · [columns](docs/en/volby-prehled.md) |
| [Czech parliamentary election 2025: results by region](https://czechdatasets.com/en/otevrena-data/volby-ps-2025-kraje) | 339 | 17 October 2026 | [Czech Statistical Office (volby.gov.cz)](https://www.volby.cz/opendata/opendata.htm) | [CC BY 4.0 (ČSÚ, ČÚZK)](https://csu.gov.cz/podminky_pro_vyuzivani_a_dalsi_zverejnovani_statistickych_udaju_csu) | [CSV](data/volby-ps-2025-kraje.csv) · [columns](docs/en/volby-ps-2025-kraje.md) |
| [Czech parliamentary election 2025: results by municipality (CSV)](https://czechdatasets.com/en/otevrena-data/volby-ps-2025-obce) | 6,254 | 17 October 2026 | [Czech Statistical Office (volby.gov.cz)](https://www.volby.cz/opendata/opendata.htm) | [CC BY 4.0 (ČSÚ, ČÚZK)](https://csu.gov.cz/podminky_pro_vyuzivani_a_dalsi_zverejnovani_statistickych_udaju_csu) | [CSV](data/volby-ps-2025-obce.csv) · [columns](docs/en/volby-ps-2025-obce.md) |

### Population of municipalities 2000–2026 ([full dataset](https://czechdatasets.com/en/data/csu-obyvatelstvo))

| Table | Rows | Data as of | Source | Licence | Files |
| --- | ---: | --- | --- | --- | --- |
| [Population of Czech municipalities on 1 January 2026 (CSV)](https://czechdatasets.com/en/otevrena-data/obyvatelstvo-obci-2026) | 6,258 | 1 January 2026 | [Czech Statistical Office (ČSÚ)](https://data.csu.gov.cz/datastat/info/SADA/OBY02E) | [CC BY 4.0 (ČSÚ)](https://csu.gov.cz/podminky_pro_vyuzivani_a_dalsi_zverejnovani_statistickych_udaju_csu) | [CSV](data/obyvatelstvo-obci-2026.csv) · [columns](docs/en/obyvatelstvo-obci-2026.md) |
| [Population of the Czech Republic and its regions 2000–2026](https://czechdatasets.com/en/otevrena-data/obyvatelstvo-kraju) | 405 | 1 January 2026 | [Czech Statistical Office (ČSÚ)](https://data.csu.gov.cz/datastat/info/SADA/OBY02E) | [CC BY 4.0 (ČSÚ)](https://csu.gov.cz/podminky_pro_vyuzivani_a_dalsi_zverejnovani_statistickych_udaju_csu) | [CSV](data/obyvatelstvo-kraju.csv) · [columns](docs/en/obyvatelstvo-kraju.md) |

### Wages by region and industry ([full dataset](https://czechdatasets.com/en/data/mzdy))

| Table | Rows | Data as of | Source | Licence | Files |
| --- | ---: | --- | --- | --- | --- |
| [Average wage in the Czech Republic by region, Q2 2026](https://czechdatasets.com/en/otevrena-data/mzdy-podle-kraju) | 30 | 30 June 2026 | [Czech Statistical Office (ČSÚ)](https://data.csu.gov.cz/datastat/info/SADA/MZDQ1) | [CC BY 4.0 (ČSÚ)](https://csu.gov.cz/podminky_pro_vyuzivani_a_dalsi_zverejnovani_statistickych_udaju_csu) | [CSV](data/mzdy-podle-kraju.csv) · [columns](docs/en/mzdy-podle-kraju.md) |
| [Average wage in the Czech Republic by industry (CZ-NACE), Q2 2026](https://czechdatasets.com/en/otevrena-data/mzdy-podle-odvetvi) | 40 | 30 June 2026 | [Czech Statistical Office (ČSÚ)](https://data.csu.gov.cz/datastat/info/SADA/MZDQ1) | [CC BY 4.0 (ČSÚ)](https://csu.gov.cz/podminky_pro_vyuzivani_a_dalsi_zverejnovani_statistickych_udaju_csu) | [CSV](data/mzdy-podle-odvetvi.csv) · [columns](docs/en/mzdy-podle-odvetvi.md) |
| [Average wage in the Czech Republic, quarterly since 2000](https://czechdatasets.com/en/otevrena-data/mzdy-cesko-ctvrtletne) | 106 | 30 June 2026 | [Czech Statistical Office (ČSÚ)](https://data.csu.gov.cz/datastat/info/SADA/MZDQ1) | [CC BY 4.0 (ČSÚ)](https://csu.gov.cz/podminky_pro_vyuzivani_a_dalsi_zverejnovani_statistickych_udaju_csu) | [CSV](data/mzdy-cesko-ctvrtletne.csv) · [columns](docs/en/mzdy-cesko-ctvrtletne.md) |

### Municipalities in numbers 2000–2025 ([full dataset](https://czechdatasets.com/en/data/obce-v-cislech))

| Table | Rows | Data as of | Source | Licence | Files |
| --- | ---: | --- | --- | --- | --- |
| [Indicator list of Czech municipal statistics (MOS)](https://czechdatasets.com/en/otevrena-data/ukazatele-obci) | 800 | 22 July 2026 | [Czech Statistical Office (municipal statistics, MOS)](https://csu.gov.cz/produkty/databaze-mos-otevrena-data) | [CC BY 4.0 (ČSÚ, ČÚZK)](https://csu.gov.cz/podminky_pro_vyuzivani_a_dalsi_zverejnovani_statistickych_udaju_csu) | [CSV](data/ukazatele-obci.csv) · [columns](docs/en/ukazatele-obci.md) |
| [Czech municipalities in figures: area, population, unemployment, schools](https://czechdatasets.com/en/otevrena-data/obce-zakladni-ukazatele) | 6,258 | 22 July 2026 | [Czech Statistical Office (municipal statistics, MOS)](https://csu.gov.cz/produkty/databaze-mos-otevrena-data) | [CC BY 4.0 (ČSÚ, ČÚZK)](https://csu.gov.cz/podminky_pro_vyuzivani_a_dalsi_zverejnovani_statistickych_udaju_csu) | [CSV](data/obce-zakladni-ukazatele.csv) · [columns](docs/en/obce-zakladni-ukazatele.md) |

### Free bundle

| Table | Rows | Data as of | Source | Licence | Files |
| --- | ---: | --- | --- | --- | --- |
| [Czech bank codes: Czech National Bank code list (CSV, JSON)](https://czechdatasets.com/en/otevrena-data/kody-bank) | 47 | 9 November 2026 | [Czech National Bank (ČNB)](https://www.cnb.cz/cs/platebni-styk/ucty-kody-bank/) | Czech National Bank website terms: may be redistributed with the credit “Source: ČNB (Czech National Bank)”; content must not be altered | [CSV](data/kody-bank.csv) · [columns](docs/en/kody-bank.md) |
| [Czech National Bank repo rate: history of changes since 1995](https://czechdatasets.com/en/otevrena-data/repo-sazba-cnb) | 118 | 9 November 2026 | [Czech National Bank (ČNB)](https://www.cnb.cz/cs/casto-kladene-dotazy/Jak-se-vyvijela-dvoutydenni-repo-sazba-CNB/) | Czech National Bank website terms: may be redistributed with the credit “Source: ČNB (Czech National Bank)”; content must not be altered | [CSV](data/repo-sazba-cnb.csv) · [columns](docs/en/repo-sazba-cnb.md) |
| [Czech public holidays 2000–2050 with shop closure days (CSV, JSON)](https://czechdatasets.com/en/otevrena-data/statni-svatky) | 647 | 9 November 2026 | [czechdatasets.com](https://czechdatasets.com/data/zdarma) | Free to use without restriction (computed from Czech Acts No. 245/2000 and No. 223/2016); attribution is welcome | [CSV](data/statni-svatky.csv) · [columns](docs/en/statni-svatky.md) |
| [Czech name days calendar (CSV, JSON)](https://czechdatasets.com/en/otevrena-data/jmeniny) | 360 | 9 November 2026 | [Wikipedia contributors (Name days in the Czech Republic)](https://cs.wikipedia.org/wiki/Jmeniny_v_%C4%8Cesku) | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) | [CSV](data/jmeniny.csv) · [columns](docs/en/jmeniny.md) |

## Using the data

Every file has a stable address in this repository and on the website:

```
https://raw.githubusercontent.com/sth3no/czech-open-data/main/data/psc.csv
https://czechdatasets.com/open/psc.csv
https://czechdatasets.com/open/psc.json
```

Python:

```python
import pandas as pd
obce = pd.read_csv("https://raw.githubusercontent.com/sth3no/czech-open-data/main/data/obce-cr.csv", dtype={"obec_kod": str})
```

DuckDB:

```sql
SELECT kraj, count(*) AS obci FROM 'https://raw.githubusercontent.com/sth3no/czech-open-data/main/data/obce-cr.csv' GROUP BY kraj ORDER BY obci DESC;
```

## How to cite

Cite the original source named on the table together with "processed by czechdatasets.com" and link the table page, for example:

> Source: Czech Statistical Office; processed by czechdatasets.com, https://czechdatasets.com/en/otevrena-data/obyvatelstvo-obci-2026

The exact wording for each table is in its file in `docs/en/` under "How to cite".

## Full datasets

The open tables are aggregates, code lists and latest snapshots. The complete datasets behind them (every address, parcel, company, vacancy or election result, with history) are available as one-off downloads at [czechdatasets.com](https://czechdatasets.com/en). Sample files of each dataset are free at https://czechdatasets.com/en/data/zdarma.

## Česky

35 otevřených tabulek o České republice z oficiálních otevřených dat: obce, PSČ a územní členění (RÚIAN), firmy, datové schránky, školy, poskytovatelé zdravotní péče, lékárny, léčiva, volby, mzdy, obyvatelstvo a ukazatele obcí. Celkem 53 124 řádků v CSV (UTF-8, oddělovač čárka, záhlaví v prvním řádku). Tabulky vycházejí na **[czechdatasets.com/otevrena-data](https://czechdatasets.com/otevrena-data)**, tento repozitář je jejich zrcadlo. Popis sloupců česky je ve složce `docs/cs/`, licence jednotlivých tabulek v [LICENSE.md](LICENSE.md).

### RÚIAN s historií ([celá sada](https://czechdatasets.com/data/ruian))

| Tabulka | Řádků | Stav dat | Zdroj | Licence | Soubory |
| --- | ---: | --- | --- | --- | --- |
| [Seznam obcí ČR s kódy (CSV, JSON)](https://czechdatasets.com/otevrena-data/obce-cr) | 6 258 | září 2026 | [ČÚZK (RÚIAN)](https://vdp.cuzk.gov.cz/) | [CC BY 4.0 (ČÚZK)](https://creativecommons.org/licenses/by/4.0/deed.cs) | [CSV](data/obce-cr.csv) · [sloupce](docs/cs/obce-cr.md) |
| [Počet obcí, katastrálních území, ulic a adres v ČR](https://czechdatasets.com/otevrena-data/pocty-uzemnich-prvku) | 14 | září 2026 | [ČÚZK (RÚIAN)](https://vdp.cuzk.gov.cz/) | [CC BY 4.0 (ČÚZK)](https://creativecommons.org/licenses/by/4.0/deed.cs) | [CSV](data/pocty-uzemnich-prvku.csv) · [sloupce](docs/cs/pocty-uzemnich-prvku.md) |
| [Seznam PSČ v ČR podle obcí (CSV)](https://czechdatasets.com/otevrena-data/psc) | 7 846 | září 2026 | [ČÚZK (RÚIAN)](https://vdp.cuzk.gov.cz/) | [CC BY 4.0 (ČÚZK)](https://creativecommons.org/licenses/by/4.0/deed.cs) | [CSV](data/psc.csv) · [sloupce](docs/cs/psc.md) |

### Číselníky ČSÚ ([celá sada](https://czechdatasets.com/data/csu-ciselniky))

| Tabulka | Řádků | Stav dat | Zdroj | Licence | Soubory |
| --- | ---: | --- | --- | --- | --- |
| [Kraje a okresy ČR s kódy CZ-NUTS a LAU 1](https://czechdatasets.com/otevrena-data/kraje-a-okresy) | 91 | 11. 11. 2026 | [ČSÚ](https://apl.czso.cz/iSMS/) | [CC BY 4.0 (ČSÚ)](https://csu.gov.cz/podminky_pro_vyuzivani_a_dalsi_zverejnovani_statistickych_udaju_csu) | [CSV](data/kraje-a-okresy.csv) · [sloupce](docs/cs/kraje-a-okresy.md) |
| [CZ-NACE 2025: číselník kódů a názvů (CSV, JSON)](https://czechdatasets.com/otevrena-data/cz-nace-2025) | 1 803 | 11. 11. 2026 | [ČSÚ](https://apl.czso.cz/iSMS/) | [CC BY 4.0 (ČSÚ)](https://csu.gov.cz/podminky_pro_vyuzivani_a_dalsi_zverejnovani_statistickych_udaju_csu) | [CSV](data/cz-nace-2025.csv) · [sloupce](docs/cs/cz-nace-2025.md) |
| [Číselník právních forem ČR (kód 112 = s.r.o., 121 = a.s.)](https://czechdatasets.com/otevrena-data/pravni-formy) | 118 | 11. 11. 2026 | [ČSÚ](https://apl.czso.cz/iSMS/) | [CC BY 4.0 (ČSÚ)](https://csu.gov.cz/podminky_pro_vyuzivani_a_dalsi_zverejnovani_statistickych_udaju_csu) | [CSV](data/pravni-formy.csv) · [sloupce](docs/cs/pravni-formy.md) |

### Geokodér a našeptávač adres ([celá sada](https://czechdatasets.com/data/geokoder))

| Tabulka | Řádků | Stav dat | Zdroj | Licence | Soubory |
| --- | ---: | --- | --- | --- | --- |
| [Počet adresních míst v ČR podle okresů](https://czechdatasets.com/otevrena-data/adresy-podle-okresu) | 78 | září 2026 | [ČÚZK (RÚIAN)](https://vdp.cuzk.gov.cz/) | [CC BY 4.0 (ČÚZK)](https://cuzk.gov.cz/Predpisy/Podminky-poskytovani-prostor-dat-a-sitovych-sluzeb/Podminky-poskytovani-prostorovych-dat-CUZK.aspx) | [CSV](data/adresy-podle-okresu.csv) · [sloupce](docs/cs/adresy-podle-okresu.md) |

### Rizika adres ([celá sada](https://czechdatasets.com/data/rizika-adres))

| Tabulka | Řádků | Stav dat | Zdroj | Licence | Soubory |
| --- | ---: | --- | --- | --- | --- |
| [Podíl adres v záplavovém území podle obcí (Q100, radon, poddolování)](https://czechdatasets.com/otevrena-data/rizika-podle-obci) | 6 258 | 11. 11. 2026 | [VÚV TGM, Česká geologická služba, AOPK ČR, ČHMÚ a ČÚZK](https://heis.vuv.cz/isvs/zapluz) | [CC BY 4.0 (VÚV TGM, ČGS, AOPK ČR, ČHMÚ, ČÚZK), MŽP](https://creativecommons.org/licenses/by/4.0/deed.cs) | [CSV](data/rizika-podle-obci.csv) · [sloupce](docs/cs/rizika-podle-obci.md) |

### Firmy a organizace (RES) ([celá sada](https://czechdatasets.com/data/firmy))

| Tabulka | Řádků | Stav dat | Zdroj | Licence | Soubory |
| --- | ---: | --- | --- | --- | --- |
| [Počet firem v ČR podle právní formy](https://czechdatasets.com/otevrena-data/firmy-podle-pravni-formy) | 67 | 31. 10. 2026 | [ČSÚ (Registr ekonomických subjektů)](https://csu.gov.cz/registr-ekonomickych-subjektu-otevrena-data-dokumentace) | [CC BY 4.0 (ČSÚ, ČÚZK)](https://csu.gov.cz/podminky_pro_vyuzivani_a_dalsi_zverejnovani_statistickych_udaju_csu) | [CSV](data/firmy-podle-pravni-formy.csv) · [sloupce](docs/cs/firmy-podle-pravni-formy.md) |
| [Počet firem podle krajů a odvětví CZ-NACE](https://czechdatasets.com/otevrena-data/firmy-podle-kraju-a-odvetvi) | 297 | 31. 10. 2026 | [ČSÚ (Registr ekonomických subjektů)](https://csu.gov.cz/registr-ekonomickych-subjektu-otevrena-data-dokumentace) | [CC BY 4.0 (ČSÚ, ČÚZK)](https://csu.gov.cz/podminky_pro_vyuzivani_a_dalsi_zverejnovani_statistickych_udaju_csu) | [CSV](data/firmy-podle-kraju-a-odvetvi.csv) · [sloupce](docs/cs/firmy-podle-kraju-a-odvetvi.md) |

### Datové schránky ([celá sada](https://czechdatasets.com/data/datove-schranky))

| Tabulka | Řádků | Stav dat | Zdroj | Licence | Soubory |
| --- | ---: | --- | --- | --- | --- |
| [Počet datových schránek v ČR podle typu](https://czechdatasets.com/otevrena-data/datove-schranky-podle-typu) | 5 | 9. 11. 2026 | [Digitální a informační agentura (seznam datových schránek)](https://www.datovka.gov.cz/sds/welcome?part=opendata) | [Volné užití (NKOD), adresy CC BY 4.0](https://data.gov.cz/podmínky-užití/neobsahuje-autorská-díla/) | [CSV](data/datove-schranky-podle-typu.csv) · [sloupce](docs/cs/datove-schranky-podle-typu.md) |
| [ID datových schránek úřadů a obcí (seznam ke stažení)](https://czechdatasets.com/otevrena-data/datove-schranky-uradu) | 7 554 | 9. 11. 2026 | [Digitální a informační agentura (seznam datových schránek)](https://www.datovka.gov.cz/sds/welcome?part=opendata) | [Volné užití (NKOD), adresy CC BY 4.0](https://data.gov.cz/podmínky-užití/neobsahuje-autorská-díla/) | [CSV](data/datove-schranky-uradu.csv) · [sloupce](docs/cs/datove-schranky-uradu.md) |

### Volná pracovní místa ([celá sada](https://czechdatasets.com/data/volna-mista))

| Tabulka | Řádků | Stav dat | Zdroj | Licence | Soubory |
| --- | ---: | --- | --- | --- | --- |
| [Počet volných pracovních míst v ČR podle krajů](https://czechdatasets.com/otevrena-data/volna-mista-podle-kraju) | 16 | 11. 11. 2026 | [MPSV a Úřad práce ČR](https://data.mpsv.cz/web/data/volna-mista-za-celou-cr) | [Volné užití (NKOD); RES a RÚIAN CC BY 4.0](https://data.mpsv.cz/web/data/podminky-uziti) | [CSV](data/volna-mista-podle-kraju.csv) · [sloupce](docs/cs/volna-mista-podle-kraju.md) |
| [Nejžádanější profese a nabízená mzda podle CZ-ISCO](https://czechdatasets.com/otevrena-data/volna-mista-podle-profesi) | 518 | 11. 11. 2026 | [MPSV a Úřad práce ČR](https://data.mpsv.cz/web/data/volna-mista-za-celou-cr) | [Volné užití (NKOD); RES a RÚIAN CC BY 4.0](https://data.mpsv.cz/web/data/podminky-uziti) | [CSV](data/volna-mista-podle-profesi.csv) · [sloupce](docs/cs/volna-mista-podle-profesi.md) |

### Školy a školská zařízení ([celá sada](https://czechdatasets.com/data/skoly))

| Tabulka | Řádků | Stav dat | Zdroj | Licence | Soubory |
| --- | ---: | --- | --- | --- | --- |
| [Kolik je v ČR mateřských, základních a středních škol podle krajů](https://czechdatasets.com/otevrena-data/skoly-podle-kraju) | 15 | 9. 11. 2026 | [MŠMT (rejstřík škol a školských zařízení)](https://lkod-ftp.msmt.gov.cz/00022985/88a7c12b-6084-4e47-8b50-46097c6e683f/RSSZ-cela-CR.jsonld) | [Volné užití (NKOD), adresy CC BY 4.0](https://data.gov.cz/zdroj/datové-sady/00022985/1c063ba63b80cbb7b0e600dfcd9a47d9/distribuce/f3888446f0df12416de8d94a0cbb3e36/podmínky-užití) | [CSV](data/skoly-podle-kraju.csv) · [sloupce](docs/cs/skoly-podle-kraju.md) |

### Léčivé přípravky (SÚKL) ([celá sada](https://czechdatasets.com/data/sukl-leciva))

| Tabulka | Řádků | Stav dat | Zdroj | Licence | Soubory |
| --- | ---: | --- | --- | --- | --- |
| [Počet léčivých přípravků v ČR podle ATC skupin](https://czechdatasets.com/otevrena-data/leciva-podle-atc) | 110 | 1. 11. 2026 | [SÚKL (Databáze léčivých přípravků)](https://opendata.sukl.cz/katalog-otevrenych-dat/databaze-lecivych-pripravku-dlp) | [Podmínky SÚKL, komerční užití povoleno](https://opendata.sukl.cz/podminky-uziti-otevrenych-dat) | [CSV](data/leciva-podle-atc.csv) · [sloupce](docs/cs/leciva-podle-atc.md) |

### Výpadky a dostupnost léků ([celá sada](https://czechdatasets.com/data/sukl-vypadky))

| Tabulka | Řádků | Stav dat | Zdroj | Licence | Soubory |
| --- | ---: | --- | --- | --- | --- |
| [Výpadky léků v ČR podle let: počet přerušení dodávek a jejich délka](https://czechdatasets.com/otevrena-data/vypadky-leku-podle-let) | 22 | 9. 11. 2026 | [SÚKL (hlášení o dodávkách léčivých přípravků)](https://opendata.sukl.gov.cz/katalog-otevrenych-dat/hlaseni-o-uvedeni-preruseni-ukonceni-obnoveni-dodavek-leciveho-pripravku-na-trh) | [Podmínky SÚKL, komerční užití povoleno](https://opendata.sukl.gov.cz/podminky-uziti-otevrenych-dat) | [CSV](data/vypadky-leku-podle-let.csv) · [sloupce](docs/cs/vypadky-leku-podle-let.md) |
| [Aktuálně nedostupné léky v ČR podle ATC skupin](https://czechdatasets.com/otevrena-data/nedostupne-leky-podle-atc) | 14 | 9. 11. 2026 | [SÚKL (hlášení o dodávkách léčivých přípravků)](https://opendata.sukl.gov.cz/katalog-otevrenych-dat/hlaseni-o-uvedeni-preruseni-ukonceni-obnoveni-dodavek-leciveho-pripravku-na-trh) | [Podmínky SÚKL, komerční užití povoleno](https://opendata.sukl.gov.cz/podminky-uziti-otevrenych-dat) | [CSV](data/nedostupne-leky-podle-atc.csv) · [sloupce](docs/cs/nedostupne-leky-podle-atc.md) |

### Lékárny s otevírací dobou a GPS ([celá sada](https://czechdatasets.com/data/lekarny))

| Tabulka | Řádků | Stav dat | Zdroj | Licence | Soubory |
| --- | ---: | --- | --- | --- | --- |
| [Kolik je lékáren v ČR: počet lékáren podle okresů a krajů](https://czechdatasets.com/otevrena-data/lekarny-podle-okresu) | 78 | 1. 11. 2026 | [SÚKL (seznam lékáren)](https://opendata.sukl.gov.cz/katalog-otevrenych-dat/seznam-lekaren) | [Podmínky SÚKL, komerční užití povoleno; adresy CC BY 4.0 (ČÚZK)](https://opendata.sukl.gov.cz/podminky-uziti-otevrenych-dat) | [CSV](data/lekarny-podle-okresu.csv) · [sloupce](docs/cs/lekarny-podle-okresu.md) |

### Zdravotnická zařízení (NRPZS) ([celá sada](https://czechdatasets.com/data/poskytovatele-zdravotni-pece))

| Tabulka | Řádků | Stav dat | Zdroj | Licence | Soubory |
| --- | ---: | --- | --- | --- | --- |
| [Počet praktických lékařů, zubařů a nemocnic podle okresů](https://czechdatasets.com/otevrena-data/ordinace-podle-okresu) | 78 | 1. 11. 2026 | [ÚZIS ČR (Národní registr poskytovatelů zdravotních služeb)](https://datanzis.uzis.gov.cz/data/NR-01-NRPZS/NR-01-06/Otevrena-data-NR-01-06-nrpzs-mista-poskytovani-zdravotnich-sluzeb.csv) | [CC BY 4.0 (ÚZIS, ČÚZK)](https://creativecommons.org/licenses/by/4.0/) | [CSV](data/ordinace-podle-okresu.csv) · [sloupce](docs/cs/ordinace-podle-okresu.md) |
| [Seznam nemocnic v ČR s adresou a GPS](https://czechdatasets.com/otevrena-data/nemocnice) | 138 | 1. 11. 2026 | [ÚZIS ČR (Národní registr poskytovatelů zdravotních služeb)](https://datanzis.uzis.gov.cz/data/NR-01-NRPZS/NR-01-06/Otevrena-data-NR-01-06-nrpzs-mista-poskytovani-zdravotnich-sluzeb.csv) | [CC BY 4.0 (ÚZIS, ČÚZK)](https://creativecommons.org/licenses/by/4.0/) | [CSV](data/nemocnice.csv) · [sloupce](docs/cs/nemocnice.md) |

### Výsledky voleb 1996–2026 ([celá sada](https://czechdatasets.com/data/volby))

| Tabulka | Řádků | Stav dat | Zdroj | Licence | Soubory |
| --- | ---: | --- | --- | --- | --- |
| [Volební účast v ČR: přehled všech voleb od roku 1996](https://czechdatasets.com/otevrena-data/volby-prehled) | 84 | 17. 10. 2026 | [ČSÚ (volby.gov.cz)](https://www.volby.cz/opendata/opendata.htm) | [CC BY 4.0 (ČSÚ, ČÚZK)](https://csu.gov.cz/podminky_pro_vyuzivani_a_dalsi_zverejnovani_statistickych_udaju_csu) | [CSV](data/volby-prehled.csv) · [sloupce](docs/cs/volby-prehled.md) |
| [Výsledky voleb do Poslanecké sněmovny 2025 podle krajů](https://czechdatasets.com/otevrena-data/volby-ps-2025-kraje) | 339 | 17. 10. 2026 | [ČSÚ (volby.gov.cz)](https://www.volby.cz/opendata/opendata.htm) | [CC BY 4.0 (ČSÚ, ČÚZK)](https://csu.gov.cz/podminky_pro_vyuzivani_a_dalsi_zverejnovani_statistickych_udaju_csu) | [CSV](data/volby-ps-2025-kraje.csv) · [sloupce](docs/cs/volby-ps-2025-kraje.md) |
| [Výsledky voleb 2025 po obcích (CSV ke stažení)](https://czechdatasets.com/otevrena-data/volby-ps-2025-obce) | 6 254 | 17. 10. 2026 | [ČSÚ (volby.gov.cz)](https://www.volby.cz/opendata/opendata.htm) | [CC BY 4.0 (ČSÚ, ČÚZK)](https://csu.gov.cz/podminky_pro_vyuzivani_a_dalsi_zverejnovani_statistickych_udaju_csu) | [CSV](data/volby-ps-2025-obce.csv) · [sloupce](docs/cs/volby-ps-2025-obce.md) |

### Obyvatelstvo obcí 2000–2026 ([celá sada](https://czechdatasets.com/data/csu-obyvatelstvo))

| Tabulka | Řádků | Stav dat | Zdroj | Licence | Soubory |
| --- | ---: | --- | --- | --- | --- |
| [Počet obyvatel v obcích ČR k 1. 1. 2026 (CSV)](https://czechdatasets.com/otevrena-data/obyvatelstvo-obci-2026) | 6 258 | 1. 1. 2026 | [ČSÚ](https://data.csu.gov.cz/datastat/info/SADA/OBY02E) | [CC BY 4.0 (ČSÚ)](https://csu.gov.cz/podminky_pro_vyuzivani_a_dalsi_zverejnovani_statistickych_udaju_csu) | [CSV](data/obyvatelstvo-obci-2026.csv) · [sloupce](docs/cs/obyvatelstvo-obci-2026.md) |
| [Počet obyvatel ČR a krajů 2000–2026](https://czechdatasets.com/otevrena-data/obyvatelstvo-kraju) | 405 | 1. 1. 2026 | [ČSÚ](https://data.csu.gov.cz/datastat/info/SADA/OBY02E) | [CC BY 4.0 (ČSÚ)](https://csu.gov.cz/podminky_pro_vyuzivani_a_dalsi_zverejnovani_statistickych_udaju_csu) | [CSV](data/obyvatelstvo-kraju.csv) · [sloupce](docs/cs/obyvatelstvo-kraju.md) |

### Mzdy podle krajů a odvětví ([celá sada](https://czechdatasets.com/data/mzdy))

| Tabulka | Řádků | Stav dat | Zdroj | Licence | Soubory |
| --- | ---: | --- | --- | --- | --- |
| [Průměrná mzda podle krajů: 2. čtvrtletí 2026](https://czechdatasets.com/otevrena-data/mzdy-podle-kraju) | 30 | 30. 6. 2026 | [ČSÚ](https://data.csu.gov.cz/datastat/info/SADA/MZDQ1) | [CC BY 4.0 (ČSÚ)](https://csu.gov.cz/podminky_pro_vyuzivani_a_dalsi_zverejnovani_statistickych_udaju_csu) | [CSV](data/mzdy-podle-kraju.csv) · [sloupce](docs/cs/mzdy-podle-kraju.md) |
| [Průměrná mzda podle odvětví CZ-NACE: 2. čtvrtletí 2026](https://czechdatasets.com/otevrena-data/mzdy-podle-odvetvi) | 40 | 30. 6. 2026 | [ČSÚ](https://data.csu.gov.cz/datastat/info/SADA/MZDQ1) | [CC BY 4.0 (ČSÚ)](https://csu.gov.cz/podminky_pro_vyuzivani_a_dalsi_zverejnovani_statistickych_udaju_csu) | [CSV](data/mzdy-podle-odvetvi.csv) · [sloupce](docs/cs/mzdy-podle-odvetvi.md) |
| [Průměrná mzda v ČR po čtvrtletích od roku 2000](https://czechdatasets.com/otevrena-data/mzdy-cesko-ctvrtletne) | 106 | 30. 6. 2026 | [ČSÚ](https://data.csu.gov.cz/datastat/info/SADA/MZDQ1) | [CC BY 4.0 (ČSÚ)](https://csu.gov.cz/podminky_pro_vyuzivani_a_dalsi_zverejnovani_statistickych_udaju_csu) | [CSV](data/mzdy-cesko-ctvrtletne.csv) · [sloupce](docs/cs/mzdy-cesko-ctvrtletne.md) |

### Obce v číslech 2000–2025 ([celá sada](https://czechdatasets.com/data/obce-v-cislech))

| Tabulka | Řádků | Stav dat | Zdroj | Licence | Soubory |
| --- | ---: | --- | --- | --- | --- |
| [Číselník ukazatelů Městské a obecní statistiky (MOS)](https://czechdatasets.com/otevrena-data/ukazatele-obci) | 800 | 22. 7. 2026 | [ČSÚ (Městská a obecní statistika)](https://csu.gov.cz/produkty/databaze-mos-otevrena-data) | [CC BY 4.0 (ČSÚ, ČÚZK)](https://csu.gov.cz/podminky_pro_vyuzivani_a_dalsi_zverejnovani_statistickych_udaju_csu) | [CSV](data/ukazatele-obci.csv) · [sloupce](docs/cs/ukazatele-obci.md) |
| [Obce ČR v číslech: rozloha, obyvatelé, nezaměstnanost, školy](https://czechdatasets.com/otevrena-data/obce-zakladni-ukazatele) | 6 258 | 22. 7. 2026 | [ČSÚ (Městská a obecní statistika)](https://csu.gov.cz/produkty/databaze-mos-otevrena-data) | [CC BY 4.0 (ČSÚ, ČÚZK)](https://csu.gov.cz/podminky_pro_vyuzivani_a_dalsi_zverejnovani_statistickych_udaju_csu) | [CSV](data/obce-zakladni-ukazatele.csv) · [sloupce](docs/cs/obce-zakladni-ukazatele.md) |

### Balíček zdarma

| Tabulka | Řádků | Stav dat | Zdroj | Licence | Soubory |
| --- | ---: | --- | --- | --- | --- |
| [Kódy bank ČR: číselník ČNB (CSV, JSON)](https://czechdatasets.com/otevrena-data/kody-bank) | 47 | 9. 11. 2026 | [ČNB](https://www.cnb.cz/cs/platebni-styk/ucty-kody-bank/) | Podmínky užívání stránek ČNB: lze šířit s uvedením zdroje „Zdroj: ČNB“, obsah se nesmí měnit | [CSV](data/kody-bank.csv) · [sloupce](docs/cs/kody-bank.md) |
| [Repo sazba ČNB: historie změn od roku 1995](https://czechdatasets.com/otevrena-data/repo-sazba-cnb) | 118 | 9. 11. 2026 | [ČNB](https://www.cnb.cz/cs/casto-kladene-dotazy/Jak-se-vyvijela-dvoutydenni-repo-sazba-CNB/) | Podmínky užívání stránek ČNB: lze šířit s uvedením zdroje „Zdroj: ČNB“, obsah se nesmí měnit | [CSV](data/repo-sazba-cnb.csv) · [sloupce](docs/cs/repo-sazba-cnb.md) |
| [České státní svátky 2000–2050 včetně zavřených obchodů (CSV, JSON)](https://czechdatasets.com/otevrena-data/statni-svatky) | 647 | 9. 11. 2026 | [czechdatasets.com](https://czechdatasets.com/data/zdarma) | Volné užití bez omezení (vypočteno ze zákonů č. 245/2000 Sb. a č. 223/2016 Sb.), uvedení zdroje je vítané | [CSV](data/statni-svatky.csv) · [sloupce](docs/cs/statni-svatky.md) |
| [Jmeniny: český kalendář jmen (CSV, JSON)](https://czechdatasets.com/otevrena-data/jmeniny) | 360 | 9. 11. 2026 | [autoři Wikipedie (Jmeniny v Česku)](https://cs.wikipedia.org/wiki/Jmeniny_v_%C4%8Cesku) | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) | [CSV](data/jmeniny.csv) · [sloupce](docs/cs/jmeniny.md) |
