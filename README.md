# Bloodhound Studio — Procedural Rap Beat Maker

**Bloodhound Studio** is a zero-backend, browser-based rap beat generator powered by the **Web Audio API**. Choose a style, speed, tonality, and instruments to instantly generate full multi-section rap beats, test your flow with a built-in lyric pad and mic booth, and export studio-ready **MP3** or **WAV** instrumentals.

> 🔗 **Live Demo:** `https://marcotessarotto.github.io/bloodhound-studio/`

---

## Features

### 🎛️ Beat & Sound Controls
* **5 Rap Style Presets:**
  * **Boom Bap** — 90s NY dusty swing & warm sub bass
  * **Trap** — Half-time drums, hard 808s & fast hi-hat rolls
  * **Drill** — Syncopated bounce & sliding 808 basslines
  * **Lo-Fi** — Chill electric piano chords & vinyl crackle
  * **West Coast (G-Funk)** — Portamento synth leads & bouncy synth bass
* **Speed (BPM):** Smooth tempo control from `65` to `165 BPM`.
* **Tonality:** All 12 root keys (`C`–`B`) with 6 scales: *Natural Minor, Harmonic Minor, Phrygian, Dorian, Minor Pentatonic,* and *Major*.
* **Selectable Bass & Melodic Layers:**
  * Bass options: *Warm Sub / Boom Bass, Heavy Punch 808, Sliding Drill 808, G-Funk Synth Bass*
  * Toggleable layers: *Electric Piano, Dark Bells / Pluck, Synth Pad, G-Funk Lead, Vinyl Crackle FX*
* **Groove & Feel:** Adjustable **Swing** (`0–60%`), **Hi-Hat Rolls / Bounce** (`0–100%`), and **Humanize** (subtle timing and velocity variations).

### 🎼 Song Arrangement & Pattern Locks
* **3 Arrangement Modes:**
  * **4-Bar Seamless Loop** (ideal for importing into a DAW)
  * **Short Beat (24 Bars):** Intro → Verse → Hook → Outro
  * **Full Song (40 Bars):** Intro → Verse 1 → Hook → Verse 2 → Hook → Outro
* **Lock & Regenerate:** Lock *Drums*, *Bass*, or *Melody* independently and regenerate the unlocked parts until you find the perfect combination.

### 🎚️ Live Mixer & Visual Feedback
* **4-Channel Mixer:** Independent Volume, **Mute (`M`)**, and **Solo (`S`)** controls for **Drums**, **Bass / 808**, **Melody**, and **FX / Vinyl** (applied to both live playback and exported audio).
* **Real-Time Visuals:** Live audio spectrum visualizer, 16-step beat LEDs, and active song-section timeline.

### 🎤 Lyric Scratchpad & Mic Flow Booth
* **Lyric Scratchpad:** Built-in notepad that auto-saves locally in your browser (`localStorage`), complete with line/word counters and one-click copy.
* **Mic Flow Booth:** Test your vocals over the beat with a live input level meter, mic gain slider, optional headphone monitoring, and one-click **Beat + Vocal demo recording** (`.webm` download).

### 💾 Audio Export
* **MP3 Export:** Encoded directly in the browser at `192 kbps` (`44.1 kHz`, stereo) via `OfflineAudioContext` and `@breezystack/lamejs`.
* **WAV Export:** Uncompressed `16-bit PCM` WAV export (works 100% offline).

---

## How to Run Locally

1. Clone or download this repository:
   ```bash
   git clone https://github.com/YOUR-USERNAME/bloodhound-studio.git
