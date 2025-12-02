# Oppimispäiväkirja: Hajautettu git

__Mikä osion tehtävissä oli vaikeaa ja mikä helppoa? Mikä auttoi minua oppimaan? Miten selvitin esteet, jotka vaikuttivat tehtävän suorittamiseen?__

GitHubiin loin uuden repositorion nimeltä Hello.

Repositoriossa näen main haaran. 

Terminaalissa näen main, paivakirja1, paivakirja2.

kohdassa 6. muuttui se että näen GitHubissa luodun tiedoston uusi.md. 

7. Palaa main-haaraan. Mitä komento status sanoo? Switched to branch 'main' your branch is behind 'origin/main' by 1 commit
   
9. Yhdistä origin/main-haaran muutokset. Mitä komento status nyt sanoo? Your branch is up to date with 'origin/main'. nothing to commit, working tree clean
    
Note! Minulla oli vaikeuksia tehtävän kanssa sillä alkuun vaihdoin vain repositoriota enkä saanut molempia repositorioita. Tämän sain kuitenkin ratkaistua ja nyt se toimii niin kuin pitääkin.

## Osiossa käyttämäni Git-komennot

| Komento | Kuvaus |

|git remote -v| etärepositorioasetukset |

| git remote remove origin | poistaa yhteyden vanhan etäreposition kanssa |

| git remote add origin | yhdistetään haluttu github repositorio |

| git remote add upstream | lisätään etärepositorio tässä tapauksessa lisäsin upstrem opettajan repositorion |

|git push -u origin main| pusketaan sisältö omaan github|

|git status| tarkistaa tilanteen |

|git fetch| Hakee muutokset |

|git merge upstream/main| yhdistää opettajan uudet tehtävät omaan repositorioon |
