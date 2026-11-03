# Finansų harmonija V20

Testavimo svetainė: https://albertborkovski-cmd.github.io/finansu-harmonija-v20/

Leidimas paruoštas 2026-11-03. Šioje saugykloje yra sukompiliuota svetainė ir tikslus programos išeities failų archyvas [source-v20.zip](./source-v20.zip). Failų SHA-256 kontrolinės sumos pateiktos [source-manifest.json](./source-manifest.json), leidimo informacija — [release.json](./release.json).

## Testavimas

- Vidinis demonstracinis naudotojas: `albertborkvski@gmail.com`.
- Išorinis demonstracinis naudotojas: `aurika.z@meso.lt`.
- Naudokite išgalvotą testinį slaptažodį: bent 6 simboliai, viena didžioji raidė ir specialus simbolis. Tikro slaptažodžio nenaudokite.

Tai demonstracinis prototipas. GitHub Pages neturi serverinio autentifikavimo, bendros duomenų bazės, tikro OCR vykdymo ar laiškų siuntimo serverio. Nenaudokite konfidencialių dokumentų. Duomenys saugomi naršyklėje; atskiram testavimui rekomenduojamas atskiras naršyklės profilis. Vietiniai `.env` ir `.meso-shared-data.json` nepublikuoti.

## Patikra

Tipų patikra, gamybinis surinkimas ir 111 tikslinių testų praėjo. Visa testų patikra: 733 praėjo, 10 senesnių testavimo aplinkos klaidų (`import.meta` / CommonJS ir `useWorkspaceExpansion` priklausomybių imitacijos).

V19 ir ankstesnės saugyklos nepakeistos. Ši saugykla skirta publikavimo artefaktams; neperrašykite jos vietinės programos Git istorija.
