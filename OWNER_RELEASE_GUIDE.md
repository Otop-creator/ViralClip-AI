# 📦 ViralClip AI — Owner's GitHub Upload Guide

**🎬 ViralClip AI — By Otop Sirois**

This guide is for Otop, to publish a **private beta download** for invited friends.

## ✅ 1. Find the finished app — use `dist`, NOT `build`

The Windows Explorer screenshot shows this location:

```text
Downloads\ViralClipAI_Final\viralclip_ai\build\ViralClipAI
```

⚠️ **This is PyInstaller's temporary build folder**, containing `.toc`, `.pkg`, and other build artifacts. **Don't ZIP or share it.**

1. In File Explorer, click the **`viralclip_ai`** breadcrumb in the address bar (or navigate two levels up).
2. Open the **`dist`** folder, which should be beside `build`.
3. Look for one of these layouts:

**One-folder output (common):**

```text
viralclip_ai/
└── dist/
    └── ViralClipAI/
        ├── ViralClipAI.exe
        └── _internal/
            └── ... supporting files ...
```

ZIP the entire `dist\ViralClipAI` folder. Include every file and folder inside.

**One-file output:**

```text
viralclip_ai/
└── dist/
    └── ViralClipAI.exe
```

If it's truly a **one-file** build and the app runs without a neighbouring `_internal` folder, ZIP that EXE. Also include any required external assets not bundled by the build.

If there's no `dist` output, the EXE build may be incomplete. Re-run `build_exe.bat` or ask Claude to fix it; don't publish the `build` folder.

## 🧪 2. Test before sharing

- Double-click the application **from the `dist` location**, not the `build` location.
- Verify the dashboard launches.
- Verify first-run component checks display correctly.
- Import a short video you have permission to use.
- Generate at least one 9:16 MP4 clip with captions.
- Confirm the output plays.
- If something fails, fix it first or clearly label the release as unverified.

## 🗜️ 3. Create the downloadable ZIP

1. Right-click the **entire finished `ViralClipAI` folder** inside `dist`.
2. Select **Compress to ZIP file**.
3. Name the archive **`ViralClipAI_Portable.zip`**.
4. Open the ZIP and confirm it contains `ViralClipAI.exe` and all needed supporting files.
5. Do **not** include your own source videos, transcripts, caches, logs, credentials, or personal settings.

## 🚀 4. Upload as a GitHub release

1. Open **[Create a Release](https://github.com/Otop-creator/ViralClip-AI/releases/new)**.
2. Create tag: `v1.0.0-beta`.
3. Title: **🎬 ViralClip AI — Private Beta | By Otop Sirois**.
4. Add a short description, e.g. `Private Windows testing build. Download and extract the ZIP, run ViralClipAI.exe, and complete first-run local AI setup. Windows compatibility is still being tested.`
5. Attach **`ViralClipAI_Portable.zip`** in **Assets**.
6. Select **Set as a pre-release** and publish.
7. Check the **[Releases](https://github.com/Otop-creator/ViralClip-AI/releases)** page to confirm the attachment appears.

Your repository is **private**. Keep it that way and invite only the friends who need access.

## 👥 5. Give friends access

Go to repository **Settings → Collaborators** and invite your friends by GitHub username.

**Important:** On a personal-account private repository, collaborators may have **write** access, not only downloads. Use a private organization with read-only permissions if that matters. Don't share account passwords.

Send your friends the repository's Releases link and **[Friend Installation Guide](FRIEND_INSTALL_GUIDE.md)**.

## 🛠️ If the portable version doesn't work

- Check that you zipped from `dist`, not `build`.
- Check whether `_internal` was included.
- Test on a second Windows computer when possible.
- Ask Claude to rebuild the app in PyInstaller **one-folder** mode and verify all runtime assets.

---

**💜 ViralClip AI — By Otop Sirois**
