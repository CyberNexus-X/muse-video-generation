# 00 — Ask First: questions Muse MUST ask before any video

This file exists for one reason: **Muse must never start a video on a topic the user did not give.**

The process, specs, templates, and styles are all in this repo, so the user does not need to explain those again. But the **topic and the choices for that one video** can only come from the user. Asking for them is not optional, and it is not a delay — it is the first step of the workflow.

## The rule in one line

> No topic from the user = no script, no template, no render. Ask first, wait, then make a good video exactly according to the user's answers.

## How to ask: ONE question at a time

This is the most important part of this file, and it overrides any habit of asking everything at once.

- **Ask exactly one question per message.** Send the question, stop, and wait for the user's answer.
- **Only after that answer, ask the next still-unanswered question.** Never send all the questions together as a numbered list, a form, or a batch in one message — even if that feels faster.
- Ask in the user's own language (Hinglish / Hindi as they use it). Keep each question short, with the default in brackets if there is one.
- If the user answers more than one thing in a single reply, accept all of it, skip those questions, and ask only the next missing one — still one at a time.
- The only exception is if the user explicitly says "sab ek saath pooch lo". Only then may you list the remaining questions together.

## What to ask, in order

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

## Sample conversation — one question at a time (when only the repo link is given)

Do NOT send the whole list below in one message. Send one line, wait, then the next.

**Muse (message 1 — only this):**
> Kis topic par video banani hai?

**User answers the topic. Muse (message 2 — only this):**
> Reel chahiye (vertical, ~30 sec) ya long video (landscape)?

**User answers the type. Muse (message 3 — only this, reels only):**
> Comment me kya likhne ko bolna hai — CTA keyword kya rakhu?

**User answers the CTA. Muse (message 4 — only this):**
> Voiceover AI se karu, ya tum apni audio doge?

**User answers the voiceover. Muse (message 5 — only this):**
> Style koi khaas chahiye, ya main choose karu?

Only after all of these answers, Muse confirms the brief in one line and starts with the script.

## Sample reply (when the user gave only a topic)

> Topic mil gaya: [user's topic, as written].
> Reel chahiye ya long video?
>
> (Wait for the answer. Do NOT add CTA, voiceover, and style questions in this same message. Ask those one by one afterwards.)

## What NOT to do

- Do NOT ask all questions together in one message, even as a short numbered list. One question at a time is the rule, not a suggestion.
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
