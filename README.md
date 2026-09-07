# Very Few Known Terrorists

An individual **web commentary** on:

> Verhelst, H.M., Stannat, A.W. & Mecacci, G. (2020). *Machine Learning Against Terrorism: How Big Data Collection and Analysis Influences the Privacy-Security Dilemma.* **Science and Engineering Ethics** 26(6), 2975–2984. [doi:10.1007/s11948-020-00254-w](https://pmc.ncbi.nlm.nih.gov/articles/PMC7755624/)

Written for the collective digital exploration **“From Data Subject to Target: the platformisation of surveillance capitalism in security governance”**, strand: *machine learning & defence industries*.

## The argument

The paper indicts mass surveillance on **efficacy** grounds — class imbalance, the curse of dimensionality, spurious correlations. This commentary accepts the mathematics and contests the strategy on three points:

1. **An efficacy critique is a wasting asset.** It concedes that surveillance would be worth its privacy cost if it worked, handing its own expiry date to the vendors it means to restrain.
2. **The paper undersells its own figure.** Error *volume* is the weak number; **precision** is the governing one, and precision collapses at low base rates while accuracy never moves.
3. **There is no theory of the vendor.** The paper addresses a sovereign policymaker for whom inaccuracy is a cost. Once surveillance is procured rather than built, false positives become demand — leads, review seats, contract renewals.

It also supplies the case the paper omits: **NSA SKYNET**, where the same three failure modes were operationalised over 55 million Pakistani phone records.

## Structure (per the brief)

| § | Requirement | Section |
|---|---|---|
| 1 | Topic, central question, working hypotheses | The exploration this commentary belongs to |
| 2 | Article analysis: field, angle, method, author, arguments | Three failures of a machine |
| 3 | Point of view on the article | Right about the machine, wrong about the fight |
| 4 | Light shed on the exploration | The loophole is not a bug |

**Word count: 968** (brief: 700–1,000). A live counter in the page's left rail computes this from the marked paragraphs at load time.

## Multimedia

All four figures are **original work built for this page** — no stock imagery, no third-party media, no copyright exposure.

- **Hero canvas** — a 10,000-mark field with a single true positive.
- **Fig. 1 — The base-rate machine** *(interactive)*. Sliders for population, base rate, sensitivity and specificity; live confusion-matrix arithmetic. Demonstrates the precision collapse the paper doesn't compute.
- **Fig. 2 — Hear the haystack** *(audio)*. A Web Audio sonification: dry ticks for cleared individuals, a sustained tone for a true positive. Class imbalance as a silence you sit through.
- **Fig. 3 — SKYNET, to scale**. The 0.008–0.18% error band rendered at true proportion against 55m records.
- **Fig. 4 — Two models of the same system** *(SVG)*. The paper's balance-scale vs. the procurement loop in which error is revenue.

Fully responsive, light/dark themed, keyboard-accessible, and `prefers-reduced-motion` aware.

## Before you publish

Search `index.html` for `Your Name` (two places, both marked with `▼▼`) and replace with your name.

## Deploy to GitHub Pages

```bash
gh repo create very-few-known-terrorists --public --source=. --push
gh api -X POST repos/:owner/very-few-known-terrorists/pages -f 'source[branch]=main' -f 'source[path]=/'
```

No `gh`? Create an empty repo on github.com, then:

```bash
git remote add origin https://github.com/<you>/very-few-known-terrorists.git
git push -u origin main
```

Then **Settings → Pages → Source: Deploy from a branch → `main` / `(root)`**. The site appears at `https://<you>.github.io/very-few-known-terrorists/` within a minute or two.

## Colophon

Single self-contained `index.html`; no build step, no dependencies, no tracking. Set in Zilla Slab, Source Serif 4 and IBM Plex Mono. Palette: grey-green board stock, petrol ink, ochre reserved for the vanishing true positive, crimson reserved exclusively for false positives.
