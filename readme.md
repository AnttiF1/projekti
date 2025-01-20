# Git ja Versionhallinta: Ohje

## Mitä on versionhallinta?
Versionhallinta tallentaa tiedot ja niiden muutokset, toimii varmuuskopiona ja mahdollistaa yhteistyön (esim. GitHubin kautta).

## Mikä on Git?
Git on hajautettu versiohallintajärjestelmä, jolla seurataan muutoksia ja tehdään yhteistyötä.

## Mikä on GitHub?
GitHub on verkkopalvelu Git-repositorion jakamiseen, yhteistyöhön ja varmuuskopiointiin.

## Peruskomennot:
- **Alusta repositorio:** `git init`
- **Lisää tiedot indeksiin:** `git add .`
- **Luo commit:** `git commit -m "Viesti"`
- **Tarkista tila:** `git status`
- **Näytä commitit:** `git log`

## GitHub-yhteys:
- Kytke repositorio:  
  `git remote add origin https://github.com/Tunnus/Repositorio.git`
- Vie tiedot GitHubiin: `git push -u origin master`
- Hae muutokset GitHubista: `git pull`

## Haarat (Branch):
- Luo uusi haara: `git branch haara`
- Siirry haaraan: `git checkout haara`
- Yhdistä haara: `git merge haara`

Git ja GitHub helpottavat versionhallintaa ja yhteistyötä tehokkaasti!
