# ViralClip AI — Installation Guide
### Experimental Early Beta • By Otop Sirois

Welcome! This started as a personal project for me and my friends, and it's now shared for anyone curious to test.

> **Experimental software.** Installation, AI models, cropping, captions, and exports may have bugs. This isn't a professionally supported release.

## 1. Download the Windows app

1. Visit **[ViralClip AI — Releases](https://github.com/Otop-creator/ViralClip-AI/releases)**.
2. If there is a beta release, download **`ViralClipAI_Portable.zip`**.
3. Right-click the downloaded ZIP and choose **Extract All**.
4. Open the extracted app folder and find **`ViralClipAI.exe`**.
5. Double-click it and follow the setup wizard.

**At present a Windows release may not yet be available.** If the Releases page is empty, wait for the creator to upload a tested ZIP.

 Keep the `ViralClipAI.exe`, `_internal/`, and `bin/` contents together.
 Don't run directly from the ZIP, and don't use a shortcut (`.lnk`) or PyInstaller's temporary `build` folder.

A correctly packaged portable app should not need Python installed separately.

## 2. Install the AI services

The inspected portable build already includes the Python runtime and video-processing tools (`bin/ffmpeg.exe` and `bin/ffprobe.exe`).

**First-run setup may still need to install these components:**

| Component | What it does | Approx. download |
| --- | --- | --- |
| **Ollama** | Runs local AI | ~0.7–1 GB |
| **`llama3.2:3b`** | Analyzes video transcripts and suggests highlights | ~2 GB |
| **Whisper base** | Speech transcription and subtitle timing | ~150 MB |

These sizes are estimates. Make sure you have free storage and a reliable internet connection. Approve installations only from trustworthy sources. If the app says FFmpeg is missing, first check that the `bin/` directory was kept with the EXE.

The setup wizard hasn't been verified on every Windows computer, so an installation may need troubleshooting.

## 3. Use ViralClip AI → → →

1. Open ViralClip AI.
2. Import an MP4/MOV/MKV/WEBM file or a supported video URL that you're permitted to use.
3. Try this prompt:
 > Generate 3 gaming YouTube Shorts in 9:16 with animated word-by-word subtitles. Keep both gameplay and the streamer's facecam visible; don't zoom in on the face.
4. Generate, preview, and export your clips.

Clip rankings, quantities, facecam layouts, and subtitles may vary depending on the recording and app version.

## 4. Optional Claude setup assistance

If your Claude Desktop installation supports **authorized computer use**, you can copy the ready-made prompt from **[CLAUDE_SETUP_PROMPT.md](CLAUDE_SETUP_PROMPT.md)**.

If computer use is unavailable, Claude can still walk you through these steps manually. Always approve installations and changes yourself.

## 5. Troubleshooting

- **App won't open:** Fully extract the ZIP and keep all bundled folders next to the EXE.
- **Ollama or model missing:** Reopen the app's setup wizard and verify installations.
- **Video URL fails:** Try a local video; some sites restrict downloads.
- **No captions:** Confirm the Whisper model installed and the video contains intelligible speech.
- **Gameplay barely visible:** Try a gameplay-first or split-screen framing option if your version supports it; cropping is still experimental.
- **Unexpected error:** Open Settings → Open Log Folder and inspect `viralclip.log`. Remove passwords, personal paths, or private content before posting any logs publicly.

**Privacy and safety:** Don't disable antivirus/Windows protections; review software warnings carefully. Only process material you have permission to use. The author can't guarantee support or compatibility.

---

 **ViralClip AI — By Otop Sirois**
*Made for fun, friends, and experimentation.*
