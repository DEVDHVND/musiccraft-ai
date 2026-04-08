# 🎵 MusicCraft.ai

**A free educational music training tool — bridging AI music creation and real DAW production.**

[![Live Tool](https://img.shields.io/badge/Live%20Tool-Open%20MusicCraft.ai-7C3AED?style=for-the-badge)](https://www.perplexity.ai/computer/a/musiccraft-ai-ai-to-daw-traini-cay494xdTfC0sxKz_GKEQw)
[![License](https://img.shields.io/badge/License-MIT-EC4899?style=for-the-badge)](LICENSE)
[![Version](https://img.shields.io/badge/Version-1.2.0-0EA5E9?style=for-the-badge)](https://github.com/deadhandcp/musiccraft-ai/releases)

---

## What It Does

MusicCraft.ai helps musicians, producers, and hobbyists **learn genre conventions, production styles, and song structure** — and supports the transition from using AI tools (Suno AI) to writing and producing music in a DAW.

### Features

| Feature | Description |
|---|---|
| 🎨 **Artist Style Reference** | Enter any artist — detects genre, era, mood, energy, production style, subgenre, and vibe. Auto-fills your entire prompt builder including all expanded sections. |
| 🔀 **Artist Blend Converter** | Enter 2+ artists (e.g. `Wreckno + Sleep Theory`) to blend their styles into an evocative fusion prompt. Each artist's sonic signature is shown. |
| 🖼 **Artist Profile Card** | Real artist photo, bio snippet, mini album covers, credit links to Spotify, Apple Music, YouTube, Last.fm, and MusicBrainz. |
| 🎛 **Suno v5.5 Prompt Builder** | Full prompt builder with Simple (≤200 chars) and Custom (≤1000 chars) output modes. Genre, subgenre, BPM, era, key, mood (50+), instruments (70+), vocals (30+), production, energy, texture, regional sound, groove feel, song length. |
| 🎲 **Randomize All / Genre Mash-up** | Instantly fill all fields randomly by genre, or blend two genres for experimental sounds. All new advanced sections included. |
| ✍️ **Emotion & Story Translator** | Describe a feeling or story in plain English — get it translated into an artist-style lyric concept, Suno lyric prompt, or songwriter's guide. |
| ✍️ **Lyric Generator** | 3 full original songs per click, Remi + Classic lyric model modes, 3-tab output, paste to lyrics. |
| 🎹 **DAW Transition Tab** | Chord progressions, MIDI suite generator (lead, chords, bass, arp), genuine variation every press, sync button, mix-up meter. |
| 🎓 **Production Learning Lab** | Describe a sound to recreate → get signal chain breakdown, plugin settings (Serum 2, Vital, stock), YouTube search links, Reddit communities. |
| 🎨 **Color Theme Picker** | 8 preset accent colors + full color wheel. |
| 💾 **Save HTML** | Download the entire app as a single self-contained HTML file. Works offline. |

---

## How to Use

### Option 1 — Live (no install)
[Open the live tool →](https://www.perplexity.ai/computer/a/musiccraft-ai-ai-to-daw-traini-cay494xdTfC0sxKz_GKEQw)

### Option 2 — Download & run locally
1. Go to [Releases](https://github.com/deadhandcp/musiccraft-ai/releases) and download `musiccraft-ai.html`
2. Open it in any modern browser (Chrome, Firefox, Safari, Edge)
3. No server, no install, no dependencies — 100% self-contained

### Option 3 — Clone and self-host
```bash
git clone https://github.com/deadhandcp/musiccraft-ai.git
# Open index.html in your browser, or host on any static file server
```

---

## What's New in v1.2.0

- **Emotion & Story Translator** — describe feelings/stories in plain English → lyric concepts, Suno prompts, songwriter guides in artist style
- **Production Learning Lab** — sound design breakdowns with Serum 2/Vital/stock plugin settings, YouTube search links, Reddit resources
- **Simple / Custom prompt modes** — ≤200 char Simple mode for Suno's Simple tab, ≤1000 char Custom mode
- **Genuine MIDI variation** — every Generate press produces different note contours (ascending/descending/arch/valley), different progressions, different register
- **Evocative artist blend** — sonic signatures per artist, role-aware fusion descriptions ("X meets Y, mic to Z")
- **70+ instrument chips**, 50+ mood chips, 30+ vocal style chips — all organized with show-more expand
- **4 new advanced builder sections** — Texture & FX, Regional Sound, Song Feel & Groove, Song Length
- **Full extended auto-fill** — artist convert fills every new chip group automatically
- **Terms of Use modal** on load
- **GitHub link** in header
- **Save HTML** button downloads offline version

---

## ⚖️ Legal Disclaimer & Acceptable Use

> **This tool is for educational and inspirational use only.**

- Artist name references are used solely to identify broad musical style characteristics
- MusicCraft.ai is **not affiliated with** any artist, label, publisher, or AI platform
- Generated content is algorithmically created — not derived from copyrighted works
- **You are solely responsible** for all content you create with this tool
- See the full [Terms of Use](https://github.com/deadhandcp/musiccraft-ai#%EF%B8%8F-legal-disclaimer--acceptable-use) displayed in the app on first load

---

## APIs Used (All Free / Public)

| API | Purpose |
|---|---|
| [MusicBrainz](https://musicbrainz.org/doc/MusicBrainz_API) | Artist lookup, genre tags |
| [TheAudioDB](https://www.theaudiodb.com/api_guide.php) | Artist photos, bio, album covers |
| [iTunes Search API](https://developer.apple.com/library/archive/documentation/AudioVideo/Conceptual/iTuneSearchAPI) | Apple Music artist URLs |

No API keys. No user data collected. No backend server. Everything runs client-side.

---

## Tech Stack

- **Pure static HTML/CSS/JS** — single file, zero dependencies, zero build step
- **Fontshare CDN** — Cabinet Grotesk + Satoshi fonts
- **Web File System Access API** — for saving MIDI files to disk

---

## License

[MIT License](LICENSE) — free to use, modify, and self-host. Attribution appreciated but not required.

---

*Made for musicians who want to understand their sound before they make it.*
