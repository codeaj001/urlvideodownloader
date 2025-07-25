# 🎬 Rust Social Video Downloader CLI

## ✨ Features

- ✅ Download from any URL supported by yt-dlp (YouTube, TikTok, Twitter, etc.)
-- Checkout supported sites here: `https://github.com/yt-dlp/yt-dlp/blob/master/supportedsites.md`
- ✅ Select multiple formats per video (`mp3`, `mp4`, `webm`)
- ✅ Interactive command-line prompts

---

## 🛠 Requirements

Make sure the following tools are installed on your system:

### 1. Rust (with `cargo`)

Install Rust using [rustup](https://rustup.rs/):

```bash
curl https://sh.rustup.rs -sSf | sh

Check installation:

```bash
rustc --version
```

---

### 2. yt-dlp

Install via pip:

```bash
pip install yt-dlp
```

Or use the binary (Linux/macOS):

```bash
wget https://github.com/yt-dlp/yt-dlp/releases/latest/download/yt-dlp
chmod +x yt-dlp
sudo mv yt-dlp /usr/local/bin/
```

---

### 🎞 3. FFmpeg

Required for format conversion (`mp3`, `mp4`, etc.).

#### Ubuntu/Debian:

```bash
sudo apt install ffmpeg
```

#### macOS (using Homebrew):

```bash
brew install ffmpeg
```

---

## 🚀 How to Run

1. **Clone or download the project**

```bash
git clone https://github.com/codeaj001/urlvideodownloader.git
cd urlvideodownloader
```

2. **Build and run it**

```bash
cargo run
```

3. **Follow the prompts**

Example terminal session:

```
Enter video URL: https://www.youtube.com/watch?v=abcd1234
Enter format(s) for this URL (e.g. mp4,mp3)
Enter video URL: 
Enter output directory (default: ./downloads):
```

Done! Your downloads will be saved in the selected folder.

---

## 🧩 Open to Extension

This tool is beginner-friendly and designed for hacking and extension.

Ideas for new features:

* [ ] Load multiple URLs from `.txt` file
* [ ] Download video thumbnail and metadata
* [ ] Save a log of downloads
* [ ] Display video title before downloading
* [ ] Parallel downloads with threads
* [ ] more...

Feel free to fork, PR, or suggest ideas!