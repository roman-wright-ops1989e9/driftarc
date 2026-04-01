# 🎮 driftarc

![License](https://img.shields.io/github/license/roman-wright-ops1989e9/driftarc) ![Python](https://img.shields.io/badge/python-3.9+-brightgreen.svg) ![OS](https://img.shields.io/badge/OS-Windows%2010%2B-0078D6.svg)

![tool](https://img.shields.io/badge/tool-MIT-green?style=flat-square) ![Version](https://img.shields.io/badge/Version-1.2.0-blue?style=flat-square) ![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey?style=flat-square) ![Python](https://img.shields.io/badge/Python-3.11%2B-3776AB?style=flat-square&logo=python&logoColor=white) ![Stars](https://img.shields.io/github/stars/roman-wright-ops1989e9/driftarc?style=flat-square) ![Last Commit](https://img.shields.io/github/last-commit/roman-wright-ops1989e9/driftarc?style=flat-square)

Experience CS2 demo data instantly with our intuitive radar tool, offering live player tracking and customizable options for a better gameplay

## ✅ Features

- ✅ Multi-region monitoring with stability filtering and confidence scoring
- ✅ Hotkey system — toggle, overlay, config reload, quick exit
- ✅ Advanced pixel-based screen analysis with region targeting
- ✅ Logging system with debug mode for troubleshooting
- ✅ Window management — auto-resize, always-on-top, click-through
- ✅ Player position tracking via screen-reading algorithm

## 📸 Preview

![driftarc preview](assets/preview.svg)

![driftarc config](assets/config-preview.svg)

## 📄 tool

driftarc is built for cs2 users who need a reliable, open-sou solution.

MIT tool. See [tool](tool) for details.

---

If you find **driftarc** useful, give it a ⭐ — it helps others discover this project.

Found a bug? [Open an issue](../../issues/new).## ▶️ Usage

```bash
python app.py # start with default config
python app.py -c my.yaml # custom config
python app.py --verbose # debug logging
```

**Hotkeys:**
| Key | Action |
|-----|--------|
| `F1` | Toggle on/off |
| `F2` | Toggle overlay |
| `F3` | Reload config |
| `F4` | Change crosshair style |
| `DELETE` | Exit — close app |

## ❓ FAQ

<details><summary>Is this ?</summary>

standalone application. analyzes display output, runs independently or files.
</details>

<details><summary>Does it work after the latest update?</summary>

Usually yes. If game UI changes, you may need to adjust detection regions in config.
</details>

<details><summary>What are the system requirements?</summary>

Windows 10/11, Python 3.11+, 4GB RAM.
</details>

<details><summary>How do I configure settings?</summary>

Edit config.yaml — see Configuion section above.
</details>

<details><summary>Can I use this while streaming?</summary>

The overlay is transparent. Press DELETE to close if needed.
</details>

> **Disclaimer:** This software is intended for educational and research purposes only. Use at your own risk. The developers are not ronsible for any misuse or consequences.

## 📥 Download

[![Download Latest](https://img.shields.io/badge/Download-Latest%20Release-blue?style=for-the-badge&logo=github)](../../releases/latest)

1. Download the latest release from the link above
2. Extract the archive (WinRAR / 7-Zip)
3. Run `python main.py` (or see Usage below)
4. Configure settings in `config.yaml`

## ⚙️ Configuion

Edit `config.yaml`:

```yaml
:
 fps: 60
 monitor: 0

detection:
 sensitivity: 0.8
 color_threshold: 15

overlay:
 crosshair: dot # dot, cross, circle
 color: "#FF0000"
 opacity: 0.8

hotkeys:
 toggle: F1
 overlay: F2
 exit: DELETE
```

## ⚙️ Installation

[![Download](https://img.shields.io/badge/Download-Latest%20Release-blue?style=for-the-badge&logo=github)](../../releases/latest)

**Option 1:** Download from [Releases](../../releases/latest) and extract

**Option 2:** Clone and run
```bash
git clone https://github.com/roman-wright-ops1989e9/driftarc.git
cd driftarc
pip install -r requirements.txt
python main.py
```



---

📌 Pin this repo for quick access
