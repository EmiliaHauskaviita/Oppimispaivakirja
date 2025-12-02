# Oppimispäiväkirja: Paikallinen git

__Mikä osion tehtävissä oli vaikeaa ja mikä helppoa? Mikä auttoi minua oppimaan? Miten selvitin esteet?__

Minulla oli alkuun isoja ongelmia, sillä minulla on git ladattu läppärilleni mutta se on MacBook ja sain sen kanssa taistella tovin, kunnes luovutin ja latasin git pöytäkoneelleni. Powershell ei ole oma lempparini ja komennot joilla, tämä toimii ovat hankalia. Olen tottunut nimittäin Linuxin komentoihin. Ilmeisesti MacBookilla tulee tietosuoja vastaan? Olen nimittäin aikaisemmin käyttänyt git SSH yhteyden kautta. 

## Osiossa käyttämäni Git-komennot

| Komento | Kuvaus |
| --------| ------ |
| Git --version | tarkastin että git on latautunut |
| dir | toimii kuin ls näyttää hakemiston sisällön |
| git clone | kloonaa halutun reposition |
| cd | siirtyy hakemistoon |
| git checkout | vaihtaa haaran |
| mkdir| luo uuden hakemiston |
| git init | perustaa repositorion |
| echo "haluttu teksti" > "tiedoston nimi"| luo uuden tiedoston sisällöllä |
| git add | valmistelee muutokset |
| git commit -m | tallentaa muutokset kuvaavalla viestillä|
| rename "vanha tiedoston nimi" "uusi tiedoston nimi" | nimeää tiedoston uudelleen|
| git rm | poistaa |
| git log | Näyttää git historian |
| git log --stat | Näyttää git historian tilastoilla |
| type "tiedoston nimi" | Toimii samalla tavalla kuin cat eli pystyt nähdä tiedoston sisällön |
| git restore | peruuttaa add toiminnon |
| git reset | poistaa kaikki muutokset |
| git revert HEAD | luo uuden commitin joka kumoaa edellisen |
| git branch | kertoo haaran |
| git checkout "haara" -- "tiedosto" | kopioi tiedoston haarasta |
| git merge| yhdistää haarat |


## Harjoitus 2

git log komento näyttää minulle commit historian.

git log --stat näyttää minulle lisätietoa siitä, miten commit on vaikuttanut tiedostoon.

## Harjoitus 3 

git status komennon avulla voidaan seurata koko ajan mitä tiedostoille tapahtuu kun ne ovat odottamassa talletusta. 

Untracked tiedostot: Pysyivät hakemistossa mutta voidaan myös poistaa käyttämällä komentoa git clean -f.

Revert komentoon käytin apuna copilot sillä en ymmärtänyt sen toimimista. 

Komento git log näyttää minulle revert-commitin jossa muutokset palautettiin.

## Harjoitus 4 

Minun piti hetki etsiä ja lueskella ohjeista mitä master haara tarkoittaa. Note to self: Älä hyppää suoraan tehtävän pariin!
Olen sen verran ruosteessa näistä asioista että jouduin hetken kaivelemaan miten voin avata hello.html tiedoston verkossa. Mutta lopulta sain kuin sainkin sen avautumaan!!

En oikein ymmärtänyt harjoituksen loppua. Olin luonut style.css master haaraan ja kun loin uuden haaran tyylit yritin siirtää style.css tiedostoa sinne ja kun luulin saaneeni sen tehdyksi mikään ei muuttunut ja kun tein lopussa master ja tyylit merge sain ilmoituksen "already up to date.". 

2.12.2025 muutoksia: Kun oltiin luodussa tyylit haarassa jossa oli myös styles.css tiedosto tyylit näkyivät selaimessa. Kun vaihdettiin main niin tyylit eivät näkyneet ennen kuin tehtiin merge. 
