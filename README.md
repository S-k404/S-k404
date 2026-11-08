# Hi, I'm SK

I build local-first tools: things that run on your own machine, keep your data on your own disk, and don't phone home unless you tell them to. Most of what's below started as "I wanted this and it didn't exist" — a converter, an exporter, a visualizer, a library fixer.

## Projects

| Project | What it does |
| --- | --- |
| [**kokoro-audiobook-studio**](https://github.com/S-k404/kokoro-audiobook-studio) | Turns textbooks and technical PDFs into chaptered M4B audiobooks, fully local on Apple Silicon (Kokoro TTS, Metal GPU). |
| [**aether-7**](https://github.com/S-k404/aether-7) | Cyberpunk telemetry HUD & Kiosk Monitor for Raspberry Pi 5 + 7-inch displays with Hailo-8 NPU / Coral TPU and Apple Silicon metrics. |
| [**flight-live**](https://github.com/S-k404/flight-live) | Native iOS & macOS flight activity tracking featuring Dynamic Island, Live Activities, lockscreen widgets, and Notion flight import. |
| [**notion-better-export**](https://github.com/S-k404/notion-better-export) | High-fidelity Notion workspace exporter — preserves folder hierarchy, Obsidian Bases, and linked CSV databases, instead of Notion's flat default export. |
| [**better-vert**](https://github.com/S-k404/better-vert) | Local-first universal file converter: 250+ formats via FFmpeg/ImageMagick, plus anything-to-Markdown via Microsoft MarkItDown, OCR, and Poppler. Web UI + interactive CLI in one Docker container. |
| [**grab**](https://github.com/S-k404/grab) | Fast parallel batch downloader for video streams, images, and files (`yt-dlp` + `ffmpeg`) with Web GUI, CLI, and browser extension. |
| [**fetch3d**](https://github.com/S-k404/fetch3d) | 3D rotating Apple-logo system fetch for macOS in zero-dependency pure C using Mach & sysctl APIs. |
| [**music-tools**](https://github.com/S-k404/music-tools) | A CLI (`mt`) for curating a local music library — album art repair, artist art and lyrics fetching, duplicate detection, misidentified tag fixes, and library stats. |
| [**music-visualiser**](https://github.com/S-k404/music-visualiser) | Two visualizers, one repo: a macOS terminal app with real-time ASCII/pixel rendering synced to playback, and ESP32 + OLED firmware showing a live spectrum over Bluetooth A2DP. |
| [**odysseus-speech-tools**](https://github.com/S-k404/odysseus-speech-tools) | Local speech engine (Kokoro-82M TTS + Faster-Whisper STT), document narrators (`narrator.py`), and audio pipelines (`pdf2epub_tts.py`) for the Odysseus workspace. |
| [**odysseus-image-tools**](https://github.com/S-k404/odysseus-image-tools) | MCP server and CLI for local image uncensoring, inpainting models, and detection tools for Odysseus. |
| [**odysseus-notion-skill**](https://github.com/S-k404/odysseus-notion-skill) | A read-only Notion tool/skill for the Odysseus local-model agent — search and read Notion live, with no writes and nothing cached to disk. |
| [**study-copilot**](https://github.com/S-k404/study-copilot) | Native macOS menubar study copilot with screen region OCR, conceptual problem explainer engine, and local offline practice quiz sandbox. |
| [**ascii-dino**](https://github.com/S-k404/ascii-dino) | Chrome Dino endless runner in the terminal written in Python `curses`, containerized with Docker. |
| [**esp32-sensor-probe**](https://github.com/S-k404/esp32-sensor-probe) | Precision environmental sensor probe suite (BME280, DHT22) with ST7789 IPS & SSD1306 OLED firmware in C++ and MicroPython. |

## Notes

- Everything above is local-first by design: no required cloud dependency, no telemetry, data stays on disk unless the tool's whole point is to export it somewhere you chose.
- Each repo's README has full setup and usage instructions — the table above is just a map.
