# Oppimispäiväkirja: Paikallinen git

__Mikä osion tehtävissä oli vaikeaa ja mikä helppoa? Mikä auttoi minua oppimaan? Miten selvitin esteet?__

Alkuun Git-komentojen muistaminen ja niiden tarkoituksen ymmärtäminen tuntui erittäin haastavalta. Harjoitusten edetessä peruskomennot alkoivat tulla tutuksi! Erityisesti haarojen käyttö selkeytyi kun käytännön tasolla pääsi näkymään miten sivu muuttui vaihtaessani haarasta toiseen. 
Muutosten peruuttamiseen liittyvät komennot olivat alkuun hieman haastavia, mutta harjoittelemalla ja toistamalla opin paremmin reset-, restore- ja revert komentojen eroja. Tehtävissä tuli vastaan myös muutamia virheilmoituksia, joiden selvittäminen auttoi ymmärtämään Gitin toimintaa paremmin. Minua auttoi erityisesti git status -komennon käyttäminen eri vaiheissa sekä komentojen rohkea kokeileminen käytännössä! :D 

## Osiossa käyttämäni Git-komennot

| Komento | Kuvaus |
git init	Luo uuden Git-repositorion
git status	Näyttää repositoryn nykyisen tilanteen
git add	Lisää muutokset seuraavaa committia varten
git commit	Tallentaa muutokset Gitin historiaan
git log	Näyttää commit-historian
git mv	Siirtää tai nimeää tiedoston uudelleen
git rm	Poistaa tiedoston versionhallinnasta
git tag	Lisää tunnisteen committiin
git reset	Poistaa muutoksia staging-alueelta
git restore	Palauttaa tiedostoon tehdyt muutokset
git revert	Kumoaa commitin muutokset uudella commitilla
git branch	Näyttää tai luo haaroja
git switch	Vaihtaa Git-haaraa
git merge	Yhdistää haarojen muutokset