# 03 — Production specs

## Output specs — check these on every file

| | Reel | Long video |
|---|---|---|
| Resolution | 1080x1920 (vertical) | 1920x1080 (landscape) |
| Frame rate | 30 fps | 30 fps |
| Video codec | H.264 | H.264 |
| Audio codec | AAC | AAC |
| Length | ~25–32 seconds | Sample ~50–60s; full ~9–10 min |
| Subtitles | Karaoke, word by word | Karaoke, word by word |

## Animation rules

1. **Motion every second.** Something must change every second: a beat pulse, a dot, a rotating arc, a pill/box highlight, a new card, a tick, a count. A still screen is a defect.
2. **Smooth or fast, as the style demands — never accidental.** Some styles use fast pop transitions; others use smoothstep eased motion. Pick one per video and stay consistent inside that video.
3. **Scene changes every 1–3 seconds in long videos** (for full recreations / fast-paced versions). Do not hold one static frame for a long stretch.
4. **Animated icons where the script names them:** for example, scammer, emergency, victim, phone, shield, checklist, clock — simple emoji-style animated icons, drawn/animated, not copied artwork.
5. **Details must connect.** A leaf must be a proper pointed-oval leaf with a vein, and its stem must overlap inside the fruit/object so no gap shows — not a flat triangle floating separate from it. This is the general rule: check joins, stems, and overlaps at real frames, not just in code.

## Versioning

- **Never overwrite a previous version.** Every remake, fix, style change, or sync fix is a new file: v1, v2, v3, `-fixed-leaf`, `-synced`, `-sfx-music`, etc.
- Keep the previous version untouched so versions can be compared.
- A "new version" that only changes audio (SFX/music) still gets a new file, with the video untouched otherwise.
- When you deliver a file, report: filename, duration, resolution, codec, and what changed vs the previous version.

## Rendering and file handling

- Render the full video, then verify it — do not deliver a preview, a script, or a single frame as if it were the video.
- If a render fails partway, check what actually rendered before re-rendering. Do not assume the failure left nothing behind.
- Keep scripts, captions, and DM reply texts alongside the video (for example, a `SCRIPTS_AND_CAPTIONS.md` in the video's folder), so a later video or DM reply can be checked against the approved text.
