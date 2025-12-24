# Class D Audio Amplifier
**Developed by:** Komal Dudhbhate

### Description
This project is a high-efficiency Class D Audio Amplifier designed in KiCad. It uses Pulse Width Modulation (PWM) to drive a MOSFET output stage, followed by an LC filter to recreate clear analog sound.

### Technical Highlights
* **High-Speed Comparator:** Uses the ADA4898 for sharp PWM edges to reduce heat and distortion.
* **Optimized Power Paths:** All high-current tracks are **1.5mm wide** to handle power safely without overheating.
* **EMI Protection:** A solid bottom ground plane was implemented to shield the audio signal from switching noise.
* **Output Filter:** Designed with a $22\mu H$ inductor and $1\mu F$ capacitor for a clean **33.9 kHz** cutoff frequency.

### How to Navigate this Repo
* **Class D.pdf**: Schematic diagram of the circuit.
* **Class D.kicad_pcb**: The physical board layout.
* **Gerber Files**: Production-ready files for manufacturing.
* **Class D.csv**: Bill of Materials (BOM).
