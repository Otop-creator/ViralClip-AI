# ViralClip AI

**Experimental local AI video clipping app for Windows**

Created by Otop Sirois. A personal project built for myself and friends to experiment with. This is an early beta, not a finished or professionally supported product.

## Latest download

**ViralClip AI V3.1 — v1.3.0-beta**

[Download ViralClip AI V3.1 Portable (Windows ZIP)](https://github.com/Otop-creator/ViralClip-AI/releases/download/v1.3.0-beta/ViralClipAI.V3.1_Portable.zip)

[View V3.1 release notes](https://github.com/Otop-creator/ViralClip-AI/releases/tag/v1.3.0-beta) | [Older versions](https://github.com/Otop-creator/ViralClip-AI/releases)

## Features (experimental)

- Import video files or supported video links
- AI-assisted highlight selection for streams, gaming videos, and podcasts
- Generate vertical Shorts with animated captions
- Automatic facecam and gameplay framing, with manual editing controls
- Facecam position and size: sliders, typed 0–100 % values, drag-to-reposition in the preview, Reset Position/Size
- Preview clip candidates first, then render only the ones you pick (Generate Selected)
- Batch queue for several videos or links, and viral score explanations (hook, humor, pacing, context, payoff)
- Clip library, project history, and clip deletion
- Save editing changes and export finished MP4 clips
- YouTube publishing through a personal Google OAuth connection
- Local AI analysis with Ollama and Llama 3.2 3B

These features are still being developed. Automatic framing, clip selection, saved edits, and uploads may not work perfectly on every system. AI scores cannot guarantee views.

## Installation

1. Download the **V3.1 portable ZIP** from the link above.
2. Right-click the ZIP and select **Extract All**.
3. Open the extracted application folder.
4. Run `ViralClipAI.exe`.
5. Follow any setup instructions for missing local AI tools or models.

Keep the entire extracted folder together. Do not run the EXE alone outside its packaged folder.

[Step-by-step installation guide](FRIEND_INSTALL_GUIDE.md) | [Claude Desktop setup prompt](CLAUDE_SETUP_PROMPT.md)

## Requirements

- Windows 11 (64-bit) is the main target
- 16 GB RAM recommended
- Several GB of free disk space for the app, temporary clips, and AI models
- Ollama and the `llama3.2:3b` model for local analysis, if not already installed
- Internet connection for setup, importing online videos, and YouTube publishing

No paid AI API credits are required for local analysis. YouTube publishing requires your own Google Cloud OAuth credentials and authorization.

## Bugs and feedback

ViralClip AI is a personal experiment. Expect bugs and compatibility issues; review generated clips before publishing and keep backups of important videos.

If something breaks, check **Settings → Open Log Folder → `viralclip.log`** when available. Remove personal information and tokens before sharing logs.

Only download, edit, and republish videos you have the necessary rights or permission to use.

**ViralClip AI by Otop Sirois**
