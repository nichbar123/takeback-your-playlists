# Takeback Your Playlists
# 🎵 Spodify → MP3

> Yo ho ho ☠️  
> In a world where music streams endlessly but ownership disappears, this notebook helps you **reclaim access to playlists you already love**.

This project converts playlist data into downloadable MP3 files using YouTube as an audio source.  
It is designed to be run **entirely in Google Colab** — no local setup required.

---

## ⚠️ Disclaimer
This project is for **personal use, educational purposes, and archival access** only.  
Always respect artists, creators, and local copyright laws.

---

## 🚀 How it works (High Level)
1. Export a playlist (track names + artists)
2. Search YouTube for matching audio
3. Download and convert audio to MP3
4. Save files in a clean, organized structure

---

## 🧰 What you need

- A playlist from **Spotify** (or another service)
- A Google account (for Colab)
- This notebook

---

## 📤 Step 1: Export your playlist

Use **Exportify** to export your Spotify playlist as a CSV:

👉 https://exportify.net/

Make sure your export includes:
- Artist
- Track name

---

## ▶️ Step 2: Run the notebook in Google Colab

1. Open Google Colab  
   👉 https://colab.research.google.com/

2. Upload or open the notebook:
   - `SpodifyToMP3.ipynb`

3. Upload your exported CSV when prompted

4. Run the cells and let it cook 🔥

Your MP3s will be downloaded into a `music/` folder.

---

## 📁 Output structure

```text
music/
├── Artist - Song Title.mp3
├── Artist - Song Title.mp3
└── ...
