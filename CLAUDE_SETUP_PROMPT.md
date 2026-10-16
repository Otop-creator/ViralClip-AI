# ViralClip AI — Claude Desktop Setup Prompt

** By Otop Sirois • Experimental Beta**

This page is for anyone who would like **Claude Desktop to help install ViralClip AI on a Windows PC**, when computer use is available and explicitly authorized.

Computer use isn't available in every Claude setup. If it isn't available, Claude can guide you step by step instead.

## Copy the prompt below into Claude

```text
# VIRALCLIP AI — WINDOWS INSTALLATION & TEST

Help me install and test ViralClip AI — By Otop Sirois — on my Windows computer.

This is an EXPERIMENTAL personal project shared publicly for friends and others to try. It is not guaranteed to work and is not a professionally supported product.

Use Claude Desktop computer use only if available and I explicitly authorize you. Otherwise, guide me manually.

GITHUB:
https://github.com/Otop-creator/ViralClip-AI

GOAL:
Set up the free local AI services and verify that the app can generate a 9:16 gaming clip with subtitles. No paid AI APIs.

TASKS:
1. Verify Windows compatibility and free disk space (aim for at least 10 GB). Explain download sizes before continuing.
2. With my permission, open the GitHub Releases page. If no portable Windows release is available, stop and tell me. Don't pretend it's published.
3. Download ViralClipAI_Portable.zip from the official project release only after I approve. Extract to a folder I choose.
4. Verify ViralClipAI.exe and the required support files are present, including _internal, bin/ffmpeg.exe, and bin/ffprobe.exe where supplied.
5. Try launching the app. Do not install Python if the bundled app runs. Confirm bundled FFmpeg and FFprobe function.
6. Check whether Ollama is installed and running. If missing, explain what it is and ask before installing it from the official source.
7. Check whether the exact model llama3.2:3b is installed. If missing, ask before downloading it (about 2 GB), and confirm it works locally.
8. Check whether Whisper base is available to the app. If not, ask before its download (about 150 MB), and test transcription when practical.
9. Check that the UI and local AI connection work. Ask me to select a short test video I own or am permitted to process.
10. Run an end-to-end test: import → transcribe → rank highlights → crop 9:16 → add captions → export → play the MP4.
11. If anything fails, inspect the relevant error and viralclip.log locally and explain targeted fixes. Confirm before any substantial change.

IMPORTANT SAFETY RULES:
- Ask my approval before each software download, install, administrator prompt, system setting change, overwrite, or deletion.
- Use trustworthy official sources; never disable Defender, SmartScreen, or other protections.
- Never access saved passwords, browser cookies, authentication secrets, or private files unrelated to this task.
- Never upload my videos, logs, credentials, or personal files to external services.
- Do not publish, edit, or change any GitHub repositories.
- Stop if I withdraw permission.
- Do not claim success until actually tested on my computer.

FINAL REPORT:
List what passed or failed: app launch, FFmpeg, Ollama, llama3.2:3b, Whisper, clip ranking, vertical cropping, animated subtitles, MP4 playback. Explain any unverified parts clearly.
```

## Local AI requirements

| Component | Expected location |
| --- | --- |
| `ViralClipAI.exe`, `_internal/`, `bin/` | Included in portable app ZIP |
| FFmpeg + FFprobe | Included in inspected portable build |
| Ollama | Installed separately if absent |
| `llama3.2:3b` | Model downloaded on first run if absent |
| Whisper base | Speech model downloaded if absent |

An internet connection is usually needed for initial downloads. Windows 11 64-bit is the target; 16 GB RAM is recommended.

> **Experimental software:** Even with Claude's help, the app may not work correctly on your machine. Review downloads and changes yourself.

---

** ViralClip AI — By Otop Sirois**
