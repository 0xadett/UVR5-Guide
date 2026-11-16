# UVR5 Guide

Minimal reference and quick-setup lookup for **Ultimate Vocal Remover v5.6**.

- **Web Guide:** [0xadett.github.io/UVR5-Guide](https://0xadett.github.io/UVR5-Guide/)
- **PDF Handbook:** [Ultimate_Vocal_Remover_5_Guide.pdf](./Ultimate_Vocal_Remover_5_Guide.pdf)
- **Official UVR v5.6 Download:** [Anjok07/ultimatevocalremovergui/releases/tag/v5.6](https://github.com/Anjok07/ultimatevocalremovergui/releases/tag/v5.6)

## Model Reference

| Task | Process Method | Default (v5.6) | Download Center Upgrade |
| :--- | :--- | :--- | :--- |
| Lead Vocals | `MDX-Net` | `UVR-MDX-NET-Inst_HQ_3` | `Kim_Vocal_2` / `MDX23C-8KFFT-InstVoc_HQ` |
| Instrumental / Karaoke | `MDX-Net` | `UVR-MDX-NET-Inst_HQ_3` | `UVR-MDX-NET-Karaoke-2` |
| 4-Stem Split | `Demucs` | `v4 \| htdemucs` | `v4 \| htdemucs_ft` |
| 6-Stem Split (+ Guitar/Piano) | `Demucs` | — | `v4 \| htdemucs_6s` |
| De-Reverb & De-Echo | `VR Arch` | — | `UVR-DeEcho-DeReverb` |
| Lead vs. Harmony | `VR Arch` | — | `5_HP-Karaoke-UVR` / `6_HP-Karaoke-UVR` |
| Noise Removal | `VR Arch` | `UVR-DeNoise-Lite` | `UVR-DeNoise` |
| Ensemble Blending | `Ensemble Mode` | Any 2+ models | `MDX-Net` + `Demucs v4` |
