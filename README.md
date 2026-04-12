# Discrete Preamps

This repository contains two discrete audio preamplifier designs intended primarily for HF receiver applications (speech, not high-fidelity music).  

Each design includes:
- KiCad 10 schematic and PCB files  
- Gerber files for fabrication  
- PDF exports for easy viewing without KiCad  

---

## Preamp K1

Designed by M. Kellett, this preamplifier is optimised for speech signals in HF receivers.

- **Gain:** ~28 dB  
- **Bandwidth (-3 dB):** ~150 Hz to 10 kHz (approximate)  
- **Use case:** Moderate gain front-end with relatively wide speech bandwidth  

### Schematic
![K1 Schematic](preamp_k1/k1_schematic_rev1_0.png)

### PCB Top
![K1 Top](preamp_k1/k1_top.png)

### PCB Underside
![K1 Underside](preamp_k1/k1_underside.png)

---

## Preamp K2

Also designed by M. Kellett, this version provides higher gain and a slightly narrower bandwidth, making it suitable where additional amplification is required.

- **Gain:** ~45 dB  
- **Bandwidth (-3 dB):** ~100 Hz to 7 kHz (approximate)  
- **Use case:** Higher gain stage for weak signal amplification  

### Schematic
![K2 Schematic](preamp_k2/k2_schmematic_rev1_0.png)

### PCB Top
![K2 Top](preamp_k2/k2_top.png)

### PCB Underside
![K2 Underside](preamp_k2/k2_underside.png)

---

## Notes

- These designs are intended for experimentation and adaptation.  
- Component values and performance figures are approximate and may vary depending on build and layout.  
- KiCad version compatibility: **KiCad 10** recommended.  
