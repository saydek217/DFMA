# Dual-Focus Multiscale Attention (DFMA) for Real-Time Object Detection in Mixed Reality

This repository contains the official implementation of **DFMA** — a lightweight dual-path attention module (multi-scale **spatial** + **channel**) that plugs into Ultralytics YOLO (v8+ family) to boost accuracy on hard, low-textured, look-alike objects **while preserving real-time performance**. The method was presented at **IEEE ISMAR 2025**.

> TL;DR: Drop‐in DFMA blocks + ready YAML + scripts to reproduce training.

---

## ✨ Features

- Plug-and-play **DFMA** (and optional **MSAF** (Multi-Scale Attention Fusion)) layers for YOLO backbones/FPN.
- **Ultralytics-native YAML** (`dfma.yaml`) for painless integration.
- **Python API** and optional CLI; simple training code.

---

## 📅 Roadmap & Availability

- **Data generation code (Blender + hybrid backgrounds):** _coming soon_  
- **Unity (Sentis) MR demo (scene + scripts):** _coming soon_  
- **Paper (ISMAR 2025):** _link coming soon_

> Watch the repository for releases and updates:
> - ⭐ **Star** the repo to bookmark it
> - 👀 **Watch** → “Releases only” to get notified when we publish code & the paper link

---

## 🔗 Paper Link (placeholder)

**Title:** Dual-Focus Multiscale Attention for Object Detection in Mixed Reality (ISMAR 2025)  
**PDF/DOI:** _coming soon_


## 📣 Changelog

- **v0.1.0** — Initial public codebase (DFMA modules, config, registry, tests).  
- **Next** — Add data-generation scripts and Unity demo; publish paper link.
