# 📥 ViralClip AI — Friend Installation Guide

**🎬 ViralClip AI — By Otop Sirois**

Welcome to the private beta! 🔒 This is a Windows desktop app for AI-assisted highlight clips, automatic subtitles, and Shorts.

## 1️⃣ Download & open

1. Sign in to the GitHub account **Otop invited** to this private repository.
2. Open **[ViralClip AI Releases](https://github.com/Otop-creator/ViralClip-AI/releases)**.
3. Download `ViralClipAI_Portable.zip` from the latest beta release **when available**.
4. Right-click the downloaded ZIP → **Extract All**.
5. Open the extracted folder and locate `ViralClipAI.exe`.
6. Double-click it. Keep all neighbouring folders and files, including `_internal` when present.

⚠️ **Do not open the EXE directly from the ZIP.** Do not use a `.lnk` desktop shortcut or the `build` folder: those aren't the transferable app. A correctly packaged Windows build should not require Python.

## 2️⃣ Complete first-launch setup ⚙️

The app may ask permission to download and install:

| Tool | Why it's needed | Approximate download |
| --- | --- | --- |
| FFmpeg | Video editing/export | ~100 MB |
| Ollama | Local AI runtime | ~0.7–1 GB |
| `llama3.2:3b` | Clip analysis model | ~2 GB |
| Whisper base | Transcription/captions | ~150 MB |

You may need several GB of free disk space and internet for initial setup. Check download sources and approve prompts; sizes are estimates. Retry unsuccessful installations.

## 3️⃣ Generate a clip 🎥 → 🧠 → ✂️ → 📱

1. Import an allowed video URL or a local MP4.
2. Enter: **“Generate 3 gaming highlights in 9:16 format with automatic animated subtitles.”**
3. Click **Generate Clips**.
4. Wait for processing, preview results, and export finished MP4 clips.

AI ranking is an estimate, not a promise of virality. The app may generate fewer clips if suitable moments aren't found.

## 4️⃣ Troubleshooting 🛠️

- **Doesn't start:** Make sure the entire ZIP was extracted and all app files stayed together.
- **AI model missing:** Retry setup and confirm Ollama/models installed.
- **Link import fails:** Try a video file on your PC instead; some sites restrict downloads.
- **Captions missing:** Verify Whisper installation and speech in the video.
- **Other failures:** Find `viralclip.log` from **Settings → Open Log Folder**; privately send relevant errors to Otop after removing sensitive details.

## 💜 Note from the creator

- Private beta for friends only; please don't redistribute.
- Local AI requires no paid per-token API credits.
- Process only video content you own or have permission to use.
- This app is still being tested on different Windows computers.

**ViralClip AI — By Otop Sirois**
