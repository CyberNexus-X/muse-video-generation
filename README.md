# Muse Video Generation Guide

> **How to use this repo:** Give any Muse AI this repo link, or paste the contents of `AGENTS.md` into the chat. After that, you do NOT need to explain the video-making process in detail again. The AI should follow this repo by default, and only ask you for the things that are genuinely missing: the topic, the video type, and the approval before anything is published.

This repo is a complete, self-contained guide for making videos the way they are actually made here: **script first, audio anchored, animated with HTML/CSS, verified frame by frame** — not a single AI prompt that magically makes a finished video.

## What kind of videos does this cover?

1. **Short vertical reels (Instagram Reels / Shorts)** — 1080x1920, roughly 25–32 seconds, Hinglish, one AI tool / one idea per reel.
2. **Long landscape videos** — 1920x1080, from a 1-minute sample up to a ~10-minute full video, Hinglish, one topic explained in scenes.

Both are made as **creative animated videos**, not plain text slides, and not copied content.

## Start here

| File | What it tells the AI |
|---|---|
| `AGENTS.md` | The master instruction: the exact workflow, defaults, and non-negotiable rules. Read this first. |
| `docs/01-scripting.md` | How to write a script: hook, structure, Hinglish, CTA. |
| `docs/02-video-types-and-templates.md` | Reel vs long video, and why every video gets its own template. |
| `docs/03-production-specs.md` | Exact technical specs: size, codec, timing, animation. |
| `docs/04-sound-and-subtitles.md` | Voiceover, karaoke subtitles, SFX and background music. |
| `docs/05-verification-and-publishing.md` | How to check a finished video, and the rules before posting. |
| `examples/reel-script-example.md` | A complete reel script in the house format. |
| `examples/long-video-outline-example.md` | A complete long-video scene outline in the house format. |
| `PROMPT-TEMPLATE.md` | The shortest brief a user can give: just fill the blanks. |

## The workflow in 30 seconds

1. **Brief** — topic + video type + CTA keyword (if a reel).
2. **Script first** — write and approve the script before any animation.
3. **Voiceover** — AI voiceover, or a voiceover file supplied by the user. The video timing is anchored to this audio, never the other way round.
4. **Template matched to the script** — a new, distinct look for each video, not a recoloured shared template.
5. **Animate every second** — something must move or change every second; karaoke subtitles highlight word by word.
6. **Sound** — SFX and music, if used, stay subtle and below the voiceover.
7. **Verify the real render** — check duration, size, codec, and actual frames. Never declare a fix complete from a size change or a guess.
8. **Approve before publishing** — show the exact video, caption, and account, and get a clear yes before anything goes public.

## Three rules that override everything else

1. **Original content only.** Another creator's work is style reference only. Never copy their script, lyrics, audio, or brand name, unless the user explicitly asks to adapt a theme — and even then, write an original script.
2. **Never claim a result you have not checked.** Check the rendered file, the live post, or the real page before reporting it.
3. **Nothing public without explicit approval.** No post, no upload, no public link without the user confirming the exact video, caption, and account.

## What this repo does NOT do

- It does not promise views, ranking, or indexing.
- It does not place links on other people's sites.
- It does not use copyrighted music, songs, or audio. SFX and music are synthesized or royalty-free only.
- It does not teach harmful skills. Prevention / awareness topics (for example, scam awareness) stay prevention-only: no instructions, tool names, or steps for doing the harmful thing.
