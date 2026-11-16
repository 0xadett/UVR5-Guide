# Ultimate Vocal Remover 5 (UVR5) — Interactive Guide & PDF Handbook

[![Live Web Guide](https://img.shields.io/badge/Live_Guide-GitHub_Pages-2563eb?style=for-the-badge)](https://0xadett.github.io/UVR5-Guide/)
[![Download PDF](https://img.shields.io/badge/Download-PDF_Handbook-059669?style=for-the-badge)](./Ultimate_Vocal_Remover_5_Guide.pdf)
[![Official UVR v5.6](https://img.shields.io/badge/Official_Software-UVR_v5.6-0f172a?style=for-the-badge)](https://github.com/Anjok07/ultimatevocalremovergui/releases/tag/v5.6)

A practical, plain-English guide and interactive setup tool for **Ultimate Vocal Remover v5 (UVR5)**—designed to help musicians, remixers, and producers understand UVR5's interface, AI separation engines, hardware settings (NVIDIA CUDA GPU & CPU/Apple Silicon), and DAW stem workflows.

---

## Quick Links

- **Interactive Web Guide (GitHub Pages):** [https://0xadett.github.io/UVR5-Guide/](https://0xadett.github.io/UVR5-Guide/) *(includes the live "What Should I Use?" Setup Recommender)*
- **Downloadable PDF Handbook:** [Ultimate_Vocal_Remover_5_Guide.pdf](./Ultimate_Vocal_Remover_5_Guide.pdf)
- **Download Official UVR5 Software (v5.6):** [Anjok07/ultimatevocalremovergui v5.6 Release](https://github.com/Anjok07/ultimatevocalremovergui/releases/tag/v5.6)

> **Attribution:** Ultimate Vocal Remover GUI is open-source software created and maintained by **Anjok07** and **aufr33**. Always download the official installer from the [Anjok07/ultimatevocalremovergui releases page](https://github.com/Anjok07/ultimatevocalremovergui/releases/tag/v5.6).

---

## What's Included

1. **Interactive Setup Recommender (`index.html`)** — Pick your goal (lead vocals, instrumental, 4-stem, 6-stem, de-reverb, harmony removal, de-noise) and hardware (NVIDIA GPU vs. CPU / Integrated Graphics) to get exact model and parameter settings instantly.
2. **60-Second Quick-Start & Sample Mode Guide** — How to test models in seconds before committing to a full track render.
3. **Visual Interface Map** — Breakdown of all 5 UVR5 UI zones and right-column sliders (`GPU Conversion`, `Window Size`, `Aggression Setting`, `Segment Size`, `Overlap`, `Shifts`).
4. **Separation Engine Breakdown & Model Cheat-Sheet** — When to use `MDX-Net`, `Demucs v4`, `VR Architecture`, and `Ensemble Mode`.
5. **Step-by-Step DAW Recipes** — Workflows for dry remix vocals, karaoke tracks, multi-track stems for Ableton Live / FL Studio / Logic Pro, and built-in Audio Tools.

---

## Quick Mode Cheat-Sheet

| Goal | Process Method | Starter Model (v5.6) | Top Download Center Upgrade |
| :--- | :--- | :--- | :--- |
| Clean Vocals + Instrumental | `MDX-Net` | `UVR-MDX-NET-Inst_HQ_3` | `Kim_Vocal_2` / `MDX23C-8KFFT-InstVoc_HQ` |
| Karaoke (Keep Backing Vocals) | `MDX-Net` | `UVR-MDX-NET-Inst_HQ_3` | `UVR-MDX-NET-Karaoke-2` |
| 4 Stems (Vocals, Drums, Bass, Other) | `Demucs` | `v4 \| htdemucs` | `v4 \| htdemucs_ft` |
| 6 Stems (+ Guitar & Piano) | `Demucs` | — | `v4 \| htdemucs_6s` |
| Remove Reverb / Echo from Vocals | `VR Architecture` | — | `UVR-DeEcho-DeReverb` |
| Separate Lead Vocal from Harmonies | `VR Architecture` | — | `5_HP-Karaoke-UVR` / `6_HP-Karaoke-UVR` |
| Remove Hiss / Background Noise | `VR Architecture` | `UVR-DeNoise-Lite` | `UVR-DeNoise` |

---

## Enabling GitHub Pages (For Repo Maintainers)

This repository includes both `index.html` at the root and a GitHub Actions workflow at `.github/workflows/pages.yml`:
1. Open **Settings → Pages** in this GitHub repository.
2. Under **Build and deployment**, choose either **GitHub Actions** or **Deploy from a branch** (`main` / `/ (root)`).
3. Your live guide and PDF download button will be published at `https://0xadett.github.io/UVR5-Guide/`.
