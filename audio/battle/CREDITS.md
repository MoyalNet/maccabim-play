# Battle and camp sounds (EB-12b): sources and licence

All files here are cut from recordings that carry the licence line **"CC0 1.0 Universal"** (Creative Commons 0, public
domain dedication) on their Internet Archive pages, read on 18 Nov 2026. CC0 asks for no credit; it is given anyway.

**Source collection:** "Red Library", a set of sound-effect items on the Internet Archive uploaded by Jason Scott on 19 May 2023, described there as "Sound effects from the USC Cinema and/or the Sunset Editorial
Collection ... digitized tapes provided by Craig Smith of USC". The CC0 dedication is the uploader's statement on those
pages; the chain of title of the old studio tapes was NOT verified (open decision in docs/reports/eb12b-real-sound.md).
These are film-library recordings of the 20th century, so what is on them (voices, steel, boots) is modern people and props:
it stands in for the scene, it is a dramatization (השלמה דרמטית), not a record of the period. The recordings were not listened
to by the developer; the owner decides.

Originals (not shipped): `assets-src/audio/review/eb12b/src-flac/`. Cuts, normalisation and encoding:
`spikes/battle/battleAudio-build-assets.py` (mono 48 kHz MP3; high-pass 60 Hz, fades, loops crossfaded, level normalised; nothing else).

| File(s) | Source item and track (page) | Cut from (s) |
|---|---|---|
| murmur.mp3 | Red_Library_Crowds_Men, "R16-17-Men Murmuring" https://archive.org/details/Red_Library_Crowds_Men | whole (16.8 s), 1.5 s crossfade loop |
| fire.mp3 | Red_Library_Fire, "R09-67-Small Crackling Fire" https://archive.org/details/Red_Library_Fire | 2-26, 2 s crossfade loop |
| embers.mp3 | Red_Library_Fire, "R09-68-Slightly Muffled Fire" | 2-26, 2 s crossfade loop |
| din.mp3 | Red_Library_Crowds_Outdoor, "R26-02-Excited Agitated Crowd Approaches" https://archive.org/details/Red_Library_Crowds_Outdoor | whole (19.2 s), 1.5 s crossfade loop |
| horn.mp3 | Red_Library_Bells_Horns_Whistles, "R12-46-Blowing Note on Cow Horn" https://archive.org/details/Red_Library_Bells_Horns_Whistles | 0-3.8 (a plain animal horn: type of 1 Macc 4:13 not given, a dramatization; not a shofar) |
| shout.mp3 | Red_Library_Crowds_Men, "R24-01-Men Rallying" | 7.5-11.0 |
| alarm-0..3.mp3 | Red_Library_Crowds_Men, "R15-73-Small Group of Men Shouting" | 1.0, 3.5, 6.0, 9.0 (0.7 s each) |
| gather.mp3 | Red_Library_Crowds_Men, "R08-58-Men Talking Quietly" | 0-3.2 |
| far-call-0..3.mp3 | Red_Library_Crowds_Outdoor, "R08-06-Outdoor Voices" | 16.5, 22, 30, 36 (1.2 s each) |
| run-out.mp3 | Red_Library_Footsteps_3, "R11-24-People Running Heavily" https://archive.org/details/Red_Library_Footsteps_3 | 0-3.4 |
| rout.mp3 | Red_Library_Footsteps_3, "R11-30-Men Running Together" | 2-16 |
| clash-0..3.mp3 | Red_Library_Weapons_Swords, "R26-33-Single Large Sword Hits" https://archive.org/details/Red_Library_Weapons_Swords | 0.74, 5.07, 23.42, 27.48 |
| block-0..3.mp3 | Red_Library_Weapons_Swords, "R19-45-Sword or Metal Objects hit Wood" | 5.78, 9.28, 11.74, 22.27 |
| block-break-0..3.mp3 | Red_Library_Weapons_Swords, "R27-03-Large Sword Rings" | 2.61, 5.36, 17.18, 26.94 |
| whoosh-0..3.mp3 | Red_Library_Weapons_Swords, "R26-27-Sword Whooshes" | 2.9, 5.53, 10.1, 11.92 |
| thud-man-0..3.mp3, thud-player-0..3.mp3 | Red_Library_Fights, "R24-08-Single Thumps or Whacks" https://archive.org/details/Red_Library_Fights | thud-man 4.66, 5.96, 7.1, 8.5; thud-player 0.16, 1.61, 17.16, 19.85 |

Direct file URLs: `https://archive.org/download/<item>/<track>.flac` (the track names are in the table). The licence line was read on each item's page (Crowds_Men, Crowds_Outdoor, Fire, Bells_Horns_Whistles, Footsteps_3, Weapons_Swords, Fights; the item metadata says the same).
