# AGENTS.md — Instructions for any Muse AI making a video from this repo

You are reading this because a user gave you this repo link instead of explaining everything again. **Follow this file by default. Do not ask the user to re-explain the process, the style, or the specs that are already written here.** Only ask for what is genuinely missing or undecided.

## 1. The one-line brief you need

Before you start, you need at most these things. If any are missing, ask one short question — do not ask for the whole process again:

- **Topic** (one line)
- **Video type:** short reel (vertical) or long video (landscape)
- **Length:** reel ~25–32s, long sample ~1 minute, or full long video (state the length)
- **CTA keyword** (reels only, e.g. FAST, QUIZ, EMAIL) — this is the word viewers comment to get a DM guide/link
- **Voiceover:** AI voiceover, or a file supplied by the user
- **Style, only if the user has a preference.** If they say "you choose", choose decisively and do not ask again.

If the user gives only a topic, assume: reel, Hinglish, AI voiceover, distinct template, karaoke subtitles, per-second animation — and say so in one line so they can correct you.

## 2. Script first, always

1. Write the script BEFORE building any video.
2. Show it to the user if it is a new topic, and wait for approval if they want to check it.
3. The script decides the scenes, the captions, and the timing. Animation follows the script; it never leads it.
4. If the user supplies their own script, keep it as written. Do not add a tool name, website link, brand, or claim that is not in their script. A link, if any, goes in the DM reply, not silently into the video.
5. If the user supplies their own voiceover audio, use that exact audio as the voiceover. Do not replace it with TTS.

## 3. Language

- **Reels and most videos: Hinglish.** Hindi in Roman script for the spoken script and on-screen text, unless the user supplies a Devanagari script — then keep Devanagari exactly as supplied.
- Keep sentences short, spoken, and phone-readable. No long paragraphs on screen.
- Numbers, steps, and tool names are in the script, not invented later.

## 4. How videos are actually made here

- Videos are **animated videos built with HTML/CSS animation and rendered to MP4**. They are not made by typing one prompt into an AI video generator and getting a finished realistic video.
- Do NOT attempt an AI video-generation tool as the main method, and do not retry it if it is blocked for the account/region. Say so plainly and use the HTML/CSS animation method instead.
- Each video gets **its own distinct template matched to its script and frames**. Never reuse one shared template across videos just by recolouring it.
- Animation must change **every second**: motion, a beat, a highlight, a new element — the screen must never sit still.
- Subtitles are **karaoke, word by word**: the currently spoken word is highlighted, upcoming words are muted, and the highlight moves with the audio. Not block text that appears all at once.
- Diagrams, cards, checklists, timelines, and icons are animated in — they are part of the explanation, not decoration.

## 5. Technical defaults (full specs in `docs/03-production-specs.md`)

- **Reel:** 1080x1920, 30 fps, H.264 video + AAC audio, ~25–32 seconds.
- **Long video:** 1920x1080, 30 fps, H.264 + AAC.
- Never overwrite a previous version. A remake, a fix, or a style change is always a **new file** (v2, v3, fixed-leaf, synced, etc.), so versions can be compared.
- Verify every finished file: duration, resolution, codec, and real frames at several timestamps. A file that only "should" be right is not done.

## 6. Sound defaults (full rules in `docs/04-sound-and-subtitles.md`)

- Voiceover is always the loudest layer.
- SFX: light whoosh + pop at scene starts, a thematic effect per video, a soft ding near the CTA. Keep them low.
- Background music, if used: a soft, synthesized, non-copyrighted loop, low under the voiceover.
- Never use copyrighted songs, music, or another creator's audio.
- If a new sound element is introduced, demo it on ONE video first and get the user's verdict on the level before rolling it out to other videos.

## 7. Originality — non-negotiable

- Style reference is allowed; copying is not. Study a reference reel's editing style (layout, colours, pacing, caption style), then write an original script and build original animation.
- Never copy another creator's script, lyrics, audio, brand name, or logo.
- If a reference has a brand mark, do not reproduce it.
- For sensitive topics (scams, security, health, money): give prevention / awareness only. No instructions, tool names, or steps that would let someone do the harmful thing, and no invented victim names, cases, or loss figures.

## 8. Before anything goes public

- Show the **exact video file, the exact caption, and the exact account**.
- Get an explicit yes for that exact set. A yes for one video is not a yes for another.
- For reels with a comment CTA, the DM reply is promised in the caption. DM replies go **only to people who actually comment** with the keyword, never in bulk, and the reply text must be the approved one (including the correct link, if any).
- After posting, verify the post is live and public, and report the real link. Do not report a post as done from a render or an upload step alone.

## 9. When you get something wrong

- Own it plainly and quickly, fix the real render, and check it again.
- If a tool fails, check the tool's own handling before concluding the user's file, credential, or input is wrong.
- If a version is disliked, ask one clarifying question if the dislike is vague — but if the user delegates the look to you, choose decisively and rebuild, do not ask again.

## 10. How to start a new video from this repo

Reply in this shape, then start:

> Topic, type, and length understood. Script first, then voiceover-anchored animation, distinct template, karaoke subtitles, per-second motion, verified render. Starting with the script now.
