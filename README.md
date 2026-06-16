# 🛡️ Google Cloud Armor: DDoS Defense Visualizer

<p align="center">
  <a href="https://apinke.github.io/cloud-armor-visualizer/"><strong>▶ View Live Demo</strong></a>
</p>

---

## About

An interactive visualization of Google Cloud Armor's DDoS protection capabilities. Demonstrates how Cloud Armor scrubs malicious traffic at the network edge before it reaches backend infrastructure.

## Features

- 🔴 **Volumetric Flood simulation** — L3/L4 UDP flood attack
- 🟠 **DNS Amplification simulation** — DNS reflection attack
- 🟢 **Legitimate traffic** — Clean traffic passing through
- 🛡️ **Cloud Armor Edge** — Real-time scrubbing visualization

## How It Works

1. Click **Volumetric Flood** or **DNS Amplification** to simulate an attack
2. Watch malicious packets (red/orange) get absorbed at the Cloud Armor edge
3. Legitimate traffic (green) continues to the backend unaffected
4. Click **Reset Simulation** to start fresh

## Technologies

- HTML5 Canvas for real-time particle animation
- Tailwind CSS for styling
- Vanilla JavaScript

---

## 📝 License

Licensed under [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/) — free to share and adapt with attribution to **Gbemisola Esho**.

---

👩🏾‍💻 **By Gbemisola Esho** — Google Developer Expert · WTM Ambassador · [Connectobridge](https://connectobridge.com)
