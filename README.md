# CommerceForge Pitch

Presentazione slide-by-slide per raccontare CommerceForge ad agenzie e partner.

## Caratteristiche

- deck full-screen con scroll verticale a snap
- navigazione da tastiera
- copy ridotto, una singola idea per slide
- visual system coerente con `commerceforge-site`
- media reali della demo + diagrammi SVG dedicati

## Run locale

```bash
npm run dev
```

Poi apri `http://localhost:4173/` se lanci il server dentro la cartella.

## Ordine narrativo

1. il limite dei temi
2. perché headless
3. routing e SEO
4. customer area B2C e B2B
5. Oxygen runtime
6. workflow Figma + AI
7. CommerceForge come offerta vendibile

## Repo GitHub + Vercel

Il progetto e` statico puro e puo` essere deployato direttamente su Vercel senza build step.

### 1. Pubblica su GitHub

```bash
cd /Users/me/Programmi/shopifylead/commerceforge-pitch
git init
git add .
git commit -m "Initial CommerceForge pitch"
git branch -M main
git remote add origin git@github.com:<account>/commerceforge-pitch.git
git push -u origin main
```

### 2. Collega a Vercel

1. Importa la repo `commerceforge-pitch`
2. Framework preset: `Other`
3. Build command: vuoto
4. Output directory: vuoto
5. Deploy

Poi assegna il dominio custom `pitch.commerceforge.dev`.

### Via CLI

```bash
cd /Users/me/Programmi/shopifylead/commerceforge-pitch
vercel
vercel --prod
```

La route principale resta `/` in inglese e `/it` in italiano.
