# Dual VHF/UHF Low-Noise Amplifier (LNA)

A hardware design project for a dual-band Low-Noise Amplifier (LNA) covering the VHF and UHF frequency ranges, tailored for software-defined radio (SDR), satellite reception, and amateur radio applications.

---

## 🎯 Target Specifications (Draft)

| Parameter | VHF Band | UHF Band | Notes |
| :--- | :--- | :--- | :--- |
| **Frequency Range** | ~144 – 148 MHz (2m) | ~430 – 440 MHz (70cm) | Configurable / TBD |
| **Target Gain** | ~18 – 20 dB | ~15 – 18 dB | TBD |
| **Noise Figure (NF)**| < 0.8 dB | < 1.0 dB | Target |
| **Impedance** | 50 Ω (SMA) | 50 Ω (SMA) | Matched I/O |
| **Power Supply** | Bias-T / External DC | Bias-T / External DC | 3.3V – 5V LDO regulated |
| **Active Devices** | TBD (e.g. ATF-54143 / PGA-103+ / PSA4-5043+) | | Low noise MMIC / pHEMT |

---

## 📁 Repository Structure

- [`LNA/`](file:///E:/LNA/LNA): KiCad design files
  - [`LNA.kicad_pro`](file:///E:/LNA/LNA/LNA.kicad_pro): KiCad project file
  - [`LNA.kicad_sch`](file:///E:/LNA/LNA/LNA.kicad_sch): Schematic sheet
  - [`LNA.kicad_pcb`](file:///E:/LNA/LNA/LNA.kicad_pcb): PCB layout

---

## 🛠 Status

- [x] Project initialization
- [ ] Schematic capture (filtering, matching networks, bias network)
- [ ] PCB layout & RF microstrip routing
- [ ] Bill of Materials (BOM) & fabrication outputs
- [ ] Prototyping & VNA/Noise Figure testing
