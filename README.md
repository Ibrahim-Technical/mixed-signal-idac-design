# mixed-signal-idac-design

# Exponential Current iDAC — Mixed-Signal CMOS

This repository documents a mixed-signal CMOS exponential current-output DAC (iDAC) designed as part of ELEC4602 Microelectronics Design and Technology.

## Objective
Design a current-output iDAC with an exponential code-to-current relationship:
- I_LSB = 10 µA
- α_R = 20
- N ≥ 3 bits
- CMOS 45 nm process (FreePDK-based)

## Architecture Overview
- Digital decoding of input code B
- Voltage domain translation (logic to analog)
- Current-mirror-based analog output stage
- NMOS switching network for current steering

## Evaluation & Verification
The design was evaluated using:
- Transient simulations
- Corner simulations (fast/slow)
- Monte Carlo simulations
- Performance metrics: DNL, settling time, power, area, output compliance

## Documentation
- Full project specification and report: see `/report/Exponential_iDAC_Report.pdf`

## Contributors
- Ibrahim Ali Harbi  
- Project partner (as per report)

## Disclaimer
This repository contains documentation and figures only. No proprietary PDKs or university-provided libraries are included.
