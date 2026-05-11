# Ajalooliste isikuandmete automaatne sidumine opteerimisprotsessi uurimisel

Repositoorium sisaldab magistritöö „Ajalooliste isikuandmete automaatne sidumine opteerimisprotsessi uurimisel” raames kasutatud R-skripte ja töövoogu.

Töö eesmärk on uurida ajalooliste isikuandmete automaatse sidumise võimalusi ja piiranguid, kasutades juhtumiuuringuna opteerimisprotsessi. Analüüs põhineb Narva karantiini kaudu aastatel 1920–1922 Eestisse saabunud isikute andmestiku sidumisel pereregistri ja rahvastikuregistri arhiiviga.

## Repositooriumi ülesehitus

Skriptid on jagatud tööetappide järgi:

- `01_andmete_puhastus.Rmd` – andmete puhastamine ja ettevalmistus
- `02_andmestike_sidumine.Rmd` – automaatse sidumise protsess
- `03_sidumistulemuste_hindamine.Rmd` – sidumistulemuste kontroll ja hindamine
- `04_kohaandmete_analyys.Rmd` – kohaandmete eeltöötlus
- `05_tulemuste_analyys.Rmd` – lõplikud analüüsid ja tulemused

Lisaks sisaldab repositoorium käsitsi loodud kontrollandmestikku:
- `Kontrollandmestik(n=287).csv`

## Kasutatud tarkvara

Analüüs viidi läbi R programmeerimiskeskkonnas. Automaatseks isikukirjete sidumiseks kasutasin paketti `reclin2`


## Andmete kättesaadavus

Repositoorium ei sisalda töö aluseks olnud täielikke algandmestikke, kuna kasutatud andmed sisaldavad isikuandmeid ja nende kasutamine on piiratud.

Kontrollandmestik on repositooriumis kättesaadav CSV-failina.

## Autor

Hanna-Riin Karu  
Tartu Ülikool  
Ajaloo ja arheoloogia instituut  
2026
