# Middags panikk™ (repo Middagspanikk.io)
Middagsplanlegger for familien Kile: ukeplan, oppskrifter, forslag, handleliste og statistikk. Én HTML-fil (`index.html`).
Nettside: https://kilemann.github.io/Middagspanikk.io/

## Regler for alt arbeid i dette repoet
- Svar brukeren på norsk. Commit-meldinger på norsk, med versjon først (f.eks. «Appnavn 1.4.0: kort beskrivelse»).
- Hver endring får nytt versjonsnummer (MAJOR.MINOR.PATCH) og en linje i endringsloggen. Versjonen skal være lik på alle stedene under.
- Lever rett på `main` når resultatet er godt nok og testene er grønne. Kjør `git fetch origin main` og rebase før push.
- Testdrevet utvikling (TDD) bare når brukeren ber om det. Eksisterende tester kjøres alltid før push.
- Tekniske påstander skal sjekkes mot dokumentasjon eller kilde, ikke gjettes.
- Appen står på samlesida (kilemann.github.io). Den skal vise navn, versjon og en (i)-knapp øverst til venstre. (i) åpner info-vinduet med bruksanvisning og versjonsliste. Oppdater versjonslista der ved hver ny versjon.
- Publiseres med GitHub Pages fra `main` (rot). Det tar noen minutter før endringen er ute.

## Versjon står her
- `index.html`: `const APP_VERSION` og versjonslista i `infoForm()`
- `package.json`, `README.md` (tittel), `CHANGELOG.md`

## Tester
Ingen automatiske tester ennå. Sjekk i nettleser i lyst og mørkt tema, mobil og PC, før push.

## Viktig
- Data ligger i `meny.json` og skrives av appen via GitHub API når noen har låst opp med GitHub-nøkkel. Ikke endre den for hånd, og hent alltid siste `main` før push.
- Streng innholdssikkerhetspolicy (CSP) i `<head>`: bare siden selv og api.github.com. Nye eksterne adresser må legges til der.
