# Hi, I'm SK

I build local-first tools: things that run on your own machine, keep your data on your own disk, and don't phone home unless you tell them to. Most of what's below started as "I wanted this and it didn't exist" — a converter, an exporter, a visualizer, a library fixer.

## Projects

| Project | What it does |
| --- | --- |
| [**kokoro-audiobook-studio**](https://github.com/S-k404/kokoro-audiobook-studio) | Turns textbooks and technical PDFs into chaptered M4B audiobooks, fully local on Apple Silicon (Kokoro TTS, Metal GPU). |
| [**notion-better-export**](https://github.com/S-k404/notion-better-export) | High-fidelity Notion workspace exporter — preserves folder hierarchy, Obsidian Bases, and linked CSV databases, instead of Notion's flat default export. |
| [**better-vert**](https://github.com/S-k404/better-vert) | Local-first universal file converter: 250+ formats via FFmpeg/ImageMagick, plus anything-to-Markdown via Microsoft MarkItDown, OCR, and Poppler. Web UI + interactive CLI in one Docker container. |
| [**music-tools**](https://github.com/S-k404/music-tools) | A CLI (`mt`) for curating a local music library — album art repair, artist art and lyrics fetching, duplicate detection, misidentified tag fixes, and library stats. |
| [**music-visualiser**](https://github.com/S-k404/music-visualiser) | Two visualizers, one repo: a macOS terminal app with real-time ASCII/pixel rendering synced to playback, and ESP32 + OLED firmware showing a live spectrum over Bluetooth A2DP. |
| [**odysseus-notion-skill**](https://github.com/S-k404/odysseus-notion-skill) | A read-only Notion tool/skill for the Odysseus local-model agent — search and read Notion live, with no writes and nothing cached to disk. |

## Notes

- Everything above is local-first by design: no required cloud dependency, no telemetry, data stays on disk unless the tool's whole point is to export it somewhere you chose.
- Each repo's README has full setup and usage instructions — the table above is just a map.
