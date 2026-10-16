# 🤖 Install ViralClip AI with Claude Desktop

**🎬 ViralClip AI — By Otop Sirois**

This is a ready-to-copy prompt for friends who have Claude Desktop and its **computer-use feature available and authorized**. It asks Claude to inspect the app, install missing local AI services with permission, and test a real clip. Computer use is not available in all environments; if unavailable, use the [manual installation guide](FRIEND_INSTALL_GUIDE.md).

## 📋 Copy this entire prompt into Claude

```text
# 🎬 VIRALCLIP AI — WINDOWS INSTALLATION & TEST

Help me install and test ViralClip AI — By Otop Sirois on my Windows computer.

Use Claude Desktop computer use only if that feature is available and I explicitly authorize it. If you cannot operate my computer, guide me through the steps instead.

PRIVATE GITHUB REPO:
https://github.com/Otop-creator/ViralClip-AI

Only use my already-authorized GitHub access. If I do not have permission to view the repository or no Windows release is available, stop and tell me.

GOAL:
Run ViralClip AI locally with automatic AI highlight selection, 9:16 video editing, and synchronized subtitles. No paid AI APIs.

TASKS:

1. Check my Windows version and available free disk space. Prefer at least 10 GB free, and let me know before any major download.
2. With my permission, download ViralClipAI_Portable.zip from the repository's Releases page and extract it to a location I approve.
3. Verify the extracted app includes ViralClipAI.exe and all neighbouring support files, including _internal, bin/ffmpeg.exe and bin/ffprobe.exe where present. Do not use PyInstaller's temporary build folder. Don't install Python separately if the packaged runtime works.
4. Launch ViralClip AI and examine the first-run setup. Check whether FFmpeg and FFprobe work from the app's bundled bin folder.
5. Check whether Ollama is installed and running. If missing, explain its purpose and size and ask permission before installing it from an official source.
6. Verify the Ollama model llama3.2:3b is installed. If missing, ask before downloading it (approximately 2 GB). Confirm the model can respond locally.
7. Verify the Whisper base speech model is available to ViralClip AI. If missing, ask before downloading it (approximately 150 MB). Confirm transcription works when possible.
8. Verify the interface opens and the local AI backend connects. If requested, test a public video URL only if downloading and reusing it is permitted.
9. Ask me to choose a short local test video I own or have permission to process. Attempt an end-to-end test: import → transcribe → rank moments → apply 9:16 crop → add animated captions → export playable MP4.
10. If something fails, inspect only relevant errors, setup diagnostics, and viralclip.log locally. Propose minimal fixes, explain major changes before making them, and report what remains unresolved.

SAFETY & PRIVACY:
- Ask my approval before downloads, installations, admin elevation, file overwrites, deletions, or system configuration changes.
- Prefer the app's guided setup and official software sources.
- Don't disable Windows Defender, SmartScreen, antivirus, or other protections.
- Don't access browser cookies, saved passwords, or credentials.
- Don't upload my videos, transcripts, logs, or personal files anywhere.
- Don't publish or alter my GitHub repositories.
- Don't claim success without actual end-to-end testing.
- Stop if I withdraw permission.

FINAL REPORT:
Give me a concise pass/fail checklist for:
- App launch
- Bundled FFmpeg
- Ollama running
- llama3.2:3b working
- Whisper base transcription
- AI highlight selection
- Vertical crop and subtitles
- MP4 export and playback

Explain any remaining errors in simple terms.
```

## ⚙️ Services needed

| Component | How it is supplied | Purpose |
| --- | --- | --- |
| ViralClipAI.exe and `_internal/` | Portable ZIP | Runs the Windows app |
| FFmpeg + FFprobe | Bundled in `bin/` | Video processing |
| Ollama | First-run install, if missing | Local AI runtime |
| `llama3.2:3b` | Download if missing (~2 GB) | Highlights and prompts |
| Whisper base | Download if missing (~150 MB) | Transcription/caption timing |

Windows 11 is the target; at least 16 GB RAM is recommended. Sizes vary by version. **A portable ZIP must be extracted fully before launching.**

## 🔒 Private beta

Only invited GitHub collaborators can open this private repository. Please don't redistribute the app without checking with the creator. Only process videos you own or are permitted to use.

**💜 ViralClip AI — By Otop Sirois**
