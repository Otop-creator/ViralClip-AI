# ViralClip AI — Publishing a Public Experimental Release
### By Otop Sirois

This is the creator's checklist for making a **publicly downloadable experimental beta**. ViralClip AI was mainly built for me and my friends to try, and other people are welcome to experiment too.

## 1. Check the app package

Use PyInstaller's **`dist/`** output, **not** `build/`:

```text
viralclip_ai/
├── build/ ← temporary build artifacts — don't upload
└── dist/
 └── ViralClipAI/
 ├── ViralClipAI.exe
 ├── _internal/
 └── bin/
 ├── ffmpeg.exe
 └── ffprobe.exe
```

If your build layout differs, keep every required runtime file. **ZIP the entire `dist/ViralClipAI/` folder**, not only the EXE.

## 2. Test before releasing

- Launch the EXE from the folder you intend to ZIP.
- Verify the interface opens and the first-run setup checks missing models.
- Import a short test recording you own or may use.
- Test at least one AI-selected clip with a playable MP4 output and captions.
- Check exported file names and locations.
- Be explicit about features you couldn't test.

 The current cropping and gameplay/facecam layouts are experimental. Don't promise they're always correct.

## 3. Privacy & dependency checks

Before making anything public:

- Remove personal videos, transcripts, project caches, log files, tokens, API keys, credentials, and personal system paths.
- Review the ZIP and project documents for private information.
- Check third-party redistribution licenses (including FFmpeg builds and bundled Python libraries) and any applicable attribution or notices.
- Only bundle software and models you're permitted to redistribute; when in doubt, let users download models from the original source on first launch.
- Don't tell testers to disable antivirus or bypass Windows security warnings.
- Prefer a clear version number and changelog for each new release.

## 4. Prepare `ViralClipAI_Portable.zip`

1. Right-click the complete portable application folder in `dist/`.
2. Choose **Compress to ZIP file**.
3. Name the archive `ViralClipAI_Portable.zip`.
4. Open the ZIP and confirm the EXE plus all supporting folders are included.

Do not upload `ViralClipAI_Final.zip` (source-only) as though it were the ready-to-run app.

## 5. Publish the beta on GitHub

1. Open **[Create a new release](https://github.com/Otop-creator/ViralClip-AI/releases/new)**.
2. Create tag: `v1.0.0-beta` (or the actual tested version).
3. Title: ** ViralClip AI — Experimental Beta | By Otop Sirois**.
4. Description:
 > Personal experimental project built mainly for myself and friends to try. Now sharing it for anyone interested. Expect bugs and compatibility issues; this is not a professionally supported product. Extract the ZIP, launch ViralClipAI.exe, and follow the local AI setup steps.
5. Attach `ViralClipAI_Portable.zip` in **Assets**.
6. Select **Set as a pre-release** and publish.
7. Verify the ZIP appears on the [Releases page](https://github.com/Otop-creator/ViralClip-AI/releases).

**A release cannot be downloaded until it has actually been uploaded and published.**

## 6. Make the GitHub repository public (when ready)

Once you've reviewed the repository for private information:

1. Open repository **Settings**.
2. Under **General**, scroll to **Danger Zone**.
3. Select **Change repository visibility** → **Make public**.
4. Review GitHub's confirmation and complete the visibility change.

 **Making a repository public exposes its contents and history to everyone.** Review carefully before confirming. Publishing the repository and uploading a release are separate actions.

## 7. After release

Share the repository link:
https://github.com/Otop-creator/ViralClip-AI

Ask testers for feedback. Keep changes incremental and label each unverified update as experimental.

---

** ViralClip AI — By Otop Sirois**
