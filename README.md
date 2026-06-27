# 💻 Abhishek Karthik PS (CLPUYIR)
### 🚀 Embedded Systems Engineer | Distributed AI Researcher | Full-Stack IoT Architect

I build bare-metal firmware, design high-frequency wireless sniffer hardware, and architect decentralized, offline-first systems. My work focuses on bridging the gap between low-level hardware (microcontrollers, sensors, biosignals) and distributed high-performance software (local LLM swarms, automated data pipelines).

---

## 🛠️ Tech Stack & Domain Expertise

<table>
  <tr>
    <td valign="top" width="25%">
      <strong>📟 Hardware & IoT</strong><br />
      • ESP32 & ESP8266 (RTOS)<br />
      • STM32 & Arduino Series<br />
      • SPI, I2C, UART, TCP/IP<br />
      • TFT Displays (ST7735, OLED)
    </td>
    <td valign="top" width="25%">
      <strong>🧠 AI & Signal Processing</strong><br />
      • LLM Swarm Orchestration<br />
      • llama.cpp RPC & Ollama<br />
      • EMG Signal Feature Extraction<br />
      • Linear Discriminant Analysis
    </td>
    <td valign="top" width="25%">
      <strong>💻 Languages & Tooling</strong><br />
      • C, C++, Python<br />
      • TypeScript & PowerShell<br />
      • Git & GitHub Actions<br />
      • PlatformIO & VS Code
    </td>
    <td valign="top" width="25%">
      <strong>🌐 Web & Scraping</strong><br />
      • React 19 & Framer Motion<br />
      • Tailwind CSS & HTML/CSS<br />
      • Playwright (Stealth)<br />
      • SQLite & Tesseract OCR
    </td>
  </tr>
</table>

---

## 🏆 Featured Projects

### 🐝 [HIVEYESH v2.0 — The Sovereign Swarm](https://github.com/CLPUYIR/HIVEYESH-V2.0)
*A Distributed AI Supercomputer designed for isolated local networks.*
*   **The Problem:** Running massive PhD-level LLMs (like Llama-3.1 405B) requires expensive enterprise GPUs ($$$$).
*   **The Sovereign Solution:** Aggregates CPU-RAM and GPU-VRAM across heterogeneous local office/lab machines into a single virtual compute pool.
*   **Architecture:** Separates execution into a **Management Plane** (WinRM, Robocopy for parallel weight distribution) and a high-performance **Data Plane** (raw binary TCP sockets bypassing standard OS networking overhead via llama.cpp RPC).
*   **Key Features:** Automated hardware/network profiling (`SetPriorityClass` optimization), interactive ASCII TUI wizard, transactional self-healing failover (Emergency Resharding), and a synchronized multi-agent router with shared memory.
*   *Stack: Python, PowerShell, C/C++, llama.cpp, Win32 API*

### 🦾 [Bionic Limb Control System](https://github.com/CLPUYIR/bmi-project)
*Real-time Electromyography (EMG) pattern recognition and prosthetic hand visualization.*
*   **The Science:** Aligned with the benchmark **NinaPro Database 2 (DB2)** dataset for non-invasive adaptive prosthetics.
*   **Signal Processing:** Simulates 8-channel raw muscle contractions, running sliding-window feature extraction to calculate Mean Absolute Value (MAV), Root Mean Square (RMS), Waveform Length (WL), and Zero Crossings (ZC).
*   **Classification:** Maps real-time muscle activity to hand gestures using a localized Euclidean distance nearest-neighbor pattern recognition algorithm (simulated LDA).
*   **Visualizer:** High-fidelity interactive hand rendering driven by Framer Motion physics.
*   *Stack: React 19, TypeScript, Framer Motion, Tailwind CSS, Vite*

### 📡 [WIFIMON — ESP32 Cybersecurity Sniffer & Radar](https://github.com/CLPUYIR/WIFIMON)
*Active packet sniffer and passive device proximity tracking on bare-metal hardware.*
*   **Network Sniffing:** Hooks directly into the ESP32 wireless stack in promiscuous mode to capture raw 802.11 frames. Parses Beacons (SSID, encryption, channel) and Client Probes to map local network topologies.
*   **Embedded Display:** Implements double-buffered drawing on an ST7735 1.8" TFT screen using `GFXcanvas16` to completely eliminate frame flicker.
*   **Proximity Mapping:** Real-time RSSI signal-strength database with rolling memory structures and 30-second inactive node aging.
*   *Stack: C++, ESP32 Wi-Fi SDK, Adafruit GFX, ST7735 SPI Driver*

### 🌴 [Kerala Toddy Shop Intelligence Pipeline](https://github.com/CLPUYIR/Kerala-Shop-Intelligence)
*An autonomous, local hybrid AI scraper and data enrichment system.*
*   **Stealth Scraping:** Playwright-driven automation maps ~4,500 target establishments, extracting geocoding, ratings, reviews, and contact information.
*   **Offline AI & Vision:** Extracts raw text (English and Malayalam) from menus/imagery via Tesseract OCR and passes it to local LLMs (via Ollama) to autonomously classify signature dishes and synthesize establishment vibes.
*   **State Machine:** SQLite database keeps the multi-stage pipeline robust, transactional, and 100% resumable.
*   *Stack: Python, Playwright, Ollama (Llama 3.1), SQLite, Tesseract OCR*

---

## 📊 GitHub Analytics & Diagnostics

<p align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=CLPUYIR&show_icons=true&theme=tokyonight&count_private=true" alt="Abhishek's GitHub Stats" height="180" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=CLPUYIR&layout=compact&theme=tokyonight&hide=html,css" alt="Top Languages" height="180" />
</p>

---

## 📬 Let's Connect

*   📧 **Direct Email:** [abhishekkarthikps@gmail.com](mailto:abhishekkarthikps@gmail.com)
*   🐙 **GitHub Home:** [github.com/CLPUYIR](https://github.com/CLPUYIR)

---
*“Recycling hardware, scaling intelligence, securing connections.”*
