# Vortex Studio

> High-performance, client-side media manipulation engine powered by FFmpeg WebAssembly. 100% private, zero uploads, zero server processing costs.

---

## 🚀 Overview

**Vortex Studio** is a web-based media toolkit designed to replace clunky desktop video editors and questionable online cloud converters. 

By executing **FFmpeg.wasm** inside the user's browser, all video conversions, audio muxing, stream repairs, and trimming run directly in memory (RAM). Files never touch an external server, eliminating data privacy risks, bandwidth usage, and file upload limits.

---

## ⚡ Tool Suite Included

1. **Audio & Video Stream Muxer**: Fuses separated audio tracks (`.mp3`, `.m4a`, `.aac`) with standalone video streams (`.mp4`, `.webm`) using instant bitstream copying (`-c:v copy`).
2. **Stream Inspector (ffprobe Engine)**: Inspects containers, video codecs (AV1, VP9, H.264), audio profiles, and bitrates without local CLI tools.
3. **Lossless Stream Trimmer**: Cuts video chapters with zero re-encoding artifacts using stream-copy.
4. **Voice / Audio Extractor**: Strips audio out of long lectures as MP3 or M4A for offline listening or AI transcription (Whisper).
5. **Instant Muter**: Strips audio tracks entirely in sub-second speeds.
6. **Audio Booster & Normalizer**: Amplifies quiet recordings up to 300% without altering the original video stream.
7. **9:16 Vertical Video Re-framer**: Converts 16:9 widescreen footage into vertical frames for YouTube Shorts, Instagram Reels, and TikTok.
8. **Target Size Compressor**: Calculates target bitrates dynamically to compress videos below strict platform limits (Discord 25MB, WhatsApp 16MB).
9. **Audio Desync Realignment**: Shifts lagging or early audio tracks via non-destructive `-itsoffset` flags.
10. **2-Pass Cinema Palette GIF Engine**: Generates smooth 256-color looping GIFs without color banding.
11. **High-Res Poster Snapper**: Snags full-resolution PNG thumbnails at any precise timestamp.

---

## 🛠️ Deployment on Vercel

Because WebAssembly uses `SharedArrayBuffer` for multi-threaded performance, browsers require `COOP` and `COEP` security headers.

1. Push this folder to a GitHub repository.
2. Import the repository into **Vercel**.
3. Deploy! The included `vercel.json` automatically configures the required response headers.

---

## 👤 Author & Contact

**Osazuwa Matthew**

- **Email**: [osazuwamatthewogbebor@gmail.com](mailto:osazuwamatthewogbebor@gmail.com)
- **WhatsApp**: [+234 826 477 6022](https://wa.me/2348264776022)

---

## 📄 License

MIT License. Free for open-source and commercial use.# vortex-studio
