# Quantum Harmony Demo

**Listen:** https://maxkyliu.github.io/quantum-harmony-demo/

One song, three harmonies. YuE2 rendered its "City Lights" example three times with the same
melody, lyrics, style and seed. In two versions the chord progression was first reshaped by
Moth Quantum's `blur-midi-v1` engine (strength 0.3 and 0.5), using the `yue2_harmony.py` tool
from [moth-quantum-skills](https://github.com/maxkyliu/moth-quantum-skills).

| File | Chords |
| --- | --- |
| `original.mp3` | YuE2's own plan |
| `quantum-0.3.mp3` | 5 of 21 chords changed |
| `quantum-0.5.mp3` | 12 of 21 chords changed |

The MP3s are loudness-matched to about −15 LUFS.

2026-10-15: the two quantum versions were re-rendered with the fixed chord naming
(original chord kept unless clearly beaten, no invented slash basses). Same blur results,
same seed; the first versions are in this repo's git history.

## Credits

- Music generated with [YuE2](https://github.com/multimodal-art-projection/YuE)
  (m-a-p/YuE2-3B, seed 831001), under its individual-creator output permission.
- Lyrics and style prompt: YuE2's "City Lights" example, Apache-2.0, © the YuE2 authors.
- Quantum blur: [Moth Quantum](https://docs.mothquantum.com) `blur-midi-v1`.
- Page: MIT, see [LICENSE](LICENSE).
