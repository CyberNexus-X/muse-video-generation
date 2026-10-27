# Muse Video Generation Guide

## About

**Muse Video Generation** is a complete, self-contained guide that teaches any Muse AI how to make good videos the right way — without the user having to explain the whole process again every time.

It covers, in detail: how to write a script, what kinds of videos to make, which template fits which script, the exact technical specs, how karaoke subtitles and sound should work, and how a finished video must be verified before anything is published.

Videos made from this guide are **script first, audio anchored, animated with HTML/CSS, and verified frame by frame** — not a single AI prompt that magically makes a finished video, and not copied content from another creator.

**Important: this repo does NOT make Muse start a video on its own.** Muse must first ask the user what video to make (see "Ask first" below), wait for the answer, and only then make the video according to the user's instructions.

## How to use this repo

**For the user — 3 steps, nothing more:**

1. **Give Muse this repo link** — `https://github.com/CyberNexus-X/muse-video-generation` — or paste the contents of `AGENTS.md` into the chat.
2. **Answer Muse's questions — ek ek karke.** Muse tumse saare sawaal ek saath nahi poochhega. Wo ek sawaal poochhega, tumhare jawab ka wait karega, phir agla sawaal poochhega, is order me:
   - Kis topic par video banani hai?
   - Kaisi video chahiye — reel (vertical, ~30 sec) ya long video (landscape)?
   - Audio kis language me ho?
   - Subtitle kis language / script me ho? (Roman Hinglish, Devanagari Hindi, English — ya "same as audio")
   - Video me on-screen text kis language me ho? (ya "same as subtitle")
   - Reel hai to comment CTA keyword kya ho? (jaise FAST, QUIZ, EMAIL)
   - Voiceover AI se ho, ya tum apni audio doge?
   - Style koi khaas chahiye, ya Muse choose kare?
   
   Bas ek ek karke jawab do. Process, specs, template, subtitles aur sound ke baare me dobara kuch batane ki zaroorat nahi hai — wo sab is repo me likha hai.
3. **Script check karo, phir video lo.** Muse pehle script banayega, phir usi script aur tumhari audio ke hisaab se video banayega, aur publish karne se pehle exact video, caption aur account dikhakar tumse approval lega.

**For Muse AI reading this repo:**
Read `AGENTS.md` first, then `docs/00-ask-first.md`. Do not start a video until the user has told you the topic and type. Do not invent a topic. After the user answers, follow the workflow in order: script → voiceover → distinct template → per-second animation + karaoke subtitles → sound → verified render → approval before publishing.

## Ask first — the most important rule in this repo

Muse apne aap kisi bhi topic par video **nahi** banayega, aur saare sawaal ek saath bhi **nahi** poochhega.

- Sirf repo link milne par, ya sirf "video banao" kehne par, Muse rukega aur pehle sirf ek sawaal poochhega: kis topic par video banani hai?
- Tumhare jawab ke baad hi wo agla sawaal poochhega, phir uske baad agla — ek ek karke, har jawab ka wait karke.
- Topic, video type, audio language, subtitle language, video language, CTA aur voiceover user batayega — tabhi video banegi, aur bilkul user ke hisaab se banegi. Audio, subtitle aur video ki language alag alag ho sakti hai, isliye ye teeno alag alag sawaal poochhe jayenge.
- Sirf tab Muse khud topic choose kar sakta hai, jab user khud kahe "tum hi decide karo / koi bhi topic chalega" — aur tab bhi shuru karne se pehle wo apni choice ek line me batayega.
- Poora question list aur sample replies: `docs/00-ask-first.md` me hain.

## What kind of videos does this cover?

1. **Short vertical reels (Instagram Reels / Shorts)** — 1080x1920, roughly 25–32 seconds, Hinglish, one AI tool / one idea per reel.
2. **Long landscape videos** — 1920x1080, from a 1-minute sample up to a ~10-minute full video, Hinglish, one topic explained in scenes.

Both are made as **creative animated videos**, not plain text slides, and not copied content.

## Start here

| File | What it tells the AI |
|---|---|
| `AGENTS.md` | The master instruction: the exact workflow, defaults, and non-negotiable rules. Read this first. |
| `SKILL.md` | The same workflow as a Muse skill: ask-first questions, script-first build, distinct templates, karaoke subtitles and verified publishing, in skill format. |
| `docs/00-ask-first.md` | **Ask first, one by one:** the questions Muse MUST ask the user (topic, type, audio language, subtitle language, video language, CTA, voiceover, style) before any video — exactly one question per message, never all together. Never start on your own topic. |
| `docs/01-scripting.md` | How to write a script: hook, structure, Hinglish, CTA. |
| `docs/02-video-types-and-templates.md` | Reel vs long video, and why every video gets its own template. |
| `docs/03-production-specs.md` | Exact technical specs: size, codec, timing, animation. |
| `docs/04-sound-and-subtitles.md` | Voiceover, karaoke subtitles, SFX and background music. |
| `docs/05-verification-and-publishing.md` | How to check a finished video, and the rules before posting. |
| `examples/reel-script-example.md` | A complete reel script in the house format. |
| `examples/long-video-outline-example.md` | A complete long-video scene outline in the house format. |
| `PROMPT-TEMPLATE.md` | The shortest brief a user can give: just fill the blanks. |

## The workflow in 30 seconds

1. **Ask first, one by one, then brief** — Muse asks the user for topic, then video type, then audio language, subtitle language and video language (each separately), then CTA keyword (if a reel), then voiceover — one question at a time, waiting for each answer. No video starts before this.
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

## Tags

Use these tags to find and describe this repo (also suggested as GitHub repo topics):

`muse-ai` · `muse` · `video-generation` · `ai-video` · `instagram-reels` · `youtube-shorts` · `hinglish` · `karaoke-subtitles` · `html-css-animation` · `video-scripting` · `content-creation` · `short-form-video` · `long-form-video` · `ai-tools` · `video-guide` · `ai-agents`

**Topics in one line:** muse-ai, video-generation, instagram-reels, hinglish, karaoke-subtitles, html-css-animation, video-scripting, content-creation.
