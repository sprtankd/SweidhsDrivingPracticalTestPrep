# Körprov Cockpit 🇸🇪

Interactive trainer for the **Swedish practical driving test (körprov B)**, modelled on the
**Volvo XC40 Recharge** (fully electric) and **Volvo XC60 Recharge T8** (plug-in hybrid).

Single file, no build step, works offline after first load (Google Fonts are the only external resource).

## What's inside

- **Stalks** — interactive left stalk (indicators, lighting collar O/AUTO/halvljus, high beam,
  AHB, rear fog) and right stalk (single sweep, INT/rain sensor, normal, fast, front/rear wash,
  rear wiper, sensitivity thumbwheel), with a live telltale cluster and animated windscreen.
- **Examiner drill** — 10 random spoken-style commands ("Blinka höger…"), validated against
  what you actually do on the stalks. Score, streak, hints.
- **Checks** — säkerhetskontroll study cards: inside / outside / under the bonnet / other,
  with XC40-EV and XC60-PHEV specific notes (no oil on the EV, no dipstick on the T8, etc.).
- **Quiz** — examiner-style multiple choice with explanations.

## Deploy to GitHub Pages

1. Create a repo and push this folder (just `index.html` + this README).
2. Repo **Settings → Pages → Source: Deploy from a branch**, branch `main`, folder `/ (root)`.
3. Open `https://<username>.github.io/<repo>/` on your phone — add to Home Screen for an app feel.

## Disclaimer

Unofficial practice aid. Controls modelled on Volvo CMA/SPA platform manuals — always verify
against the actual driving-school car. Sources: Trafikverket (körprov B), Volvo Cars support.
