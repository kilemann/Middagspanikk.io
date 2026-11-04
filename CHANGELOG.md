# Endringslogg – Middags panikk™

## 1.2.0 – 2026-11-04
- Navn, versjon og info-knapp (i) øverst til venstre, med bruksanvisning og versjonsliste, som i de andre appene.

## 1.1.1 – 2026-11-04
Rettinger etter kodegjennomgang.
- Bokmerke-import: «1 båt hvitløk» blir hvitløk (fedd), «frisk spinat/estragon» havner under Frukt og grønt,
  kraft og fond under Hermetikk og saus, og «2 til 3 ss» leses som spenn. Kjente ingredienser matches på hele ord.
- Dialoger: har navn for skjermlesere, fokus holdes inni dialogen (Tab), resten av siden er låst mens den er åpen.
  Trykk utenfor et skjema med innskrevet tekst lukker det ikke lenger (bruk «Avbryt»).
- Bedre kontrast i lyst og mørkt tema (aksentfarge, grønn, stjerne, dempet tekst). Forbigåtte dager og utilgjengelige
  forslag dempes uten at teksten blir uleselig.
- Større trykkflater (minst 40 px) for stjerne, 🎲, ✕, antall personer, filterknapper og lukkeknapper.
- Oppskriftskort er nå en vanlig knapp med egen stjerne (ikke knapp inni knapp). Synlig fokusmarkering på avkrysning i handlelisten.
- Sidetittel følger visningen. Respekterer «reduser bevegelse». Fritekstfeltet har etikett. Språk satt til nb.
- Ingen horisontal scrolling på 320 px brede skjermer.
- Innholdssikkerhetspolicy (CSP) begrenser hvilke adresser siden kan snakke med: bare GitHub og siden selv.
- Hvis GitHub ikke svarer for en som kan redigere, vises den lagrede kopien på enheten i stedet for Pages-kopien.

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
