# 🎯 Problem Canvas Builder

Een interactieve web applicatie om gestructureerd problemen te analyseren en oplossingen te documenteren. Geïnspireerd op de Business Model Canvas, maar dan voor problem solving in software teams.

## ✨ Features

- 📝 **Volledig editeerbaar** - vul alle velden direct in de browser in
- ⭐️ **Impact rating** - klik op de sterren om prioriteit aan te geven
- 💾 **Opslaan & laden** - download canvassen als JSON en laad ze later weer
- 🖨️ **Print-ready** - maak direct PDF's voor meetings/presentaties
- 🎨 **Kleurgecodeerde secties** - overzichtelijke layout zoals Business Model Canvas
- 🚀 **Geen installatie nodig** - gewoon openen in je browser
- 🔒 **Privacy-first** - alle data blijft lokaal, geen database nodig

## 🚀 Quick Start

### Optie 1: Lokaal gebruiken
1. Download `index.html`
2. Open het bestand in je browser
3. Start met invullen!

### Optie 2: Hosten op GitHub Pages

#### Via GitHub Web Interface (geen Git kennis nodig):
1. Ga naar [github.com](https://github.com) en log in
2. Klik op **"New repository"** (groene knop rechtsboven)
3. Repository naam: `problem-canvas`
4. Maak het **Public** (voor gratis GitHub Pages)
5. Vink **"Add a README file"** aan
6. Klik **"Create repository"**
7. Klik op **"Add file"** → **"Create new file"**
8. Bestandsnaam: `index.html`
9. Kopieer de volledige HTML code uit `index.html` en plak in het grote tekstveld
10. Scroll naar beneden, klik **"Commit new file"**
11. Ga naar **Settings** (tab bovenaan)
12. Scroll naar **"Pages"** in het linker menu
13. Bij **"Source"**: selecteer **"main"** branch en **"/ (root)"** folder
14. Klik **"Save"**
15. Wacht 1-2 minuten ⏱️
16. Je app is nu live op: `https://jouwnaam.github.io/problem-canvas`

#### Via Git Command Line:
```bash
# Clone je repository
git clone https://github.com/jouwnaam/problem-canvas.git
cd problem-canvas

# Kopieer index.html naar de folder
cp /path/to/index.html .

# Commit en push
git add index.html
git commit -m "Add Problem Canvas Builder"
git push

# Enable Pages in Settings → Pages → Deploy from main branch
```

### Optie 3: Hosten op GitLab Pages

1. Maak een nieuwe repository op [gitlab.com](https://gitlab.com)
2. Upload `index.html`
3. Ga naar **Settings** → **Pages**
4. Enable Pages
5. Je app is live op: `https://jouwnaam.gitlab.io/problem-canvas`

## 📖 Hoe te gebruiken

### Een nieuw canvas maken
1. Open de applicatie in je browser
2. Klik op **"🆕 Nieuw Canvas"** (als je nog een oud canvas open hebt)
3. Vul de titel in bovenaan
4. Klik op de sterren om de impact rating in te stellen (1-5 sterren)
5. Vul alle secties in:
   - **Problem Statement** - wat is het kernprobleem?
   - **Context** - waarom is dit nu urgent?
   - **Current State** - wat zien we nu? (feiten)
   - **Root Causes** - waarom gebeurt dit?
   - **Desired State** - hoe zou het eruit moeten zien?
   - **Impact Op** - wat is de impact?
   - **Oplossing 1 & 2** - mogelijke oplossingen met pros/cons
   - **Stakeholders** - wie moet erbij betrokken worden?
   - **Aanbeveling** - wat adviseer je?
   - **Next Steps** - concrete acties

### Canvas opslaan
1. Klik op **"💾 Download JSON"**
2. Het bestand wordt automatisch gedownload (bv. `problem-canvas-testing-lambda.json`)
3. Bewaar dit bestand in een folder (bv. `/canvassen` of `/problem-canvasses`)
4. **Tip**: Voeg deze JSON files toe aan je Git repo als documentatie!

### Canvas laden
1. Klik op **"📂 Upload JSON"**
2. Selecteer een eerder opgeslagen JSON bestand
3. Het canvas wordt automatisch ingevuld

### Canvas printen of als PDF opslaan
1. Klik op **"🖨️ Print / PDF"**
2. In het print dialoog:
   - **Orientatie**: Landscape / Liggend (belangrijk!)
   - **Destination**: Kies "Save as PDF" of een printer
3. Klik op "Print" of "Save"

## 💡 Workflow Tips

### Voor individueel gebruik:
```
1. Nieuw probleem geïdentificeerd
   ↓
2. Open app → Nieuw Canvas
   ↓
3. Vul in tijdens analyse/meeting
   ↓
4. Download als JSON
   ↓
5. Bewaar in /canvassen folder
   ↓
6. Print/PDF voor presentatie
```

### Voor team gebruik:
```
1. Host app op GitHub/GitLab Pages
   ↓
2. Deel link met team
   ↓
3. Iedereen kan eigen canvassen maken
   ↓
4. JSON files delen via Slack/email/Git
   ↓
5. Teammembers kunnen canvas laden en bespreken
   ↓
6. Update canvas na feedback → download nieuwe versie
```

### Voor documentatie in Git:
```
project-repo/
├── docs/
│   └── problem-canvasses/
│       ├── 2024-10-testing-lambdas.json
│       ├── 2024-10-code-quality.json
│       └── 2024-11-deployment-pipeline.json
└── README.md
```

Dit maakt je problem-solving proces transparant en traceable!

## 🎨 Canvas Structuur

Het canvas is verdeeld in 4 rijen:

### Rij 1: Probleem Definitie
- **Problem Statement** (linkerkant) - kernprobleem in één oogopslag
- **Context** (rechterkant) - waarom nu urgent, wat is er gebeurd?

### Rij 2: Analyse
- **Current State** - feiten, wat zien we nu?
- **Root Causes** - onderliggende oorzaken
- **Desired State** - hoe zou het moeten zijn?
- **Impact Op** - wie/wat wordt geraakt?

### Rij 3: Oplossingen
- **Oplossing 1** - eerste voorstel met feasibility/effort
- **Oplossing 2** - alternatief voorstel met pros/cons

### Rij 4: Actie
- **Stakeholders** - wie moet betrokken worden?
- **Aanbeveling** - wat adviseren we?
- **Next Steps** - concrete acties met deadlines

## 🎯 Best Practices

### Bij het invullen:
- ✅ **Feiten boven meningen** - vooral in "Current State"
- ✅ **Specifiek zijn** - gebruik metrics en concrete voorbeelden
- ✅ **Geen blame game** - focus op het probleem, niet op personen
- ✅ **Eerlijk over trade-offs** - elke oplossing heeft nadelen
- ✅ **Actionable next steps** - met owners en deadlines
- ✅ **Gebruik bullets (▸)** - voor leesbaarheid

### Voor workshops:
1. **Pre-work**: Vul het canvas voor 80% in vóór de meeting
2. **Workshop**: Bespreek root causes en oplossingen met het team
3. **Post-workshop**: Update canvas met input, download finale versie
4. **Follow-up**: Print PDF en deel met stakeholders

### Formatting tips:
```
▸ Gebruik ▸ voor bullet points
🟢 Feasibility: Hoog
🟡 Feasibility: Middel  
🔴 Feasibility: Laag
🔨 Effort indicators (1-5 hamers)
```

## 🔧 Technische Details

- **Geen database** - alles draait in de browser
- **Geen server nodig** - pure HTML/CSS/JavaScript
- **Geen externe dependencies** - volledig standalone
- **Privacy-vriendelijk** - data verlaat je browser niet (behalve wanneer je download)
- **Browser support** - werkt in alle moderne browsers (Chrome, Firefox, Safari, Edge)

## 📦 Bestandsformaat

JSON files zijn simpel en leesbaar:
```json
{
  "title": "Testing Lambda & Step Functions",
  "rating": 5,
  "problem": "We kunnen Lambda's niet adequaat testen...",
  "context": "Laatste 2 sprints: 4 critical bugs...",
  ...
}
```

Dit maakt het makkelijk om:
- Te delen via email/Slack
- Op te slaan in Git
- Te bewerken met een text editor (als dat nodig is)
- Te vergelijken met diff tools

## 🤝 Delen met Team

### Via hosted app:
1. Host op GitHub/GitLab Pages
2. Deel link: `https://jouwnaam.github.io/problem-canvas`
3. Iedereen kan de app gebruiken
4. JSON files delen onderling

### Via Git repo:
```bash
# Clone repo
git clone https://github.com/team/documentation.git

# Open canvas app (lokaal of hosted)
# Upload JSON uit docs/problem-canvasses/

# Na update: download nieuwe versie
# Commit terug naar repo
git add docs/problem-canvasses/updated-canvas.json
git commit -m "Update canvas na team feedback"
git push
```

## 🐛 Troubleshooting

**Canvas laadt niet na upload?**
- Check of het bestand valid JSON is
- Probeer het opnieuw op te slaan vanuit de app

**Print ziet er niet goed uit?**
- Zorg dat je **Landscape/Liggend** als orientatie hebt geselecteerd
- Disable "Headers and footers" in print opties voor een cleaner PDF

**GitHub Pages werkt niet?**
- Check of je repo **Public** is (of een betaald account hebt)
- Wacht 1-2 minuten na het enablen van Pages
- Check Settings → Pages → zorg dat Source = main branch

**Wil je meerdere canvassen tegelijk bekijken?**
- Open de app in meerdere browser tabs
- Upload verschillende JSON files in elke tab

## 📝 Licentie

Open source - gebruik vrij voor je team!

## 🙋 Support

Vragen of suggesties? Open een issue in de GitHub repo of pas de code aan naar je eigen behoeften!

---

**Veel succes met je problem-solving! 🚀**