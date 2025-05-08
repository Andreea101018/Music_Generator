# 🎶 AI Music Generator

Generate original music using deep learning. This project leverages both **Transformer** and **LSTM** models to learn musical structure from MIDI files and generate new compositions in the same style.

---

## 📌 Overview

This project allows you to:
- Preprocess MIDI files into tokenized sequences (pitch, step, duration)
- Train Transformer or LSTM models on these sequences
- Generate new music with tempo, rhythm, and instrument program preserved
- Export results to MIDI files using the original instrument sounds

---

## ✨ Features

- ✅ **Transformer and LSTM support**  
  Train either model architecture and compare results.

- ✅ **Tokenized music sequences**  
  Pitch, step (delay), and duration are quantized into discrete bins.

- ✅ **Subfolder-aware MIDI ingestion**  
  Automatically scans all `.mid` / `.midi` files recursively.

- ✅ **Instrument preservation**  
  Generated output uses the same MIDI program as the original.

- ✅ **Custom sequence length and timing bins**  
  Adjustable sequence length and timing granularity.

---
