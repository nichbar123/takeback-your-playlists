# Take Back Your Playlist ✊
# 🎵 Spodify → MP3

![Made with Python](https://img.shields.io/badge/Made%20with-Python-blue)
![Runs on Colab](https://img.shields.io/badge/Runs%20on-Google%20Colab-orange)
![Notebook](https://img.shields.io/badge/Format-Jupyter%20Notebook-lightgrey)

> Yo ho ho ☠️  
> In a world where music streams endlessly but ownership disappears, this project helps you **reclaim access to playlists you already curated**.

This repository contains a Google Colab–ready Jupyter Notebook that converts playlist exports into MP3 files using YouTube as an audio source.

---

## ⚠️ Disclaimer

This project is intended for **personal use, educational purposes, and data portability**.  
Always respect artists, creators, platform terms of service, and local copyright laws.

---

## 🚀 How It Works

1. Export a playlist (track + artist metadata)
2. Search YouTube for matching audio
3. Download and convert audio to MP3
4. Save files locally in an organized folder

---

## 🧰 Requirements

- A playlist from Spotify (or another service)
- A Google account
- This notebook

No local installs required — everything runs in **Google Colab**.

---

## 📤 Step 1: Export Your Playlist

Use **Exportify** to export your Spotify playlist as a CSV:

👉 https://exportify.net/

Ensure the export includes:
- `artist`
- `track`

---

## ▶️ Step 2: Run in Google Colab

1. Open Google Colab  
   👉 https://colab.research.google.com/

2. Upload or open `SpodifyToMP3.ipynb`

3. Upload your exported CSV when prompted

4. Run the cells and let it do its thing 🔥

---

## 📁 Output

```text
music/
├── Artist - Song Title.mp3
├── Artist - Song Title.mp3
└── Artist - Song Title.mp3
```

---

## 🧭 TODO / Roadmap

- [ ] Apple Music playlist support  
- [ ] Better handling when a song is not found  
- [ ] Retry / fallback search strategies  
- [ ] Audio metadata tagging (album art, year, genre)  
- [ ] Progress summary + error report  
- [ ] Optional ZIP export of results  

---

## 🧠 Why This Exists

Streaming platforms are convenient — but playlists represent **time, taste, and effort**.

This project exists to:
- Preserve access to playlists you’ve already built
- Enable experimentation with music data workflows
- Provide a reproducible, notebook-based approach to audio extraction

Think of it as **data portability for music**, not a replacement for streaming services.

---

## 🤝 Contributing

Contributions are welcome.

- Open an issue for bugs or feature requests  
- Submit a pull request for improvements  
- Keep changes readable and well-documented  

Pirate jokes optional. Clean code required.

---

## 🏴‍☠️ Final Note

If you can export it,  
you should be able to use it.

