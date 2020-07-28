# Python webpage parser - DigDirCamp 2020

## Installasjon

For å køyre denne notebooken trenger du jupyter på din PC. Eg anbefaler at ein installerer følgande program:

- Visual Studio Code (link: https://code.visualstudio.com/)
- Anaconda (link: https://www.anaconda.com/products/individual)

### Visual Studio Code

I Visual Studio Code anbefalar eg å installere følgande extensions:

- Python
- Rainbow csv

Python extensionen lar deg redigere og køyre jupyter notebooks i visual studio code istadenfor å hoste ein jupyter økt i terminalen og opne den i nettlesaren.

### Anaconda og anacondamiljø

Python-koden i notebooken krever ein del bibiliotek, t.d scipy, numpy, pandas, faker osv. For å kjapt installere dette på din PC og for å håndtere bibiliotek på ein god
måte er det anbefalt å bruke anaconda. 

Aktiver anaconda miljøet i vscode og opne terminalen i rot mappa med miljøet aktivert. (oppsett: https://code.visualstudio.com/docs/python/environments)

For å importere anacondamiljøet køyr kommandoen: `conda env create -f pydigdir.yml`

Då er alle bibiliotek som ein treng for å køyre denne notebooken (og dei andre jupyter notebookane laga på DigDirCamp) installert.

### Litt om jupyter notebook

Ein jupyter notebook består av blokker som kan vere tekst eller kode. Det er vanleg praksis å legge små blokker med kode etter kvarandre med forklarande tekst.
Dette gjer at koden i cellene bygger på kvarandre og ein er nøydd å køyre koden frå topp til bunn (vs code har ein eigen knapp for å gjere dette automatisk)

## Politi

Datasett generert 9 Juli 2020.

Denne notebooken parser nettsidene til politiet for å lage eit datasett over lensmannskontor i Norge. Dette datasettet er dermed kun oppdatert pr 9 Juli 2020 og koden fungerer slik nettsidene til politiet såg ut den 9 Juli 2020. Bruker tree.xpath for å parse.

## Wikipediaartikkel over norske selkap

https://no.wikipedia.org/wiki/Liste_over_Norges_500_st%C3%B8rste_selskaper_i_2006#cite_note-1

Koden parser alle selskapa fra wikipediaartikkelen. Bruker tree.xpath for å parse.
