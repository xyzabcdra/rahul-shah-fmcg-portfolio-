# Rahul Shah — FMCG Sales & Marketing Portfolio

A responsive React + Vite portfolio with a dark/cyan visual style, detailed business journey, interactive case studies, and Rahul's supplied professional portrait.

## Run locally

Requirements: Node.js 18+.

```bash
npm install
npm run dev
```

## Build for production

```bash
npm run build
npm run preview
```

## Deploy to Vercel

### Option A — GitHub (recommended)
1. Create a new repository on GitHub.
2. Upload the contents of this folder to the repository (the `package.json` and `index.html` should be at the repository root).
3. Sign in to Vercel and choose **Add New → Project**.
4. Import the GitHub repository.
5. Framework preset: **Vite**. Build command: `npm run build`. Output directory: `dist`.
6. Click **Deploy**.

### Option B — Vercel CLI
1. Install Node.js.
2. In this folder run `npm install`.
3. Install the Vercel CLI with `npm install -g vercel`.
4. Run `vercel` and follow the prompts. For production, run `vercel --prod`.

The portrait is stored locally at `public/images/rahul-shah.png` and is bundled by Vite. No external image hosting is required.

## Personalisation
- LinkedIn URL is in `src/main.jsx`.
- Contact email and phone numbers are included as clickable `mailto:` and `tel:` links.
- Sales/retailer figures are clearly described as approximate recollections, not audited results.
- Education currently says MBA Marketing at SSSIHL, consistent with the supplied LinkedIn screenshot. Confirm this before publishing if your enrollment status has changed.
