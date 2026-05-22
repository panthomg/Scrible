# 📖 Scribe: The Local Audiobook Titan

**Scribe** is a high-performance, privacy-focused, browser-based reader that transforms your local PDF, DOCX, and TXT files into a Spotify-like audiobook experience. Built for operators who value offline capability and a premium UI.

![Scribe UI Concept](https://img.shields.io/badge/UI-Spotify--Inspired-1DB954?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)
![Local Only](https://img.shields.io/badge/Data-100%25_Local-orange?style=for-the-badge)

## 🔍 The Mission
Most TTS readers are either clunky, locked behind subscriptions, or harvest your data. Scribe uses your browser's native **Web Speech API** to provide a seamless, free, and completely offline experience. No server. No tracking. Just the code.

## ⚡ Core Features
- **Multi-Format Ingestion**: Support for PDF, DOCX, and plain TXT files.
- **Spotify-Inspired UX**: Minimalist, glassmorphic design optimized for focus.
- **Live Captions**: Real-time word highlighting for synchronized visual reading.
- **Grammar-Aware Synthesis**: Intelligent sentence splitting for natural breathing and cadence.
- **Persistent Library**: Save your books and reading progress locally using IndexedDB.
- **Variable Speed**: Adjustable playback rates (0.75x to 2.0x).
- **Zero Latency**: No API calls; all synthesis happens on the device.

## 🛠️ Tech Stack
- **Engine**: Web Speech API (SpeechSynthesis)
- **Parsers**: PDF.js (Mozilla), Mammoth.js (DOCX conversion)
- **Storage**: LocalForage (IndexedDB wrapper)
- **Icons**: Phosphor Icons

## 🚀 Quick Start
1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/scribe.git
