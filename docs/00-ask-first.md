# 00 — Ask First: questions Muse MUST ask before any video

This file exists for one reason: **Muse must never start a video on a topic the user did not give.**

The process, specs, templates, and styles are all in this repo, so the user does not need to explain those again. But the **topic and the choices for that one video** can only come from the user. Asking for them is not optional, and it is not a delay — it is the first step of the workflow.

## The rule in one line

> No topic from the user = no script, no template, no render. Ask first, wait, then make a good video exactly according to the user's answers.

## What to ask, in order

Ask in the user's own language (Hinglish / Hindi as they use it). Ask only the questions that are still unanswered. Keep it to one short message.

1. **Topic — "Kis topic par video banani hai?"**
   - One line, in the user's own words. Do not rephrase it into a different topic.
   - If the user gives a reference reel / style, that is the style, not the topic. Still ask for the topic.
2. **Video type — "Kaisi video chahiye?"**
   - Reel (vertical 1080x1920, ~25–32s) or long video (landscape 1920x1080)?
   - If long video: sample (~1 minute) or full video (~10 minutes)?
3. **Length — only if it is not already fixed by the type.**
   - Reel: ~25–32s is the default range; confirm only if the user wants shorter/longer.
4. **CTA keyword — reels only.**
   - "Comment me kya likhne ko bolna hai?" e.g. FAST, QUIZ, EMAIL, BIO.
   - This word decides the DM reply, so do not invent it.
5. **Voiceover — "Voiceover kaisa ho?"**
   - AI voiceover, or will the user supply their own audio file (e.g. ElevenLabs)?
   - If the user will supply audio, wait for that file before timing scenes. Do not time scenes to a guessed duration.
6. **Style — only if the user has a preference.**
   - "Koi khaas style chahiye, ya main choose karu?"
   - If the user says "tum choose karo", choose decisively, name the style in one line, and do not ask again.

Suggest defaults in brackets to make answering easy, for example: "Reel chahiye ya long video? (default: reel)". A suggested default is not permission to start without an answer.

## Sample opening reply (when only the repo link is given)

> Video banane se pehle ye bata do, taaki video bilkul tumhare hisaab se bane:
> 1. Kis topic par video banani hai?
> 2. Reel chahiye (vertical, ~30 sec) ya long video (landscape)?
> 3. Reel hai to comment CTA keyword kya rakhu?
> 4. Voiceover AI se karu, ya tum apni audio doge?
> 5. Style koi khaas chahiye, ya main choose karu?
>
> Inke jawab milte hi main pehle script banaunga, phir usi ke hisaab se video.

## Sample reply (when the user gave only a topic)

> Topic mil gaya: [user's topic, as written].
> Bas ye 2-3 cheezein aur bata do: reel chahiye ya long video? CTA keyword kya ho? Voiceover AI se ya tumhari audio se?
> Phir main script se shuru karunga.

## What NOT to do

- Do NOT pick a topic yourself ("aaj AI tools par ek reel bana deta hoon") and start.
- Do NOT write a script for a topic the user never named, even as a "demo" or "sample", unless the user explicitly asked for a sample on any topic.
- Do NOT decide the CTA keyword, the video type, or the length silently and mention it only after the video is made.
- Do NOT ask the user to re-explain the process, the specs, or the style — those are in this repo. Ask only for the choices listed above.
- Do NOT ask the same question twice. If the user already answered it, use that answer.

## When you MAY decide yourself

Only when the user explicitly says, in their own words, "tum hi decide karo", "jo achha lage karo", or "koi bhi topic chalega". Then:

1. Tell the user in one line what topic, type, and CTA you chose.
2. Give them a chance to stop you ("agar ye topic nahi chahiye to bata do").
3. Only then start with the script.

## After the answers come in

1. Confirm the brief back in one line: topic + type + length + CTA (if reel) + voiceover.
2. Then follow the normal workflow: script first (`docs/01-scripting.md`), voiceover-anchored animation, distinct template, karaoke subtitles, per-second motion, verified render, approval before publishing (`docs/05-verification-and-publishing.md`).
3. Make the video well, according to the user's answers — not according to a topic or style you invented.
