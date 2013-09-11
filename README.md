# Tiimityoskentelyn harjoitus-repo

Kaikki Tiimityöskentelyopintojaksolle osallistuvat, forkatkaa ja kloonatkaa tämä repo. Tätä repoa käytetään opintojakson aikana erilaisiin yhteistyöharjoituksiin.

## Harjoitus 1

Tee uusi tiedosto repon juureen, ja laita sen nimeksi `oma.nimi.md`. Kopioi tiedoston sisällöksi [harjoitus1-malli.md](harjoitus1-malli.md):n sisältö, mutta korvaa kaikki aaltosulkeet (`{}`).

Kun olet saanut tiedoston valmiiksi:

1. Tallenna se
2. Tee pysyvä muutos (commit)
3. Julkaise pysyvä muutos GitHubiin
4. Tee GitHubissa vetopyyntö (pull request)

Kun opettaja on yhdistänyt (merged) ja sulkenut (closed) vetopyyntösi, on aika siirtyä harjoitukseen 2.

## Harjoitus 2

Nyt sinun tulisi vetää (pull) muiden tekemät muutokset alkuperäisestä reposta (upstreamistä) forkattuun repoosi (originiin). Tee tämä tehtävä uudelleen vähän ajan päästä, kun opettaja on yhdistänyt lisää muista vetopyyntöjä.

1. Avaa GitHub for Windowsin komentorivi (tools > open a shell here).
2. Kirjoita seuraavat komennot (URL:n voit kopioida GitHubista):
   
   ```shell
   git remote add upstream https://github.com/haapajarven-ammattiopisto/tiimityoskentely-harjoitus.git
   git pull upstream
   ```
   
3. Julkaise upstreamistä vetämäsi muutokset GitHubiin.
