# ALT-AI Marker

Mark your images as AI-generated — the easy way.

> **Languages / Sprog:** [English](#english) · [Dansk](#dansk) — more languages can be added later. In the repo, the English version lives in `README.md` and the Danish version in `docs/README.da.md`; additional languages follow the same pattern (`docs/README.de.md`, etc.).

<a id="english"></a>

**ALT-AI Marker** stamps an "AI" badge onto images so viewers can immediately see that the content was created or modified with artificial intelligence. It supports custom badge size, transparency, margin, position, and color — and saves the marked copy as a new file with an `_ai` suffix, so your originals are **never touched**.

Built to support transparency obligations for AI-generated content (e.g. the EU AI Act's marking requirements for synthetic media).

---

## Why

AI-generated images are everywhere. Marking them clearly is:

- **Good practice** — honest labeling builds trust with clients and audiences.
- **Increasingly required** — the EU AI Act (Art. 50) introduces transparency obligations for AI-generated and manipulated content.
- **Simple to do right** — one drag-and-drop, and every exported image carries a visible badge.

## Features

- ✅ Stamp an "AI" badge (label pill or icon-only) on any image
- ✅ Choose **size** (relative to image dimensions)
- ✅ Choose **transparency** (0–90 %)
- ✅ Choose **margin** (distance from the image edge)
- ✅ Choose **corner** (bottom-right / bottom-left / top-right / top-left)
- ✅ Choose **badge color**
- ✅ **Batch mode** — mark many images at once
- ✅ Output saved as `originalname_ai.png` — originals are never modified
- ✅ 100 % local and offline — no uploads, no cloud, no accounts

## Badge assets

The official badge graphics used by ALT-AI Marker are kept in the project's badge folder:

```
C:\Users\henri\Dropbox\Privat\Nenolink\AI\AI-mærkning\AlT-AI\badges
```

Any `.png` badge placed in this folder is available as a badge style in the app.
(For the GitHub repo, badge assets are stored in `assets/badges/` — keep the Dropbox folder and the repo folder in sync.)

## Usage

1. Open ALT-AI Marker (no install needed once the standalone `.exe` is released).
2. Drag & drop one or more images — or click **Choose images…**.
3. Tune the badge with the sliders:
   - **Size** — badge height, as % of the smallest image side
   - **Margin** — distance from the edge, as % of the smallest image side
   - **Transparency** — 0 % fully opaque, 90 % nearly invisible
   - **Position / color** — pick any corner and color
4. Preview updates live. Use **← →** to browse images in a batch.
5. Click **Save as …_ai**. Each image is saved next to the original as `name_ai.png`.

## Output naming

| Original | Saved as |
|---|---|
| `meeting-photo.jpg` | `meeting-photo_ai.png` |
| `hero.png` | `hero_ai.png` |

The `_ai` file is always a **new file** — the original is left exactly as it was.

## Repository

📍 <https://github.com/nenolinkdk/alt-ai-marker>

```
alt-ai-marker/
├── assets/badges/      # badge graphics (synced with the local badges folder)
├── docs/               # usage guide, screenshots
├── src/                # application source
├── README.md
└── LICENSE
```

Releases page: installable Windows builds will be published under **Releases** so non-technical users can download a `.exe` directly — no development tools needed.

## Roadmap

- [ ] Standalone Windows app (`.exe`)
- [ ] Custom badge images from the badges folder
- [ ] EXIF metadata marking (IPTC "Digital Source Type: AI-generated")
- [ ] Optional "AI" watermark for videos

## License

To be decided — see `LICENSE` in the repo.

---

<a id="dansk"></a>

# ALT-AI Marker (dansk)

Markér dine billeder som AI-genererede — den nemme måde.

**ALT-AI Marker** sætter et "AI"-mærke på billeder, så alle straks kan se, at indholdet er skabt eller ændret med kunstig intelligens. Du kan selv vælge mærkets størrelse, gennemsigtighed, margen, placering og farve — og det markerede billede gemmes som en ny fil med `_ai` til sidst, så dine originaler **aldrig bliver ændret**.

Lavet til at understøtte krav om mærkning af AI-genereret indhold (fx EU's AI-forordnings transparenskrav til syntetisk medieindhold).

---

## Hvorfor

AI-genererede billeder er overalt. Tydelig mærkning er:

- **God praksis** — ærlig mærkning skaber tillid hos kunder og følgere.
- **Efterhånden et krav** — EU's AI-forordning (art. 50) indfører transparenskrav for AI-genereret og AI-manipuleret indhold.
- **Nemt at gøre ordentligt** — ét drag-and-drop, og hvert eksporteret billede bærer et synligt mærke.

## Funktioner

- ✅ Sæt et "AI"-mærke (tekst-pille eller kun ikon) på ethvert billede
- ✅ Vælg selv **størrelse** (relativt til billedets dimensioner)
- ✅ Vælg selv **gennemsigtighed** (0–90 %)
- ✅ Vælg selv **margen** (afstand til billedkanten)
- ✅ Vælg selv **hjørne** (nederst til højre / venstre, øverst til højre / venstre)
- ✅ Vælg selv **mærkefarve**
- ✅ **Batch-tilstand** — mærk mange billeder på én gang
- ✅ Output gemmes som `originalnavn_ai.png` — originalerne ændres aldrig
- ✅ 100 % lokalt og offline — ingen upload, ingen sky, ingen konti

## Mærke-aktiver

De officielle mærke-grafikker, som ALT-AI Marker bruger, ligger i projektets mærke-mappe:

```
C:\Users\henri\Dropbox\Privat\Nenolink\AI\AI-mærkning\AlT-AI\badges
```

Alle `.png`-mærker i denne mappe kan vælges som mærkestil i appen.
(I GitHub-repoet ligger mærkerne i `assets/badges/` — hold Dropbox-mappen og repo-mappen synkroniseret.)

## Sådan bruger du den

1. Åbn ALT-AI Marker (ingen installation nødvendig, når den selvstændige `.exe` er udkommet).
2. Træk ét eller flere billeder ind — eller klik på **Vælg billeder…**.
3. Justér mærket med sliderne:
   - **Størrelse** — mærkets højde, i % af billedets mindste side
   - **Margen** — afstand fra kanten, i % af billedets mindste side
   - **Gennemsigtighed** — 0 % helt uigennemsigtig, 90 % næsten usynlig
   - **Placering / farve** — vælg hjørne og farve
4. Forhåndsvisningen opdateres løbende. Brug **← →** til at bladre gennem billeder i en batch.
5. Klik på **Gem som …_ai**. Hvert billede gemmes ved siden af originalen som `navn_ai.png`.

## Navngivning af output

| Original | Gemmes som |
|---|---|
| `mødefoto.jpg` | `mødefoto_ai.png` |
| `hero.png` | `hero_ai.png` |

`_ai`-filen er altid en **ny fil** — originalen forbliver præcis, som den var.

## Repository

📍 <https://github.com/nenolinkdk/alt-ai-marker>

```
alt-ai-marker/
├── assets/badges/      # mærke-grafikker (synkroniseret med den lokale mærke-mappe)
├── docs/               # vejledning, skærmbilleder, README.da.md m.fl. sprog
├── src/                # applikationens kildekode
├── README.md
└── LICENSE
```

Releases: installerbare Windows-builds udgives under **Releases**, så alle — også uden teknisk baggrund — kan downloade en `.exe` direkte uden udviklingsværktøjer.

## Roadmap

- [ ] Selvstændig Windows-app (`.exe`)
- [ ] Egne mærke-billeder fra mærke-mappen
- [ ] EXIF-metadata-mærkning (IPTC "Digital Source Type: AI-generated")
- [ ] Eventuelt "AI"-vandmærke til video

## Licens

Afgøres senere — se `LICENSE` i repoet.