# 🎬 ViralClip AI
### Local AI Video Clipping • Highlights • Animated Subtitles • Shorts

**Created by Otop Sirois**

> **EXPERIMENTAL PROJECT / EARLY BETA**
>
> ViralClip AI is a personal experiment I made primarily for **myself and my friends to try**. I'm sharing the project so others can experiment with it too.
>
> **This is not a finished or professionally supported product.** Expect bugs, unfinished features, inconsistent results, and possible compatibility problems. Use it at your own discretion and keep backups of important videos.

**Import → Analyze → Clip → Caption → Export**

## What is ViralClip AI?

ViralClip AI is an experimental Windows desktop app for identifying promising highlights in videos, gaming streams, and podcasts, then turning them into short vertical clips.

It is designed to use **free local AI**, rather than paid API credits. Processing speed and results depend on your computer, the video, and the models.

## Experimental features

- Import supported video links or MP4, MOV, MKV, and WEBM files
- Highlight recommendations powered by Ollama and Llama 3.2 3B
- Automatic Ollama startup when installed, with live connection status (v1.1.0-beta)
- Gaming clips with gameplay/facecam framing for vertical exports (still experimental)
- 9:16 YouTube Shorts, TikTok, and Reels formats
- Speech transcription and automatic animated subtitles
- Prompt-based requests, e.g. **"Generate 3 gaming clips in 9:16 with subtitles"**
- Preview, edit, and export MP4 clips

These are **experimental features**, not promises of reliable performance. AI highlight scores are subjective estimates, not guarantees of virality.

## Download and installation

**An experimental Windows beta is available.** The app has not been verified on every computer, so expect possible setup issues.

1. Open the **[latest ViralClip AI beta release](../../releases/latest)** or see **[all versions](../../releases)**.
2. Under **Assets**, download the portable ZIP file.
3. Right-click the ZIP → **Extract All**.
4. Open the extracted folder and double-click **`ViralClipAI.exe`**.
5. Follow the application's first-run setup for any missing AI tools or models. In v1.1.0-beta, the app checks for Ollama at startup and can start an installed Ollama service automatically.

**Keep the entire application folder together.** Do not use a lone `.exe` from a one-folder build, a `.lnk` shortcut, or a source-only ZIP as the portable app.

 **[Step-by-step installation guide](FRIEND_INSTALL_GUIDE.md)**

 **[Optional: Let Claude Desktop guide the installation](CLAUDE_SETUP_PROMPT.md)**

## Current beta

**v1.1.0-beta** adds automatic background startup for an installed Ollama service and a connection-status indicator. You still need to install Ollama and download the required models if they are not already present. Review exported clips before sharing, especially gameplay framing and subtitles.

## Requirements

- Windows 11, 64-bit: Main target; other platforms not verified
- RAM: 16 GB recommended
- Free disk space: Allow at least several GB for setup, app, and AI models
- FFmpeg + FFprobe: Included with the inspected portable build
- Ollama: Installed separately if missing
- `llama3.2:3b`: Local analysis model, approximately 2 GB
- Whisper base: Speech model, approximately 150 MB

An internet connection is needed for initial model downloads. No paid AI API credits are required for local inference.

## Bugs, limitations, and feedback

This app is a **personal learning and experimentation project**. It has not been independently validated across different Windows machines.

If something breaks, you're welcome to describe the problem. You can check **Settings → Open Log Folder → `viralclip.log`**. **Remove personal paths, secrets, and any private data before sharing logs publicly.**

Do not disable Windows security protections to run an unfamiliar binary. Inspect downloads and use only sources you trust.

**Only download and reuse videos you own or have permission to process.** Some sites restrict downloading and reuse.

## Note from the creator

I originally built ViralClip AI to experiment with clipping streams and generating Shorts for myself and my buddies. It's still a work in progress, but I figured I'd share the experiment for anyone interested in trying it out.

**Don't expect perfection. It's just a fun project I'm learning from.**

**ViralClip AI by Otop Sirois**

