# Matteassistenten

> Notater, oppgaver og ressurser i matematikk – samlet på ett sted for elever, studenter og lærere.

🌐 **Nettside:** [matteforeleseren.github.io/Matteforeleseren/Matteassistenten/](https://matteforeleseren.github.io/Matteforeleseren/Matteassistenten/)

---

## Om prosjektet

**Matteassistenten** er en portal som samler matematikkressurser for ulike målgrupper – fra ungdomsskoleelever til ingeniørstudenter og lærerstudenter. Her finner du notater, oppgaver, programmeringshefter, veiledninger og prosjektmateriell.

Nettsiden er bygget som en enkel, statisk side hostet på **GitHub Pages**, med hver kategori i sin egen mappe og et felles utseende.

---

## Innhold

| Kategori | URL | Beskrivelse |
|---|---|---|
| 📘 ENT3R | [`ENT3R/`](ENT3R/) | Matematikkhjelp for elever – veiledningshefter for mentorer |
| 📗 Matematikk for ingeniørstudenter | [`MFI/`](MFI/) | Bokprosjekt, programmeringshefter og notater |
| 📕 Matematikk for realfagsstudenter | [`MFR/`](MFR/) | Støttelitteratur til brukerkurs ved UiB |
| 📙 Matematikk for lærerstudenter | [`MFL/`](MFL/) | Fagdidaktikk, emnesider og kompendium |
| 💊 Medikamentregning | [`MFS/`](MFS/) | Regneoppgaver for helsefaglige studier |
| 📄 Handout 10. klasse | [`Handout10klasse/`](Handout10klasse/) | Prosjektmateriell for 10. trinn |
| 📄 Handout VGS | [`HandoutVGS/`](HandoutVGS/) | Prosjektmateriell for videregående skole |
| 👤 Min CV | [`CV/`](CV/) | Erfaring og bakgrunn |

---

## Mappestruktur

```
Matteassistenten/
├── index.html                          Portalen med 7 kategorier
├── README.md                           Denne filen
│
├── ENT3R/
│   ├── index.html                      ENT3R-hovedside
│   └── pdf/
│       ├── ENT3R-Veiledningsheftet-Hefte1.pdf
│       ├── ENT3R-ProgrammeringISkolen-AT-Hefte2.pdf
│       └── ENT3R-Programmeringshefte-Hefte3.pdf
│
├── MFI/
│   ├── index.html                      Matematikk for ingeniørstudenter
│   └── pdf/
│       ├── MAT110-Programmeringshefte.pdf
│       ├── MAT202-Programmeringshefte.pdf
│       ├── Notat-Interpolasjon.pdf
│       ├── ODE-Difflign-Likevekt.pdf
│       └── Diffusjon-PDE-MAT201.pdf
│
├── MFR/
│   ├── index.html                      Matematikk for realfagsstudenter
│   └── pdf/
│       ├── Forkurs-UiB-h24.pdf
│       ├── MFR-MAT101-h25.pdf
│       ├── MFR-h25.pdf
│       ├── Hefte-Kontrolloppgaver-MiP-ufasit.pdf
│       ├── Hefte-kontrolloppgaver-MP-mfasit.pdf
│       └── MiP-Programmeringsdel.pdf
│
├── MFL/
│   ├── index.html                      Matematikk for lærerstudenter
│   └── pdf/
│       └── MFL-MGUMAT402.pdf
│
├── MFS/
│   ├── index.html                      Medikamentregning
│   └── pdf/
│
├── Handout10klasse/
│   ├── index.html                      Handout for 10. trinn (12 temaknapper)
│   └── pdf/
│       ├── Algebra-10Trinn.pdf
│       ├── Polynomer-10Trinn.pdf
│       ├── Ligningssett-10Trinn.pdf
│       ├── Funksjoner-10Trinn.pdf
│       ├── Linearefunksjoner-10Trinn.pdf
│       ├── Eksponentialfunksjoner-10Trinn.pdf
│       ├── Programmering-10Trinn.pdf
│       ├── Modellering-10Trinn.pdf
│       ├── Økonomi-10Trinn.pdf
│       ├── Statistikk-10Trinn.pdf
│       ├── Datamodellering-10Trinn.pdf
│       └── Geometri-10Trinn.pdf
│
├── HandoutVGS/
│   ├── index.html                      Handout for VGS (matematikk + realfag)
│   ├── 1P/
│   ├── 1T/
│   ├── 1P-Y/
│   ├── R1/
│   ├── R2/
│   │   ├── index.html                  Handout R2 (6 temaknapper)
│   │   └── pdf/
│   │       └── Handout-R2-*.pdf
│   ├── S1/
│   ├── S2/
│   ├── Fysikk1/
│   ├── Fysikk2/
│   ├── Kjemi1/
│   ├── Kjemi2/
│   ├── Biologi1/
│   ├── Biologi2/
│   ├── Geofag1/
│   ├── Geofag2/
│   ├── Teknologi1/
│   ├── Teknologi2/
│   ├── IT1/
│   ├── IT2/
│   ├── Programmering1/
│   ├── Programmering2/
│   └── Naturfag/
│
└── CV/
    └── index.html                      Min CV
```

---

## Teknologi

- **Ren HTML og CSS** – ingen rammeverk eller byggeverktøy
- **Hostet på GitHub Pages**
- **Mobiltilpasset** – fungerer på telefon, nettbrett og PC
- **PDF-filer** organisert per kategori
- **Ingen backend** – alle filer er statiske

---

## Design

- 🎨 **Fargepalett:** Grønn (`#6BBF59` / `#1E5F2E`) som hovedfarge
- 🔤 **Fonter:** Georgia (overskrifter) + systemfonter (brødtekst)
- 🌈 **Fargekoder per kategori** – hver kategori har sin egen farge
- 📱 **Responsivt design** – tilpasser seg alle skjermstørrelser

---

## Slik legger du til nye ressurser

### 1. Last opp PDF-filen

1. Gå til riktig kategori-mappe (f.eks. `MFI/pdf/`)
2. Klikk **"Add file" → "Upload files"**
3. Dra inn PDF-en og commit

### 2. Legg til lenken i `index.html`

Åpne `index.html` i samme kategori og legg til:

```html
<a href="pdf/ditt-filnavn.pdf" target="_blank" class="ressurs notat">
  <div class="ressurs-ikon">📄</div>
  <div class="ressurs-innhold">
    <h3>Tittel på ressursen</h3>
    <p>Kort beskrivelse av innholdet.</p>
    <span class="meta">Kategori · PDF</span>
  </div>
</a>
```

---

## Bidrag og tilbakemeldinger

Har du funnet feil, eller har forslag til forbedringer? Send gjerne en e-post til:

📧 **E-post:** [ahas@hvl.no](mailto:ahas@hvl.no)

Alle tilbakemeldinger tas imot med glede!

---

## Lisens

Innholdet er delt åpent med elever, studenter og lærere. Ta gjerne kontakt før gjenbruk.

---

## Relaterte sider

- 🏠 **Hovedside:** [Matteforeleseren](https://matteforeleseren.github.io/Matteforeleseren/)
- 💻 **GitHub:** [Matteforeleseren/Matteforeleseren](https://github.com/Matteforeleseren/Matteforeleseren)
