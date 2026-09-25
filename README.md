# Sting Bench

**Try it: https://joonas98.github.io/sting-bench/**

Sting Bench makes short musical stings, the few-second musical moments you hear in video intros, podcast transitions, notification sounds and games. Pick a style, change the notes and instruments, and export the result as a WAV file.

Everything is synthesized in your browser. There are no samples, no sign-up and no server, so every sound you export is yours to use however you like.

## Getting started

1. Open the page and pick one of the styles, like **Piano Motif** or **Eerie Music Box**.
2. Press **Play** (or the Space key). With **Play on change** ticked, every tweak plays right away.
3. Press **New take** (V) to hear a different melody with the same settings.
4. When you like it, press **Export this take** to save a WAV.

Stuck for ideas? **Surprise me** (S) starts from a random style and reshuffles the key, chords, melody and ending.

## Styles

| Style | Character |
| --- | --- |
| Piano Motif | A simple, gentle piano phrase that lifts to a major chord at the end |
| Dark Piano | Low, slow piano with a soft boom |
| Eerie Music Box | A detuned music box winding down |
| Broken Music Box | Badly out of tune, warped and winding down hard |
| Dark Survival | Brass, choir and deep cinematic hits |
| Heroic Fanfare | Brass fanfare with timpani and a crash |
| Haunted Organ | Church organ and choir in a dark scale |
| Guitar Riff | Distorted power-chord riff with a lead guitar line |

The styles are starting points. Try putting a riff on a music box, a fanfare on a detuned piano or an organ in a major key.

## Controls

**Composition**
- **Harmony**: key, scale, chord progression, how it ends, chord style and chord color (plain triads, 7ths or 9ths).
- **Melody**: the shape of the tune (rising, arch, falling, valley, fanfare leap or wander), how many notes it plays per chord, and its octave.
- **Timing**: an exact length in seconds (or Auto), tempo, how long the final chord rings, and how much it slows down at the end.

**Sound**
- **Voices**: separate instruments for the lead, chords and bass, including piano, music box, clean and distorted guitar, brass, strings, organ and more.
- **Mix**: volume for each layer, plus the style's percussion. Set a layer to zero to mute it.
- **Character**: brightness, reverb, echo and **Eerie**, which adds out-of-tune notes and warped tape.

The piano roll shows what each layer plays, with the chord names underneath.

## Exporting

- **Export this take** saves one WAV file.
- **Export 6 takes** saves six versions with the same settings but different melodies, useful when a sound repeats often and shouldn't sound identical every time.
- **Export wave ladder** saves the same take at five intensity levels, from calm to full power, for moments that should build up over time.
- **Export level** sets how loud the files are. −1 dBFS is full loudness; lower it to leave headroom in your mix. **Preview volume** only changes what you hear in the browser.

Files are 44.1 kHz, 16-bit stereo WAV.

## Running it locally

It's a single `index.html` file with no build step. Download it and open it in a modern browser (Chrome, Edge, Firefox or Safari).

## Credits

Made by Joonas Suuronen ([@joonas98](https://github.com/joonas98)).
