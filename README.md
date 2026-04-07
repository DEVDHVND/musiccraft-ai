# 🎵 MusicCraft.ai

**A free educational music training tool — bridging AI music creation and real DAW production.**

[![Live Tool](https://img.shields.io/badge/Live%20Tool-Open%20MusicCraft.ai-7C3AED?style=for-the-badge)](https://www.perplexity.ai/computer/a/musiccraft-ai-ai-to-daw-traini-cay494xdTfC0sxKz_GKEQw)
[![License](https://img.shields.io/badge/License-MIT-EC4899?style=for-the-badge)](LICENSE)
[![Version](https://img.shields.io/badge/Version-1.0.0-0EA5E9?style=for-the-badge)](https://github.com/deadhandcp/musiccraft-ai/releases)

---

## What It Does

MusicCraft.ai helps musicians, producers, and hobbyists **learn genre conventions, production styles, and song structure** — and supports the transition from using AI tools (like Suno AI) to writing and producing music in a DAW (Ableton, FL Studio, Logic Pro, etc.).

### Features

| Feature | Description |
|---|---|
| 🎨 **Artist Style Reference** | Enter any artist — detects genre, era, mood, energy, production style, subgenre, and vibe. Auto-fills your entire prompt builder. |
| 🖼 **Artist Profile Card** | Real artist photo, bio snippet, album covers, and credit links to Spotify, Apple Music, YouTube, Last.fm, and MusicBrainz. |
| 🎛 **Suno v5.5 Prompt Builder** | Full prompt builder: genre, subgenre, BPM, era, key, mood chips, energy slider, instrument chips, vocal style, production style, and extra vibe field. |
| ✍️ **Lyric Concept Generator** | Remi and Classic lyric model modes. Generates 3 full original song options (3-tab output) with copy and paste-to-lyrics buttons. |
| 🎹 **DAW Transition Tab** | Chord progressions, MIDI suite generator (lead, chords, bass, arp), sync button, mix-up meter, and save-to-folder for FL Studio / Ableton. |
| 🎨 **Color Theme Picker** | 8 preset accent colors + full color wheel to customize the UI. |
| 💾 **Save HTML** | Download the entire app as a single self-contained HTML file. Works offline. |

---

## How to Use

### Option 1 — Live (no install)
[Open the live tool →](https://www.perplexity.ai/computer/a/musiccraft-ai-ai-to-daw-traini-cay494xdTfC0sxKz_GKEQw)

### Option 2 — Download & run locally
1. Go to [Releases](https://github.com/deadhandcp/musiccraft-ai/releases) and download `musiccraft-ai.html`
2. Open it in any modern browser (Chrome, Firefox, Safari, Edge)
3. No server, no install, no dependencies — it's 100% self-contained

### Option 3 — Clone and self-host
```bash
git clone https://github.com/deadhandcp/musiccraft-ai.git
# Open index.html in your browser, or host it on any static file server
```

---

## ⚖️ Legal Disclaimer & Acceptable Use

> **This tool is for educational and inspirational use only.**

- **Artist name references** are used solely to identify broad musical style characteristics (genre, tempo, mood, production era) — the same way a music textbook might reference an artist as an example of a style.
- MusicCraft.ai is **not affiliated with, endorsed by, or connected to** any artist, record label, music publisher, or rights holder referenced within the tool.
- **Generated content** (prompts, lyrics, MIDI patterns, chord progressions) is algorithmically created original content based on general genre conventions. It is not derived from, transcribed from, or substantially similar to any specific copyrighted musical work.
- **You are solely responsible** for all content you create, publish, or monetize using outputs from this tool.
- Deliberately using this tool to clone, impersonate, or substantially copy an artist's recognizable creative identity is a violation of the Terms of Use and may violate applicable law.
- The creator of MusicCraft.ai accepts **no liability** for misuse of this tool or any content generated through it.

By using this tool (live or locally), you agree to the [Terms of Use](https://github.com/deadhandcp/musiccraft-ai#%EF%B8%8F-legal-disclaimer--acceptable-use) displayed within the application on first load.

---

## APIs Used (All Free / Public)

| API | Purpose | Auth Required |
|---|---|---|
| [MusicBrainz](https://musicbrainz.org/doc/MusicBrainz_API) | Artist lookup, genre tags | None |
| [TheAudioDB](https://www.theaudiodb.com/api_guide.php) | Artist images, bio, albums | Free key (`1`) |
| [iTunes Search API](https://developer.apple.com/library/archive/documentation/AudioVideo/Conceptual/iTuneSearchAPI) | Apple Music artist URL | None |

No API keys are stored or required. No user data is collected. No backend server.

---

## Tech Stack

- **Pure static HTML/CSS/JS** — single file, zero dependencies, zero build step
- **Fontshare CDN** — Cabinet Grotesk + Satoshi fonts
- **Web Audio / File System Access API** — for MIDI file saving
- All data processing happens **client-side only**

---

## Contributing

Pull requests welcome. If you find a bug or want to add an artist to the style maps, open an issue or PR.

When adding artists, follow the existing pattern in `ARTIST_GENRE_MAP`, `ARTIST_OVERRIDES`, and `ARTIST_VIBE_MAP` inside `index.html`.

---

## License

[MIT License](LICENSE) — free to use, modify, and self-host. Attribution appreciated but not required.

---

*Made for musicians, by someone who wanted better AI → DAW tooling.*
