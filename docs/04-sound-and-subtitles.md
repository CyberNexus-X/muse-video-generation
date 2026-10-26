# 04 — Sound and subtitles

## Voiceover

- **Source, in order of preference:**
  1. A voiceover file supplied by the user (for example, ElevenLabs audio) — use it exactly as supplied.
  2. AI TTS voiceover in Hinglish, matching the approved script.
- The video's scene timing is anchored to the real voiceover audio. Measure the audio first.
- If TTS repeatedly returns empty audio for a line, soften that line's wording and retry. Do not skip the line silently.
- Voiceover is always the loudest layer. Everything else sits below it.

## Karaoke subtitles — the house standard

- **Word by word, not line by line.** The currently spoken word is highlighted; upcoming words are muted (grey); spoken words stay readable.
- Highlight style depends on the template: a black pill with a sweep underline, a black/accent highlight box on key words, or a white caption pill — but always word-by-word motion, never a whole block appearing at once.
- Captions sit in a lower third, in 2–3 short lines maximum, in a bold clean sans-serif.
- Captions must match the spoken script exactly. If the script changes, the captions change with it.
- The user has praised this karaoke style specifically. Do not replace it with plain block text cards unless the user explicitly asks for that exact style — and even then, keep the per-second motion if they still want it.

## Sound effects (SFX)

- Use **synthesized SFX only**. No copyrighted music, songs, or audio.
- Standard pattern:
  - Light whoosh + pop at each scene start
  - A thematic effect per video (for example, tick sounds as checklist items tick; a pop for each new card)
  - A soft ding near the CTA
- Keep SFX clearly lower than the voiceover.
- **Demo first:** when SFX is new, demo it on ONE video, get the user's verdict on the level, and only then roll it out to other videos.

## Background music

- Use a **synthesized, non-copyrighted loop only** (for example, a soft arpeggio loop).
- Keep it low under the voiceover at all times. If the voice is hard to hear, the music is too loud — lower it, do not raise the voice to compete.
- If SFX + music are added to an existing video, deliver it as a new file (`-sfx-music`), with the original untouched.
- Never add a copyrighted song "for feel", even for a demo.

## Silence vs sound

- A style recreation delivered without audio is a **silent version**. Label it silent. It is not finished sound work.
- A version with voiceover + SFX is a different file from the silent original. Both are kept.
