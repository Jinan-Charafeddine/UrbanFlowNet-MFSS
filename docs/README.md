# UrbanFlow-Net (MF-SS) — Docs

This folder contains paper artefacts, figures, and extra notes so others can
understand and reproduce the results.

## Figures
- `architecture.png` — model overview (CNN + ConvLSTM + GNN + stacking).
- `hazard_maps.png` — example Safe/Deviation/Unsafe maps (legend included).
- `coherent_structures.png` — velocity magnitude + absolute-error panels.
- `calibration_roc.png` — ROC (Unsafe) + reliability diagram (ECE).
- `efficiency_bars.png` — runtime vs LES/CNN (log-scale).
- `logo_generalization.png` — LOGO accuracy per geometry.
- `external_case.png` — square-cylinder case (mean + error).

> Put the images here and reference them in the main README when needed.

## Reproduction checklist
1. Prepare datasets as described in `../data/README.md`.
2. Create the environment:
   ```bash
   python -m venv .venv && source .venv/bin/activate
   pip install -r ../requirements.txt
