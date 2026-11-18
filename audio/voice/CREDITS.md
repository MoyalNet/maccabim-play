# Recorded voice: source and credits

**AI-generated speech.** Every file in this folder was generated with ElevenLabs (elevenlabs.io), text to speech, model `eleven_v3`, on the project's ElevenLabs account, on **16 and 18 November 2026**. No human actor recorded these lines; they must not be presented as human recordings (research/licences.md, section 3).

Attribution owed on the free plan (research/licences.md, "Attribution lines", item 2): "Voices generated with ElevenLabs (elevenlabs.io)" in the game's credits, and `elevenlabs.io` in the title of the release page. Whether a free public game counts as non-commercial under the free plan's terms is an open question for the owner (licences.md, section 3).

| Folder | Lines | Voice (ElevenLabs name, id) | Speaker |
|---|---|---|---|
| `modiin/he/` | A01, A02, A05, A15, A03, A04, A07, A10, A20, A22-A26, A29, A30 (narrator) | Tomer - Calm, Curious Narrator (`yGpVFXFoImvRvaURKypy`, a voice made in this workspace) | Shimon, old, narrating |
| `modiin/he/` | A06, A09, A16-A19, A27 | Mattathias - Maccabim (`WVxFCHDrHvTd7H1aOSJM`, a designed voice saved in this workspace) | Mattathias |
| `modiin/he/` | A08, A28 | Dorian - Expressive Young man (`PBHwEnXdzx0yfhIO2UCH`, ElevenLabs library voice) | Judah |
| `modiin/he/` | A11, A12, A13, A14 | Itamar - Israeli Hebrew Narrator (`l7Q9rbdCC6j3J5dNlOOg`, ElevenLabs library voice) | the king's officer |
| `modiin/he/` | A21 | Erez - Natural Israeli Hebrew (`AZzja2JCoYeMe9vDQBll`, ElevenLabs library voice) | the man at the altar |

A01, A02, A05, A15 and the first A20 were generated on 16 November 2026; the other 25 lines and the A20 re-take on 18 November 2026 (round 2c, `docs/reports/voice-r2c.md`). The first A20 take (wrong readings of לדבר and לזבוח) is kept out of the game as `modiin/he/A20.old.mp3` and is not in the manifest.

Text sent for each line (the line of `src/scene/scenes/modiin-lines.ts` verbatim, with punctuation and niqqud added only for pronunciation and pace, and v3 delivery tags in brackets): `pipeline/audio/voice-takes.json`, with the ElevenLabs generation ids (flow `GkZaYv4tdOOjSUgDb8Zs`).

Mouth cues beside each file (`*.cues.json`): Rhubarb Lip Sync 1.14.0 (MIT), phonetic recogniser, made locally by `pipeline/audio/voice_manifest.mjs`; lip-sync data generated with Rhubarb belongs to the project.

Report: `docs/reports/voice-r1.md`.
