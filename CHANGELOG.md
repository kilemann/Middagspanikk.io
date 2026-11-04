# Endringslogg – Middags panikk™

## 1.1.0 – 2026-11-04
- Hent oppskrifter fra nettsider med et bokmerke («📥 Til Middags panikk»). Det leser oppskriften i schema.org-format
  og åpner «Ny rett» ferdig utfylt. Installeres fra menyen eller «📥 Fra nettside» under Oppskrifter.
- Ingredienser tolkes: «400g kjøttdeig», «1 1/2 dl», «½ ts», «2–3 fedd» (største tall brukes), «2 x 400 g», ml/cl til dl,
  «klype» og linjer uten mengde blir «etter smak». Avdeling gjettes fra ingredienser du har fra før og et ordforråd.
- Kategori gjettes (suppe, grill, vegetar, fisk, kylling, kjøtt), antall porsjoner og tid hentes fra siden.
- Ber om opplåsing først hvis enheten ikke kan redigere. Finnes retten fra før, vises den i stedet.
- Retter kan ha lenke til originaloppskriften. Vises som «🔗 Se fremgangsmåten hos …».

## 1.0.0 – 2026-10-30
Første versjon.
- Ukeplan mandag–søndag med ukenavigasjon, 3 eller 4 personer per dag, fritekst (f.eks. «Rester»), 🎲 nytt forslag og angre.
- 33 forhåndsutfylte norske middagsretter med strukturerte ingredienser (mengde, enhet, navn, butikkavdeling), skrevet for 4 personer.
- Smarte forslag: raske retter på hverdager, kosemat i helgen, ingen rett to dager på rad, maks én fiskemiddag per uke.
- «✨ Foreslå ukemeny» med forhåndsvisning, bytte av enkeltdager og valg om å erstatte planlagte dager.
- Handleliste fra ukeplanen: skalert til antall personer, like ingredienser slått sammen, gruppert etter avdeling.
  Velg hvilke dager som tas med, hak av varer, skjul kjøpte, ekstra varer og deling/kopiering.
- Oppskrifter med søk, kategorifilter, favorittfilter og sortering. Egen favorittvisning.
- Statistikk: mest brukte middager, fiskemiddager per måned, hverdagsmat mot helgekos, kategorier og nøkkeltall.
- Lyst og mørkt tema (eller følg enheten). Eksport og import av JSON.
- Lagring i `meny.json` i GitHub-repoet. Redigering låses opp med GitHub-nøkkel, som i Vinyl Vault.
