# Middags panikk™ v1.0.0
Middagsplanlegger for familien Kile: ukeplan, oppskrifter, smarte forslag, handleliste, favoritter og statistikk.

Åpne: https://kilemann.github.io/Middagspanikk.io/

## Slik virker lagringen
- Alt ligger i `meny.json` i dette repoet. Alle som åpner lenken ser planen, men kan ikke endre den.
  Filen lages automatisk første gang noen lagrer, med 33 forhåndsutfylte retter.
- For å redigere: trykk **🔒 Lås opp** og lim inn en GitHub-nøkkel:
  1. https://github.com/settings/personal-access-tokens/new
  2. Repository access: **Only select repositories** → **Middagspanikk.io**
  3. Repository permissions: **Contents: Read and write**
- Endringer lagres til GitHub 1 minutt etter siste endring, eller straks med «💾 Lagre nå» og når appen legges i bakgrunnen.
  Nøkkelen lagres bare på enheten. Hver lagring blir en commit, så all historikk finnes i GitHub.
- Avhaking i handlelisten lagres bare på enheten, så alle kan hake av uten nøkkel.

## Forslag
- Hverdager: retter på 30 min eller mindre prioriteres.
- Helg: helgekos, grill og retter som tar tid prioriteres.
- Aldri samme rett to dager på rad, helst ikke to ganger samme uke. Maks én fiskemiddag per uke.
- Grill trekkes ned utenfor mai–september. Retter brukt de siste 4 ukene trekkes ned.

Endringer: se [CHANGELOG.md](CHANGELOG.md).
