# astra
astra ia
# ASTRA-SAFE — Virtual Prototype (Web Demo)

**ASTRA-SAFE** — Autonomous Smart Telemetry & Recovery AI for CubeSats  
This repository contains a lightweight interactive *virtual prototype* (web demo) of the ASTRA-SAFE 3U CubeSat module.

## Demo contents
- `index.html` — single-file interactive demo (Three.js 3D view + Chart.js telemetry)
- `README.md` — this file

The demo simulates telemetry (voltage, temperature, gyro), runs a simple in-browser anomaly detector and shows automated recovery actions (visual + log).

## How to run locally
1. Download / clone the repository.
2. Serve the folder (recommended) or open `index.html` directly.

**Serve with Python (recommended):**
```bash
# from repository root
python -m http.server 8000
# open http://localhost:8000 in your browser
