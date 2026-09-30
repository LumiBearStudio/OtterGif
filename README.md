# OtterGIF

OtterGIF is a simple Windows app by LumiBear Studio that turns videos into GIFs.

- **Privacy Policy / 개인정보 처리방침**: [PRIVACY.md](PRIVACY.md) — the app collects no data and works fully offline.

## Third-party source code

OtterGIF bundles a copy of **FFmpeg** (`ffmpeg.exe`) built from unmodified source under the **GNU LGPL v2.1 or later**, statically linked with **zlib**.
The app runs `ffmpeg.exe` as a separate program and does not link to it.

The exact source archives used for each build are attached to the matching release:

| OtterGIF build | Sources |
|---|---|
| 1.0.0 | [ffmpeg-8.1.3 release](https://github.com/LumiBearStudio/OtterGif/releases/tag/ffmpeg-8.1.3) |

Each release contains:

- `ffmpeg-8.1.3.tar.xz` — FFmpeg source, unmodified (https://ffmpeg.org/releases/ffmpeg-8.1.3.tar.xz)
- `zlib-1.3.2.tar.gz` — zlib source, unmodified
- `BUILD-INFO.txt` — SHA-256 of the archives and every FFmpeg configure option used, so the binary can be rebuilt

FFmpeg is a trademark of Fabrice Bellard, originator of the FFmpeg project.

---

OtterGIF에 동봉된 ffmpeg.exe의 소스 코드(LGPL)와 빌드 정보를 공개하는 곳입니다. 파일은 [Releases](https://github.com/LumiBearStudio/OtterGif/releases)에 있습니다.
