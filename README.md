
# NetSanity Anti-Cheat

**NetSanity** is a lightweight, modular anti-cheat system designed for real-time multiplayer games. Built with performance and flexibility in mind, NetSanity helps detect, prevent, and respond to cheating and unauthorized modifications in both client-side and server-side environments.

![License](https://img.shields.io/badge/license-MIT-green) ![Unity](https://img.shields.io/badge/unity-supported-blue) ![Photon Fusion](https://img.shields.io/badge/photon-fusion%202-compatible-purple)

---

## 🔒 Features

- ✅ **Speed/Teleport Detection**
- ✅ **Integrity Validation** (DLL tampering, APK modification)
- ✅ **Remote Kick/Ban System** (with optional PlayFab integration)
- ✅ **Custom Rule Definitions**
- ✅ **Obfuscated Runtime Checks**
- ✅ **Network Packet Validation**
- ✅ **Lightweight Client Footprint**
- ✅ **Logs + Cheat Reporting System**

---

## 🧠 How It Works

NetSanity uses a modular detection system:

- **Client Module:** Monitors unauthorized code injection, game speed hacks, movement anomalies, and file integrity.
- **Server Module:** Validates network packets, monitors behavior, and takes corrective actions (kick/ban/report).
- **Integration Layer:** Hooks into Photon Fusion, PlayFab, or your custom backend for full control.

---

## 🚀 Getting Started

### Requirements

- Unity 2021 or newer
- Photon Fusion 2 (optional)
- PlayFab (optional)
