# Muse Video Generation

## Ask first, one question at a time

- Never invent a topic and start a video on it.

- Ask exactly one question per message and wait for the answer before asking the next question.

- Start by asking which topic the video is about.

- Then ask whether the user wants a short reel or a long video.

- Then ask about length only when the video type does not already fix it.

- Then ask about audio language as its own question.

- Then ask about subtitle language and script as its own question, such as Roman Hinglish, Devanagari Hindi or English.

- Then ask about video language for on screen headings, cards and labels as its own question.

- Then ask about the comment CTA keyword for a reel, such as FAST, QUIZ or EMAIL.

- Then ask whether the voiceover comes from AI or from a file supplied by the user.

- Then ask whether the user wants a particular style or wants Muse to choose the style.

- Accept an answer of same as audio or same as subtitle for a language question and skip the questions the user already answered.

- Start work only after the user answered, unless the user explicitly says Muse may decide everything.

## Write the script first

- Write the script before building any video.

- Show the script to the user for a new topic and wait for approval when the user wants to check it.

- Keep a script supplied by the user exactly as written and do not add a tool name, link, brand or claim that is not in that script.

- Use a voiceover file supplied by the user exactly as supplied and do not replace it with generated speech.

- Keep prevention topics prevention only and do not add instructions, tool names or steps for a harmful act.

## Build the video

- Build an animated video with HTML and CSS animation and render it to MP4.

- Do not use an AI video generator as the main method for this workflow.

- Give each video its own template matched to its script and frames and do not reuse one shared template only by changing its colour.

- Change something on screen every second, such as motion, a beat, a highlight or a new element.

- Use karaoke subtitles that highlight one spoken word at a time and keep upcoming words muted.

- Keep the voiceover as the loudest layer.

- Use only synthesized or royalty free sound effects and music and keep them low under the voiceover.

- Use a reel size of 1080 by 1920 at 30 frames per second with H264 video and AAC audio and a length near 25 to 32 seconds.

- Use a long video size of 1920 by 1080 at 30 frames per second with H264 video and AAC audio.

## Check and publish

- Verify the rendered file for duration, resolution, codec and real frames at several timestamps before reporting it as done.

- Never overwrite a previous version and save a remake, fix or style change as a new file.

- Show the exact video file, the exact caption and the exact account and get an explicit yes for that exact set before anything goes public.

- Send a comment CTA DM reply only to a person who actually commented with that keyword and use the approved reply text.

- Report a published post only after checking that the post is live and public and return its real link.

- Keep original content only and treat another creator's work as style reference only, never as a script, lyric, audio or brand to copy.

## Available connectors

- [Instagram](/opt/hatch/connectors/instagram/CONNECTOR.md) for publishing reels to an account the user approved, after showing the exact video and caption.

- [Instagram Messages](/opt/hatch/connectors/instagram_messages/CONNECTOR.md) for reading and sending approved DM replies to actual commenters.

- Use `muse.connector_search` to find other connectors and `muse.skill_search` to find related skills.

- If nothing here fits, look on the web for a maintained API or MCP server and set it up with [Custom Connectors and MCPs](/opt/muse/skills/custom-connector-setup/SKILL.md), or build a custom connector.

## Alternatives for better results

- Demo a new sound element on one video first and get the user's verdict on its level before using it in other videos.

- Turn one long video into several short reels only when the user asks for that cut down, with a new script and template for each reel.

- When the user dislikes a version, ask one clarifying question about what to change and rebuild that version as a new file.
