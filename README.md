# Hardware‑Centric Analysis of Analog FM and Digital PCM on the ETT‑101

A structured, experiment‑centric repository for **Analog Frequency Modulation (FM)** and **Digital Pulse‑Code Modulation (PCM)** using the **Emona ETT‑101** modular trainer. Each experiment is documented as a mini‑report:

**Overview → Setup → Procedures → Data → Analysis → Results → Discussion → QA**

## Repository Navigation
- `01_FM/` — Frequency Deviation (Δf), Modulation Index (β=Δf/fm), Spectrum around fc
- `02_PCM/` — Nyquist sampling verification, Quantization and SNR vs bits, Codec loopback/BER
- `Data_Dictionary.md` — filename → variable → figure mapping (traceability)
- `LICENSE`, `.gitignore` — housekeeping

## Quick Start
1. Open `01_FM/README.md` or `02_PCM/README.md`.
2. Follow **Procedures**; log measurements in `Data/` (CSV/XLSX).
3. Upload oscilloscope screenshots in `Waveforms/`.
4. Compute metrics in `Analysis.md`.
5. Write your insights in `Results.md` & `Discussion.md`.

## Standards
- **Filenames**: `PartX_Context_Descriptor.ext`  
- **Units**: Hz, kHz, V, dB  
- **Math**: Markdown LaTeX

## References
- Hardware platform: **Emona ETT‑101** communications trainer (FM & PCM capable) [1](https://www.emona-tims.com/emona-product/compact-experimenter/)
- Each experiment includes its own internal references
