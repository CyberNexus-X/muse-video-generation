# 05 — Verification and publishing

## Verify the render — every time, before you say it is done

Check, on the real rendered file, not on the code or the plan:

- [ ] Duration matches the voiceover / target length
- [ ] Resolution and codec: reel 1080x1920, long 1920x1080, H.264 + AAC
- [ ] Frames at several timestamps actually show the right scene, template, and captions (for example, at the start, middle, and near the CTA)
- [ ] Karaoke highlight is on the word actually being spoken at that time
- [ ] No gap / floating element where two parts should join (leaf/stem, icon/card edges)
- [ ] Audio: voiceover audible throughout, SFX/music below it, no silent stretch that should have voice
- [ ] Previous version untouched; new version is a new file

If any check fails, fix that file (as a new version) and check again. **Never declare a fix complete from a size change, a code change, or a guess.** A fix is complete only when the real render has been checked.

## Sync fixes

- Scene boundaries must come from **real audio seconds**, not guessed timings.
- When a sync fix is made, regenerate SFX at the new times as well — old SFX timings will be wrong after a re-time.
- Report the sync windows you used (for example: scene 1: 0–6.3s, scene 2: 6.3–11.3s) so the next fix does not start from guesses.

## Publishing — approval first, verification after

1. Show the user the **exact video file, exact caption, and exact account**.
2. Get an explicit yes for that exact set. Pre-approval for a scheduled set must name each video, its time, and its account — a general "post my reels" is not approval for a specific set.
3. Post, then **verify the post is live and public** and report the real link.
4. If a post attempt is interrupted and its outcome is uncertain, check recent posts first for a duplicate before retrying. One retry only after confirming no post exists.

## Comment CTAs and DM replies

- A reel's caption promises a DM guide/link to anyone who comments the keyword.
- DM replies go **only to people who actually comment** with that keyword. Never send them in bulk, and never send them to people who did not comment.
- Use the approved reply text for that keyword, including the correct link. If the link was supplied later (for example, a tool's official page), use that exact link — do not invent or substitute a different tool or link.
- Keep a consolidated DM-reply pack (one file, all keywords, all reply texts) so no keyword's reply is improvised at send time.
- Outstanding DM replies are a real open task, not a note. Do not mark them done until they are actually sent to the actual commenters.

## What never to promise

- Views, ranking, or indexing — never promise these for a video, article, or link.
- A link placement on someone else's site without that owner's permission.
- A delivery time you have not verified. Report the last observed status, not a predicted finish time.
