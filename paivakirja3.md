# Oppimispäiväkirja: Git projektissa

__Mitä hyötyä voisi olla versionhallinnasta, jos kehität projektia yksin?__

Versionhallinnasta on hyötyä myös silloin, kun projektia kehittää yksin. Sen avulla muutokset ja projektin eri vaiheet jäävät talteen, jolloin aikaisempaan toimivaan versioon on mahdollista palata, jos jokin muutos aiheuttaa ongelmia. Commit-historiasta pystyy myös myöhemmin tarkistamaan, mitä projektiin on tehty ja missä vaiheessa. Haarojen avulla uusia ominaisuuksia voi kokeilla erillään projektin toimivasta versiosta. Kurssin aikana ymmärsin käytännössä, että Git ei ole pelkästään yhteistyöväline, vaan siitä on paljon hyötyä myös oman työn hallinnassa.


__Mitä hyötyä voisi olla versionhallinnasta, jos projektissa on useita kehittäjiä?__

Usean kehittäjän projektissa versionhallinnan merkitys korostuu entisestään. Gitin avulla jokainen voi työskennellä omassa haarassaan ilman, että keskeneräiset muutokset vaikuttavat suoraan muiden työhön. Muutokset voidaan yhdistää hallitusti yhteiseen haaraan ja GitHubin Pull Requestien avulla niitä voidaan myös tarkastella, kommentoida ja katselmoida ennen yhdistämistä. Versionhallinnasta jää lisäksi yhteinen historia siitä, kuka on tehnyt mitäkin ja milloin. Tämä helpottaa yhteistyötä ja vähentää riskiä siitä, että kehittäjät vahingossa sotkevat toistensa muutoksia.


__Miten järjestäisit projektitiimin versionhallinnan 3-4 hengen ohjelmistoprojektikurssilla? Laadi tiimiläisille lyhyt ohje, miten projektissa toimitaan.__

Järjestäisin tiimin työskentelyn niin, että projektilla olisi yhteinen GitHub-repositorio ja kaikilla tiimin jäsenillä olisi siitä oma paikallinen kopio. Sovittaisiin yhdessä, mikä haara toimii projektin yhteisenä kehityshaarana ja miten muutokset nimetään ja tallennetaan.

Uutta ominaisuutta varten tekisin aina oman ominaisuushaaran. Ennen työskentelyn aloittamista päivittäisin paikallisen repositorion, jotta käytössäni olisi projektin uusin versio. Muutokset tekisin omaan haaraan ja tallentaisin ne selkeillä commit-viesteillä. Kun ominaisuus olisi valmis, veisin haaran GitHubiin ja tekisin siitä Pull Requestin yhteiseen haaraan. Vähintään yksi toinen tiimin jäsen tarkistaisi muutoksen ennen sen yhdistämistä. Yhdistämisen jälkeen muut tiimiläiset päivittäisivät omat paikalliset repositorionsa.

Kurssilla opitut toimintatavat ovat hyödyllisiä myös oman työni kannalta. Työskentelen ohjelmistotalossa ohjelmistoasiantuntijana ja teen läheistä yhteistyötä tuotekehityksen kanssa. Käytän työssäni myös VS Codea ja GitHubia, joten kurssilla tutuksi tulleet työkalut ja versionhallinnan toimintaperiaatteet tukevat suoraan myös työssäni toimimista. Koen, että minun on nyt helpompi ymmärtää tuotekehityksen työskentelytapoja ja Gitissä käytettyjä käsitteitä.

__Kommenttini opintojaksosta, esim. sisällöstä, materiaalista, työmäärästä, hyödyllisyydestä, työmäärästä. Mitä toivoisit olevan enemmän, mitä vähemmän?__

Opintojakso oli mielestäni hyödyllinen erityisesti käytännönläheisyytensä vuoksi. Alussa Git-komentojen määrä ja eri käsitteet tuntuivat haastavilta, mutta harjoitusten edetessä kokonaisuus alkoi hahmottua paremmin. Erityisesti haarojen käyttäminen, paikallisen ja etärepositorion välinen toiminta sekä muutosten yhdistäminen tulivat paljon ymmärrettävämmiksi käytännön harjoittelun kautta. Myös virhetilanteiden ratkaiseminen opetti paljon, vaikka ne välillä hidastivat tekemistä.

Pidin siitä, että harjoituksissa käytettiin VS Codea ja GitHubia, koska ne ovat minulle hyödyllisiä myös työelämässä. Työskentelen ohjelmistoasiantuntijana ja teen yhteistyötä tuotekehityksen kanssa, joten koen kurssin auttavan minua ymmärtämään paremmin myös heidän työskentelyään ja versionhallinnan merkitystä ohjelmistokehityksessä.

Kokonaisuutena opintojakso antoi hyvän pohjan ja käsityksen Gitin käyttöön ja ennen kaikkea rohkeutta käyttää sitä jatkossa! Kiitos kurssikokonaisuudesta! 