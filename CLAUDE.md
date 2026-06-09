# Traktor og Maskin AS — Felles arbeidsrepo

Dette repoet er det felles arbeidsområdet for teamet hos Traktor og Maskin AS.
Her lagres prosjekter, møtereferat, driftsplan, mockups og interne verktøy.

## Teamet

| Person | Rolle |
|--------|-------|
| Vidar  | Daglig leder / utviklingsansvarlig |
| Tom    | Utvikler |
| Trond  | Kollega — bidrar med møtereferat og Dølen-produkter |

## Repostruktur

```
TM/
├── Vidar/              — Vidars personlige arbeidsmappe
├── Tom/                — Toms personlige arbeidsmappe
├── Trond/              — Tronds personlige arbeidsmappe
├── prosjekter/
│   ├── aktive/         — Pågående prosjekter
│   ├── parkert/        — Prosjekter på vent
│   └── fullfort/       — Avsluttede prosjekter
├── motereferat/        — Møtereferat sortert per år
│   └── 2026/
├── driftsplan/         — Driftsplan og fremdriftsplaner
├── mockups/            — Skisser og designutkast
└── modules/            — Interne verktøy og kalkulatorer
```

## Viktige regler — les dette først

### ALDRI rør disse mappene
- `modules/kalkulatorer/tilhengerkalkulator/`
- `modules/kalkulatorer/leasingkalkulator/`

Disse er innebygd via iframe i nettbutikken. Endringer kan ødelegge kalkulatorer for kunder.

### Prosjektfiler
- Bruk markdown (`.md`) for all dokumentasjon
- Prosjekter får egen mappe under `prosjekter/aktive/` med en `README.md` som beskriver status
- Når et prosjekt er ferdig, flyttes mappen til `prosjekter/fullfort/`

### Møtereferat
- Lagres under `motereferat/2026/` med filnavn på formatet `YYYY-MM-DD-tema.md`
- Eksempel: `2026-06-09-ukesmote.md`

### Commits
- Skriv commitmelding på norsk
- Beskriv hva som ble endret og hvorfor

## Kontekst for Claude

- Dette er et internt repo for Traktor og Maskin AS, ikke offentlig deling
- Repoet brukes som felles kunnskapsbase — søk her før du svarer på spørsmål om prosjektstatus
- modulhub.no er et separat privat prosjekt og er ikke del av dette repoet
