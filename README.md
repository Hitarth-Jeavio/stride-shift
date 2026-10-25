# Stride Shift

A run-walk interval timer for weight loss. Pick a level, press Start, and it beeps (plus a voice cue) every time you should switch between running and walking.

**Live:** https://hitarth-jeavio.github.io/stride-shift/

## Levels

Each session has a 5-minute warm-up walk and a 5-minute cool-down walk around the intervals. Move up a level after 3 sessions that felt comfortable.

| Level | Run / Walk | Rounds | Running | Session |
|---|---|---|---|---|
| L1 | 1:00 / 2:00 | 10 | 10 min | 38 min |
| L2 | 1:30 / 2:00 | 9 | 13.5 min | 39.5 min |
| L3 | 2:00 / 2:00 | 8 | 16 min | 40 min |
| L4 | 3:00 / 1:30 | 7 | 21 min | 40 min |
| L5 | 4:00 / 1:30 | 6 | 24 min | 41.5 min |
| L6 | 5:00 / 1:00 | 5 | 25 min | 39 min |
| L7 | 8:00 / 1:00 | 4 | 32 min | 45 min |
| L8 | 10:00 / 1:00 | 3 | 30 min | 42 min |

**Sound modes** (Settings → Play with music):
- **On (default):** beeps play as short sound effects that mix with YouTube Music, Spotify and so on. They need the screen on, so use Lock screen.
- **Off:** the whole session plays as one audio track, so beeps keep going with the screen off, but the track pauses other music. If another app takes over the audio mid-session, the timer keeps counting and switches to the mixing beeps.

Voice cues and vibration only work while the screen is on.

During a session, **Lock screen** keeps the display on but ignores touches, so the phone can sit in a pocket or armband. Hold the lock icon for 1.5 seconds to unlock.

Add it to your home screen to use it like an app (it has an icon and opens without the browser bar).

A single static `index.html` with no build step. Session history stays in your browser's localStorage.
