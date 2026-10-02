# AETHEL CELLULAR — Vercel Deploy

Production-grade private longevity institute — Zurich, London, Geneva.

## Deploy to Vercel (No Env Required)

1. Go to https://vercel.com/new
2. Drag & drop this entire folder OR upload the zip
3. Framework Preset: Other (Static)
4. Build Command: (leave empty)
5. Output Directory: . (root)
6. Deploy — site will be live instantly

No environment variables, no build step, no serverless functions.

## Structure
- index.html — full React 18 app via CDN (Tailwind, React, Babel)
- assets/images/ — 6 photorealistic clinical assets
  - clinic-interior-zurich.jpg
  - biomarker-sequencing-lab.jpg
  - physician-portrait-1.jpg
  - physician-portrait-2.jpg
  - cryo-chamber-detail.jpg
  - phlebotomy-kit-luxury.jpg
- vercel.json — cleanUrls + SPA rewrite

## Features Live
- Biological Age & DNAm PhenoAge Engine (live calculation)
- Currency Switcher CHF/GBP/EUR/USD
- 3 Diagnostic Tiers with allocation
- Biomarker Sequencing Panel (4 tabs)
- Confidential Clinical Admission Modal with dossier #AE-XXXX-CL confirmation
- Patient Portal drawer
- Export Confidential Health Summary

Swissmedic Regulated · ISO 15189:2022 · GCP/GLP Certified
