# Plant contacts: sources and licence

Moving through dry grass, bushes and thorny cushions (`src/audio/vegetation.ts`,
`docs/reports/sound-vegetation.md`). All files are cut from recordings released under
**Creative Commons 0 (public domain dedication)** on Freesound. CC0 asks for no credit; it is given
anyway. Licence re-read on each page on 15 Nov 2026. Sources (not shipped): `assets-src/downloads/freesound-<id>/`.

Freesound's CDN refused the original files of four of the five (HTTP 503 after the first download),
so those four are cut from Freesound's own HQ previews of the same recordings (MP3, about 200 kb/s).
`spikes/audio-veg/cut.py` cuts the same windows from the original WAVs once they are downloaded.

| Files | Source | Cut from (s) |
|---|---|---|
| veg-grass-01..08.mp3 | Freesound #611146, "Hiking Through Tall Dry Grass & Gravel.wav" by EverydayEldritch (original WAV). https://freesound.org/people/EverydayEldritch/sounds/611146/ | 6.7, 12.1, 14.3, 16.4, 24.5, 26.5, 36.3, 41.2 |
| veg-shrub-01..04.mp3 | Freesound #594774, "Bush Rubbing Movement" by EminYILDIRIM (HQ preview). https://freesound.org/people/EminYILDIRIM/sounds/594774/ | 0.2, 4.0, 12.0, 17.4 |
| veg-shrub-05..08.mp3 | Freesound #560560, "bushwhacking" by bittermelonheart (HQ preview). https://freesound.org/people/bittermelonheart/sounds/560560/ | 30.2, 38.2, 41.7, 51.1 |
| veg-thorn-01..05.mp3 | Freesound #871627, "Brambles and branches" by innov8_Music (HQ preview). https://freesound.org/people/innov8_Music/sounds/871627/ | 0.2, 9.1, 21.7, 28.8, 35.4 |
| veg-thorn-06..08.mp3 | Freesound #708145, "walking on dead twigs" by keahnpot (HQ preview). https://freesound.org/people/keahnpot/sounds/708145/ | 4.8, 10.7, 43.7 (its seconds 0-3 and 36-39.5, with a tonal line, are left out) |

Processing (`spikes/audio-veg/cut.py`): mono (mix of the two channels; none is in anti-phase),
48 kHz, high-pass 300 Hz (grass, thorn) or 250 Hz (shrub): the foot's weight is in the step bank, the
plants only rustle. Windows of densest contact (active 10 dB over the recording's floor for at least
60 % of the window); rejected if a narrow tonal line (bird, voice, hum) stands 12 dB over its
neighbours, if the contact is under 14 dB over the floor, or if the envelope is steady (CV under
0.35: a hiss). 5 ms / 60 ms fades, peak -3 dBFS, MP3 80 kb/s mono 48 kHz. Exact windows and
measurements per clip: `assets-src/audio/review/vegetation/clips.json` (not committed).
