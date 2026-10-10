# 🌐 OSI Explorer — Interactive Network Security Reference

An interactive educational web application designed to help beginners and cybersecurity students understand the **OSI (Open Systems Interconnection) 7-Layer Model**.

Explore protocols, hardware devices, threat vectors, attack mechanisms, and defense strategies at every layer of the network stack.

---

## ✨ Features

- **⬡ Interactive Layer Stack**:
  - All 7 layers (Application down to Physical) with Cisco-inspired distinct color palettes.
  - **Dual Mnemonic Switcher**:
    - *Top-Down (L7 → L1)*: **A**ll **P**eople **S**eem **T**o **N**eed **D**ata **P**rocessing
    - *Bottom-Up (L1 → L7)*: **P**lease **D**o **N**ot **T**hrow **S**ausage **P**izza **A**way
  - Deep-dive tabs for every layer: **📋 Protocols**, **🖥️ Devices**, **⚡ Attacks & Vulnerabilities**, and **🛡️ Defenses**.

- **⤑ Step-by-Step Packet Journey**:
  - Follow real-world traffic flows: **HTTP Web**, **DNS Query**, **SMTP Email**, **SSH Shell**, **VoIP (SIP)**, and **Video Streaming**.
  - **3-Phase Visual Model**:
    1. *Encapsulation (Sender L7 → L1)* — Watch headers wrap around payload data like nested envelopes.
    2. *Physical Transmission* — Animated live data pulse traversing physical cables, fiber, or airwaves.
    3. *Decapsulation (Receiver L1 → L7)* — Watch headers get verified and stripped to recover the original message.
  - Bidirectional stepper navigation with `‹ Prev Step`, `Next Step ›`, and `↺ Reset`.

- **◈ Casual Quiz & Knowledge Checks**:
  - 25 scenario-based questions with instant explanations.
  - Filter by individual layers or test all layers at once.

- **🎨 Modern Security UI**:
  - Terminal/cyber dot-grid aesthetic with glowing indicators.
  - Full Dark Mode / Light Mode toggle.
  - Pure client-side static web application (zero dependencies, zero build steps).

---

## 🚀 Quick Start (Local Run)

Simply open `index.html` in any modern web browser:
- Double-click `index.html`, or
- Right-click and choose **Open with > Chrome / Firefox / Edge**.

---

## 📂 Project Structure

```
osi-explorer/
├── index.html   # Main application markup, layout, styles, and interactive engine
├── data.js      # Comprehensive OSI layer metadata, protocol specs, threat models & quiz questions
└── README.md    # Documentation
```

---

## 📜 License

MIT License — Feel free to use, share, and expand for educational purposes!
