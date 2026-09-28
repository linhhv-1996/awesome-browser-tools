# Awesome Browser Video Tools [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of free video tools that run in your web browser — no install, no desktop app, and (where marked) no upload.

Browsers can now decode and encode video natively through [WebCodecs](https://developer.mozilla.org/en-US/docs/Web/API/WebCodecs_API) and run full encoders like FFmpeg through WebAssembly. That means a growing number of tools can do real video work **on your own device** instead of sending your file to someone else's server. This list focuses on tools that are genuinely free to use, and flags which ones keep your file local.

**Legend**

- 🔒 Processes the file on your device — nothing is uploaded.
- ☁️ Uploads the file to a server for processing.
- 🧑‍💻 Open source.
- 👤 Requires an account for core features.

## Contents

- [Compress](#compress)
- [Convert and extract audio](#convert-and-extract-audio)
- [Transcribe and subtitle](#transcribe-and-subtitle)
- [Upscale and enhance](#upscale-and-enhance)
- [Trim, cut and edit](#trim-cut-and-edit)
- [GIFs and frames](#gifs-and-frames)
- [Screen and webcam recording](#screen-and-webcam-recording)
- [Players](#players)
- [Libraries for building your own](#libraries-for-building-your-own)
- [Why local processing matters](#why-local-processing-matters)
- [Contributing](#contributing)

## Compress

- [SquishyFile Video Compressor](https://squishyfile.com/) 🔒 - Shrink MP4, MOV, MKV, AVI and WebM by quality level or to an exact target size (e.g. 10MB, 25MB). Uses WebCodecs for speed with an FFmpeg/WASM fallback for older formats. No file-size cap, no watermark, works in Safari on iPhone.
- [SquishyFile 8MB Video Compressor](https://squishyfile.com/8mb-video-compressor) 🔒 - Same engine with the target preset to 8MB, plus guidance on how long a clip can be at each resolution.
- [SquishyFile Discord Video Compressor](https://squishyfile.com/discord-video-compressor) 🔒 - Presets for Discord Free, Nitro Basic and Nitro upload limits.

## Convert and extract audio

- [SquishyFile Video to MP3](https://squishyfile.com/video-to-mp3) 🔒 - Pull the audio track out of almost any video file as MP3.
- [SquishyFile MP4 to MP3](https://squishyfile.com/mp4-to-mp3) 🔒 - Extract MP3 audio from MP4 files locally.
- [SquishyFile MOV to MP3](https://squishyfile.com/mov-to-mp3) 🔒 - Handy for iPhone recordings and Mac screen captures.
- [SquishyFile MP4 to WAV / OGG / M4A](https://squishyfile.com/mp4-to-wav) 🔒 - Lossless or alternative audio formats when MP3 isn't what you need.
- [SquishyFile MP4 to WebM](https://squishyfile.com/mp4-to-webm) 🔒 - Convert to WebM for web embedding.

## Transcribe and subtitle

- [SquishyFile Video to Text](https://squishyfile.com/video-to-text) 🔒 - Turn speech in a video into a text transcript without uploading the file.
- [SquishyFile MP4 to Transcript](https://squishyfile.com/mp4-to-transcript) 🔒 - Transcript extraction tuned for MP4 recordings like meetings and lectures.
- [Whisper Web](https://github.com/xenova/whisper-web) 🔒 🧑‍💻 - OpenAI's Whisper model running in the browser via Transformers.js. Great for tinkering and self-hosting.
- [Subtitle Edit Online](https://www.nikse.dk/subtitleedit/online) - Browser version of the popular subtitle editor for timing and fixing SRT files.

## Upscale and enhance

- [SquishyFile Video Upscaler](https://squishyfile.com/video-upscaler) 🔒 - Upscale low-resolution clips toward 1080p or 4K directly in the browser.
- [SquishyFile Video Filter](https://squishyfile.com/video-filters) 🔒 - Apply stylized effects (VHS, sketch and more) to a video locally.

## Trim, cut and edit

- [Omniclip](https://github.com/omni-media/omniclip) 🔒 🧑‍💻 - Open-source, timeline-based video editor that runs fully in the browser.
- [Clipchamp](https://clipchamp.com/) 👤 - Microsoft's browser video editor with a solid free tier and templates.
- [Kapwing](https://www.kapwing.com/) ☁️ 👤 - Collaborative online editor with auto-subtitles and resizing for social formats.
- [CapCut Web](https://www.capcut.com/) ☁️ 👤 - Web version of CapCut with effects, captions and templates.
- [Online Video Cutter](https://online-video-cutter.com/) ☁️ - Quick trim, crop and rotate for one-off jobs, no account needed.

## GIFs and frames

- [SquishyFile MP4 to GIF](https://squishyfile.com/mp4-to-gif) 🔒 - Turn a clip into a GIF without uploading it. Also available for [MOV](https://squishyfile.com/mov-to-gif).
- [SquishyFile Frame Extractor](https://squishyfile.com/frame-extractor) 🔒 - Grab still frames from a video as images.
- [ezgif](https://ezgif.com/video-to-gif) ☁️ - The long-running Swiss army knife for GIF creation, optimizing and editing.

## Screen and webcam recording

- [Screenity](https://github.com/alyssaxuu/screenity) 🔒 🧑‍💻 - Privacy-friendly open-source screen recorder and annotation tool as a Chrome extension.
- [Loom](https://www.loom.com/) ☁️ 👤 - Record screen and camera and share a link instantly. Free tier has length limits.

## Players

- [Video.js](https://videojs.com/) 🧑‍💻 - The most widely used open-source HTML5 video player.
- [Plyr](https://github.com/sampotts/plyr) 🧑‍💻 - Lightweight, accessible, customizable media player.
- [Vidstack](https://www.vidstack.io/) 🧑‍💻 - Modern player components for React, Vue and web components.

## Libraries for building your own

- [ffmpeg.wasm](https://github.com/ffmpegwasm/ffmpeg.wasm) 🧑‍💻 - FFmpeg compiled to WebAssembly. Slower than native but handles nearly any format.
- [Mediabunny](https://github.com/Vanilagy/mediabunny) 🧑‍💻 - Pure TypeScript library for reading, writing and converting media files using WebCodecs.
- [Remotion](https://github.com/remotion-dev/remotion) 🧑‍💻 - Create videos programmatically with React.
- [Transformers.js](https://github.com/huggingface/transformers.js) 🧑‍💻 - Run speech recognition and other ML models client-side.
- [WebCodecs API (MDN)](https://developer.mozilla.org/en-US/docs/Web/API/WebCodecs_API) - Reference for the browser-native encode/decode API most modern tools are built on.

## Why local processing matters

Upload-based tools are convenient, but your file leaves your device, and free tiers often cap file size, add watermarks or require an account. Browser-local tools flip that trade-off:

- **Privacy** — personal videos, meeting recordings and client footage never touch a third-party server.
- **No upload wait** — a 2GB file doesn't need to cross your connection twice.
- **No size caps** — the limit is your own device's memory, not a pricing tier.

The trade-off is speed: encoding happens on your hardware, so a large 4K file on an older phone will take a while. Keep the tab in the foreground while it works — browsers throttle background tabs.

## Contributing

Suggestions welcome. Please open a pull request and make sure the tool:

1. Runs in a web browser (extensions are fine).
2. Has a genuinely usable free tier.
3. Is correctly labeled 🔒 or ☁️ — if you're not sure whether it uploads, leave the label off.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related rights to this work.
