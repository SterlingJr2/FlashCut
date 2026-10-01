# FlashCut

FlashCut is a local-first, GPU-aware desktop video editor.

## v0.1.1-beta source package

Download `FlashCut-MVP-source-v0.1.1-beta.zip`, extract it, and open the extracted folder in Codex.

### Build on macOS

1. Put executable macOS `ffmpeg` and `ffprobe` files in `vendor/ffmpeg/macos/`.
2. Run `chmod +x vendor/ffmpeg/macos/ffmpeg vendor/ffmpeg/macos/ffprobe`.
3. Run `npm ci`.
4. Run `npm run package:mac`.

The resulting macOS ZIP is created in `dist/`.

Windows beta builds are self-contained and include their own FFmpeg files.
