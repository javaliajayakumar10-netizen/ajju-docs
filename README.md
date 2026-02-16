## 📌 Overview

**AJJU – YT Downloader PRO** is a professional CLI tool designed to:

- Download YouTube videos in high quality
- Extract MP3 audio
- Download full playlists
- Display real-time progress with speed & ETA
- Automatically handle missing dependencies

It is fast, lightweight, and built for developers and power users.

---

## ✨ Features

- 🎥 Download videos in **1080p / 720p / 480p**
- 🎧 Audio-only **MP3 extraction**
- 📂 Full playlist auto-detection
- 📊 Real-time progress bar with speed & ETA
- ⚡ Auto dependency installation
- 📁 Saves downloads to system **Downloads folder**
- 🌍 Global CLI command support (`ajju`)
- 🖥 Cross-platform compatible

---

## 🛠 Installation

### 🔹 Prerequisites

- Python 3.8+
- pip
- FFmpeg (added to system PATH)

Download FFmpeg from:
https://ffmpeg.org/

---

### 🔹 Option 1 — Global Install (Recommended)

```bash
git clone https://github.com/javaliajayakumar10-netizen/ajju_do.git
cd ajju_do
pip install .
````

After installation, you can run:

```bash
ajju
```

---

### 🔹 Option 2 — Run Directly

```bash
git clone https://github.com/javaliajayakumar10-netizen/ajju_do.git
cd ajju_do
python ajju_do.py
```

---

## 🚀 Usage

1. Run the program:

```bash
ajju
```

2. Paste the YouTube video or playlist link.

3. Select quality:

```
1. Best
2. 1080p
3. 720p
4. 480p
5. MP3
```

4. Download begins automatically.

---

## 📂 Download Location

Videos are saved to:

```
Downloads/
```

Playlists are saved to:

```
Downloads/Playlist_Name/
```

---

## 📦 Dependencies

| Package  | Purpose             |
| -------- | ------------------- |
| yt-dlp   | Download engine     |
| rich     | Terminal UI         |
| argparse | CLI handling        |
| FFmpeg   | Audio/video merging |

Dependencies are automatically installed if missing.

---

## 💡 Why This Tool?

This tool was built to solve common problems:

* Manual YouTube downloads are slow
* Playlist downloads are inconvenient
* Many tools lack proper CLI UX
* Manual dependency setup is annoying

AJJU simplifies everything into one clean CLI experience.

---

## 🔒 Legal Notice

This tool uses **yt-dlp** and **FFmpeg** under their respective licenses.

Users are responsible for complying with:

* YouTube Terms of Service
* Copyright laws in their country

---

## 👨‍💻 Author

**Javali Ajayakumar**

---

## ⭐ Support

If you find this project useful:

* ⭐ Star the repository
* 🍴 Fork it
* 🛠 Contribute improvements

---

## 📜 License

© 2026 Javali Ajayakumar
All rights reserved.

