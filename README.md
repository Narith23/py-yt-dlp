# 🎥 YouTube Video Downloader (Python + yt-dlp)

This is a simple Python script to download YouTube videos using the powerful [yt-dlp](https://github.com/yt-dlp/yt-dlp) library.

---

## ✅ Features

- Downloads the **best quality** MP4 video.
- Saves all videos to the `videos/` directory (auto-created).
- Clean and user-friendly terminal interface.
- Handles invalid URLs and exit gracefully.

---

## 🚀 Getting Started

### 1. Clone the repository or download the script

```bash
git clone https://github.com/Narith23/py-yt-dlp.git
cd yt-downloader
```

### 2. Create a virtual environment (optional but recommended)

```bash
python -m venv .venv
source .venv/bin/activate   # On Windows: .venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install yt-dlp
```

---

## ▶️ Usage

```bash
python main.py
```

Paste the YouTube URL when prompted and let the script download the video for you!

Videos will be saved in the `videos/` folder.

---

## 🛑 Exit

- Type `exit` or press `Ctrl + C` to quit the script.

---

## 📁 Output

All downloaded videos are saved in:

```
/videos/
```

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).
