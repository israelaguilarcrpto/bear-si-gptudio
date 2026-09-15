# Bear-Si GPTudio 16.2+

Web DAW (Digital Audio Workstation) inspired by BandLab, built with Bear-Si aesthetic and no ads.

## Vision

Accessible music production without friction:
- Simple, intuitive interface (Android-first)
- Persistent local storage (IndexedDB)
- Real multitrack audio mixing
- IA integration (upcoming)
- No ads, no account required

## Current Status: 16.2 — GREEN CORE + Persistence

### ✅ Working
- Multiple simultaneous audio playback
- Per-track volume, pan, mute, solo
- Master volume & BPM
- Loop playback
- Timeline with playhead
- Save/load projects to IndexedDB (with audio Blobs)
- Android-optimized UI
- Light/dark theme

### 🎯 Next: 16.3
- Non-destructive region editing
- Markers/cues
- BPM-grid snap
- Basic crossfade
- Better session recovery

## Usage

1. Open `index.html` in Chrome/Android Chrome
2. Click **+ Añadir audio** to load audio files
3. Use transport controls (play/pause/stop)
4. Adjust volume, pan, mute, solo per track
5. Click **Guardar proyecto** to save locally
6. Click **Cargar proyecto** to restore

## Architecture

- **Frontend**: Vanilla JS, no frameworks
- **Storage**: IndexedDB (local, persistent)
- **Audio**: Web Audio API / HTMLAudioElement
- **Styling**: CSS Grid, mobile-responsive

## Design Principles

1. **No reinit**: Each release builds on the previous one
2. **Real functionality first**: Avoid UI-only features
3. **Android/Chrome first**: Optimize for mobile
4. **Persistent workflow**: Save/load without friction
5. **Green Core aesthetic**: Bear-Si visual identity

## Contributing

Please respect continuity. Test on Android. Preserve existing functionality.

---

**Made with 🐻 & 💚 for accessible music production.**
