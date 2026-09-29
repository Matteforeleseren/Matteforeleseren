# Matteforeleseren

> Matematikk for elever og studenter – notater, oppgaver og ressurser samlet på ett sted.

🌐 **Nettside:** [matteforeleseren.github.io/Matteforeleseren/](https://matteforeleseren.github.io/Matteforeleseren/)

---

## Om prosjektet

**Matteforeleseren** er en personlig nettside for matematikkforelesning og formidling. Siden samler alt materiell jeg har utviklet gjennom mange år – forelesningsnotater, oppgaver, programmeringshefter, veiledninger og prosjektmateriell.

Nettsiden er bygget som en enkel, statisk side hostet på **GitHub Pages**, med en moderne forside, en portal (**Matteassistenten**) med alle kategorier, og en egen **Om meg**-side.

---

## Innhold

| Side | URL | Beskrivelse |
|---|---|---|
| 🏠 **Matteforeleseren** | [`/`](https://matteforeleseren.github.io/Matteforeleseren/) | Hovedside med klokke som følger musen |
| 📚 **Matteassistenten** | [`Matteassistenten/`](Matteassistenten/) | Portal med alle matematikk-kategorier |
| 👤 **Om meg** | [`Ommeg/`](Ommeg/) | Bakgrunn, erfaring og engasjement |

---

## Mappestruktur

```
Matteforeleseren/
├── index.html                          Hovedside (Matteforeleseren)
├── README.md                           Denne filen
│
├── Ommeg/
│   └── index.html                      Om meg
│
└── Matteassistenten/
    ├── index.html                      Portal med 7 kategorier
    ├── README.md                       README for Matteassistenten
    │
    ├── ENT3R/
    │   ├── index.html
    │   └── pdf/
    │       ├── ENT3R-Veiledningsheftet-Hefte1.pdf
    │       ├── ENT3R-ProgrammeringISkolen-AT-Hefte2.pdf
    │       └── ENT3R-Programmeringshefte-Hefte3.pdf
    │
    ├── MFI/
    │   ├── index.html                  Matematikk for ingeniørstudenter
    │   └── pdf/
    │       ├── MAT110-Programmeringshefte.pdf
    │       ├── MAT202-Programmeringshefte.pdf
    │       ├── Notat-Interpolasjon.pdf
    │       ├── ODE-Difflign-Likevekt.pdf
    │       └── Diffusjon-PDE-MAT201.pdf
    │
    ├── MFR/
    │   ├── index.html                  Matematikk for realfagsstudenter
    │   └── pdf/
    │       ├── Forkurs-UiB-h24.pdf
    │       ├── MFR-MAT101-h25.pdf
    │       ├── MFR-h25.pdf
    │       ├── Hefte-Kontrolloppgaver-MiP-ufasit.pdf
    │       ├── Hefte-kontrolloppgaver-MP-mfasit.pdf
    │       └── MiP-Programmeringsdel.pdf
    │
    ├── MFL/
    │   ├── index.html                  Matematikk for lærerstudenter
    │   └── pdf/
    │       └── MFL-MGUMAT402.pdf
    │
    ├── MFS/
    │   ├── index.html                  Medikamentregning
    │   └── pdf/
    │
    ├── Handout10klasse/
    │   ├── index.html                  Handout for 10. trinn
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
    │   ├── index.html                  Handout for VGS
    │   ├── 1P/
    │   ├── 1T/
    │   ├── 1P-Y/
    │   ├── R1/
    │   ├── R2/
    │   │   ├── index.html
    │   │   └── pdf/
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
        └── index.html                  Min CV
```

---

## Teknologi

- **Ren HTML og CSS** – ingen rammeverk eller byggeverktøy
- **Hostet på GitHub Pages**
- **Interaktiv hovedside** – med klokke som følger musen
- **Mobiltilpasset** – fungerer på telefon, nettbrett og PC
- **PDF-filer** organisert per kategori

---

## Design

### Hovedside (Matteforeleseren)

- 🕐 **Interaktiv klokke** som følger musen og deformeres når du drar
- 🖼️ **To bilder** som lastes automatisk fra Unsplash
- 🎨 **Grønn fargepalett:** `#6BBF59` (lysegrønn) og `#1E5F2E` (mørkegrønn)
- 🔤 **Fonter:** Georgia (overskrifter) + systemfonter (brødtekst)

### Matteassistenten

- 🎨 **Moderne portal** med 7 kort
- 🌈 **Fargekoder per kategori** – hver kategori har sin egen farge
- 📱 **Responsivt design** – 4 → 3 → 2 → 1 kolonner

### Undersider

- 📄 **Kort-baserte lister** for ressurser (PDF-er, lenker)
- 🎨 **Grønne aksenter** for å matche hovedsiden
- ✨ **Hover-effekter** for interaktivitet

---

## Slik legger du til nye ressurser

### 1. Last opp PDF-filen

1. Gå til riktig kategori-mappe (f.eks. `Matteassistenten/MFI/pdf/`)
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

## Relaterte lenker

- 📚 **Matteassistenten:** [README](Matteassistenten/README.md)
- 💻 **GitHub:** [Matteforeleseren/Matteforeleseren](https://github.com/Matteforeleseren/Matteforeleseren)
