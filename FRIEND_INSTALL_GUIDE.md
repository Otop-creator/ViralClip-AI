# 📥 ViralClip AI — Friend Installation Guide

**🎬 Created by Otop Sirois**

## 1️⃣ Download
1. Sign in to the GitHub account invited to this private repository.
2. Visit **[Releases](../../releases)** and download `ViralClipAI_Portable.zip` if a beta has been published.
3. Right-click ZIP → **Extract All**.
4. Open the extracted application folder.
5. Double-click `ViralClipAI.exe`.

⚠️ Keep the entire app folder together, including `_internal` if present. A Windows shortcut (`.lnk`) or source-only ZIP is not a usable portable application.

## 2️⃣ First-launch setup
The app may prompt you to install:

| Tool | Purpose | Approx. download |
| --- | --- | --- |
| FFmpeg | Video editing/export | ~100 MB |
| Ollama | Local AI runtime | ~0.7–1 GB |
| llama3.2:3b | AI ranking model | ~2 GB |
| Whisper base | Speech transcription/captions | ~150 MB |

Allow several GB of free storage. Check that downloads come from trustworthy sources and approve the setup prompts. A correctly packaged app should not require a separate Python installation.

## 3️⃣ Create clips
1. Import a permitted public video URL or a local MP4.
2. Enter: **"Generate 3 gaming highlights in 9:16 with automatic animated subtitles."**
3. Click **Generate Clips**.
4. Preview and export the clips.

Local processing time depends on hardware. Sometimes fewer suitable highlights are available.

## 4️⃣ Troubleshooting
- **App won't start:** Confirm the ZIP was extracted fully and all bundled files stay together.
- **AI missing:** Run first-time setup and verify Ollama/models are installed.
- **URL unsupported:** Try a local MP4 instead.
- **Captions missing:** Check that Whisper installed and the video contains audible speech.
- **Other error:** Send the relevant error from `viralclip.log` (Settings → Open Log Folder), with private information removed.

🔒 Private beta for invited friends. Please don't redistribute without permission. Only process content you're allowed to use.

**💜 ViralClip AI — By Otop Sirois**
