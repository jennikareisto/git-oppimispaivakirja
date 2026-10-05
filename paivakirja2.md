# Oppimispäiväkirja: Hajautettu git

__Mikä osion tehtävissä oli vaikeaa ja mikä helppoa? Mikä auttoi minua oppimaan? Miten selvitin esteet, jotka vaikuttivat tehtävän suorittamiseen?__

Hajautetun Gitin alussa etärepositorion ja paikallisen repositorion välinen ero tuntui hieman vaikealta hahmottaa. Harjoituksen aikana asia selkeytyi, kun muutoksia vietiin GitHubiin ja haettiin sieltä takaisin. Erityisesti fetch-komennon toiminta tuli konkreettisesti esille, kun GitHubissa tehty muutos ei tullut suoraan paikalliseen haaraan vaan se piti vielä yhdistää erikseen.
Harjoituksessa tuli vastaan myös muutamia virhetilanteita, mutta niiden selvittäminen auttoi ymmärtämään Gitin toimintaa paremmin. git status oli jälleen hyödyllinen, koska sen avulla pystyin tarkistamaan missä haarassa olin ja oliko paikallinen haara ajan tasalla etähaaran kanssa.

## Osiossa käyttämäni Git-komennot

| Komento | Kuvaus |
git remote -v	Näyttää repositorion etärepositoriot
git push	Vie paikalliset muutokset etärepositorioon
git fetch	Hakee etärepositorion muutokset yhdistämättä niitä
git branch -r	Näyttää etähaarat
git merge	Yhdistää haaran muutokset nykyiseen haaraan
git switch	Vaihtaa haarasta toiseen