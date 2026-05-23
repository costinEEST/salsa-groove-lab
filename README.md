A browser-based salsa sequencer for studying how nine instruments lock together across the 8-beat clave cycle. Two independent implementations built from the same brief — choose either from the landing page.

## Features

- 16-step pattern editor (eighth-note resolution across two bars of 4/4)
- Nine synthesized tracks: clave, cáscara, campana, bongo, conga, bass, piano montuno, horns, coro
- Anticipated bass tumbao and piano guajeo over Dm ↔ G7
- Stem upload per track — demo synth mutes when a real audio file loads
- Swing knob, master volume, solo/mute per track
- Web Audio API, vanilla HTML/CSS/JS, zero dependencies

## The two builds

| | Opus build (`antropic.html`) | ChatGPT build (`openai.html`) |
|---|---|---|
| Aesthetic | Vintage hardware sequencer | Glassmorphic dashboard |
| Clave variants | 2-3 Son, 3-2 Son, 2-3 Rumba | 2-3 Son, 3-2 Son |
| Swing | Excluded from clave | Applied to all tracks |
| Stereo | Per-track panning | Per-track panning |
| Typography | Big Shoulders Display + Instrument Serif + JetBrains Mono | System Impact + monospace stack |

## Running

Open `index.html` in any modern browser. No build step, no `npm install`.
