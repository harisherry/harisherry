### Hi, I'm Haris (`@harisherry`)

**Systems & Desktop Software Engineer** building low-level Windows hardware utilities, direct USB HID device drivers, real-time telemetry compositors, and quantitative financial terminals.

[![C#](https://img.shields.io/badge/C%23-.NET%204.8%20%7C%20.NET%208-512BD4?logo=dotnet&logoColor=white)](https://github.com/harisherry)
[![WPF / WinForms](https://img.shields.io/badge/Windows-WPF%20%7C%20WinForms%20%7C%20Win32-0078D6?logo=windows&logoColor=white)](https://github.com/harisherry)
[![USB HID & Super I/O](https://img.shields.io/badge/Hardware-USB%20HID%20%7C%20Super%20I%2FO%20%7C%20NVAPI-00E5FF)](https://github.com/harisherry)
[![Python](https://img.shields.io/badge/Python-Quantitative%20Finance%20%26%20CV-3776AB?logo=python&logoColor=white)](https://github.com/harisherry)

---

### ⚡ Engineering Focus

- **Hardware Telemetry & Thermal Control**: Direct register-level motherboard Super I/O control (`ITE IT8696E/IT8689E`, `Nuvoton NCT6798D` via `PawnIO`), multi-bus USB HID controller protocols (`CorsairLink`, `HidSharp`), and GPU sensor pipelines (`NVAPI`, `AMD ADLX`).
- **Auxiliary Display Drivers & DSP Pipelines**: Reverse-engineered USB HID / bulk frame streamers (`VID_0416&PID_5302`), 60 FPS hardware-accelerated `WebView2` / `WPF` compositors, and real-time 1024-bin WASAPI loopback FFT audio spectrum analyzers.
- **Quantitative Financial Terminals**: Multi-factor equity scoring engines, EOD technical indicator pipelines (Wilder's $\text{RSI}_{14}$, 50/200-day SMAs, DRIP XIRR simulators), and WinRT Computer Vision OCR portfolio synchronization.

---

### 🛠 Featured Open-Source Projects

| Project | Architecture & Domain | Stack |
| :--- | :--- | :--- |
| **[HyteFlow Studio](https://github.com/harisherry/HyteFlow)** | **Universal PC Fan & Chassis Telemetry Utility** — Ring-0 Super I/O + USB HID fan curve controller with 6-second 100%-duty header pulse identification (`⚡ LOCATE 100%`) and an interactive 3D spatial chassis viewport. | `C#` `WPF` `PawnIO` `HidSharp` `NVAPI` |
| **[TL-M10 Vision Studio](https://github.com/harisherry/tl-m10-vision-studio)** | **60 FPS Direct USB LCD Controller (`1920 × 462`)** — High-frequency replacement driver & visual studio for the Thermalright TL-M10 Vision ultra-wide display with WASAPI 64-band FFT audio spectrum, HWiNFO64 MMF telemetry, and live multi-market terminals (`BTC`, `KSE-100`, `NYSE`). | `C#` `WinForms` `WebView2` `WASAPI DSP` `USB HID` |
