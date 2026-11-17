# Legends & Betrayals: Channel Archive

YouTube: [@LegendsBetrayals](https://www.youtube.com/@LegendsBetrayals): cinematic dark-history documentaries about the betrayals that shaped history.

This repository keeps every video's script, full SEO package, file names and thumbnail prompt, plus a log of every change and its results.

## Structure

```text
README.md        Channel strategy and rules (this file)
changelog.md     Every change to a live video, with views before and after
videos/
  YYYY-MM-DD-topic/
    script.md        The video script (when available)
    seo-package.md   Title, file names, thumbnail text, description, tags,
                     playlists, pinned comment, chapters, thumbnail prompt
  upcoming-topic/    Videos not yet published
```

## Strategy

- **Target audience:** US, UK and English-speaking viewers. Each package includes a "Western hook": a film, series or event those viewers already know that honestly connects to the story (Game of Thrones, Magnificent Century, Nolan's The Odyssey, Anastasia, America 250).
- **Topics:** about 3 in 4 videos on topics Western viewers already care about (Rome, Tudor and British treason, WWII traitors, American betrayals). Ottoman and South Asian topics are the other 1 in 4.
- **Length:** breakout videos in this niche run 20–45 minutes. Build toward longer videos over time.
- **Publish time:** 11 pm to 12 am Pakistan time (afternoon in New York, evening in London).

## Package rules

1. **Title:** start with the primary keyword (search brings almost all views on this channel), then the hook. Score 4–6 keyword-first options in vidIQ and aim for 95+. Keyword once, correct English, no space before "?". Never change the title of a video that is getting search views.
2. **Description:** primary keyword plus the hook in the first ~150 characters; chapters matched to the final edit; Watch Next link; playlists; credits; subscribe link; about; disclaimer; 5–8 hashtags, never #Shorts on a long video.
3. **Tags:** 450–500 characters counted the way YouTube does; strong searched phrases, no channel-name tag while the channel is small, no other channels' names, no off-topic or vague tags.
4b. **Tags and description match:** every important tag phrase also appears naturally in the description; when tags change, the description is rewritten to match.
4. **File names:** `[primary-keyword]-[title-hook].mp4` and `[primary-keyword]-[thumbnail-text]-thumbnail.jpg`, lowercase, hyphens. Thumbnails exported as JPG, 1280×720, under 2 MB.
5. **Accuracy:** recent events are checked against news sources; unconfirmed claims become questions.

## Thumbnail system: the "Gunpowder" movie poster (v4, approved 28 Oct 2026)

The model for every thumbnail is the Gunpowder Plot poster: King James walking in glory above ground, Guy Fawkes with a glowing match in the cellar directly beneath him, a fuse running from "ONE SPARK. / NO KING." into the gunpowder, and the creator holding a lit match with a "Should I light it?" half-smile.

Every thumbnail needs 4 things, with a fresh idea for each story:

1. **One high-concept image built on dramatic irony, in ONE continuous scene** (no upper/lower split, since it makes characters too small). The main character is big and close, with the threat behind him, in the shadows, or leaking through a crack or door.
2. **The creator in the story, holding its key prop** (match, lantern, silk cord, letter), lit by it, with an in-character expression.
3. **The title physically linked to the scene** (a fuse, a bulb cord, a silk cord).
4. **A catchphrase a stranger understands instantly.**

Layout: story left ~65%, creator right ~35%, torn white-edged divider with a red glow, bottom-right corner empty. Text top-left in an ultra-heavy wide sans (line 1 white, line 2 yellow #FFE600 and 1.5× taller), with story textures, one letter replaced by a story object, and a red date stamp.

**Safety:** no blood, bodies, explosions or weapons aimed; no children in danger; no Nazi symbols; no real politicians in invented scenes; no copyrighted masks or characters; historically accurate details.

## YouTube Studio settings (every video)

Category: Education · Type: Documentary · Made for kids: No · Language and caption language: English · Altered or synthetic content: Yes

## Playlists

- Greatest Traitors in History: https://www.youtube.com/playlist?list=PLVl9aBiTjyjE
- Dark Deceptions & Legendary Tricks: https://www.youtube.com/playlist?list=PLHkWplx2KUS0
- Royal & Court Betrayals: https://www.youtube.com/playlist?list=PLDWuBNf97bCQ
- Empire Betrayals: https://www.youtube.com/playlist?list=PLYH9HlNk65Wc
- Modern & Geopolitical Betrayals: https://www.youtube.com/playlist?list=PLJb4bXnjfAug
- Ottoman Empire: not created yet

## Re-optimizing old videos

Edit in place, never re-upload the same file. Change title and thumbnail together, then compare views and click-through rate after 7 days, and log it in `changelog.md`.

## Script rules (from 13 Nov 2026)
- Scripts: ultra hook → montage → chapter montages → final teaser of the next video in VIDEO-ORDER.md. Narration only, no B-roll or prompts.
- Research based: name sources inside the narration where it adds authority ("According to the FBI's own Inspector General report…", "In his book … historian X writes…"). Quote real lines (letters, court records) word for word.
- Contested claims are flagged in the narration ("according to tradition", "never confirmed", "some historians believe it was exaggerated").
- Only call back to videos with a lower number in VIDEO-ORDER.md.
- Each video folder has sources.md; its SOURCES & FURTHER READING block goes into the description, after WATCH MORE and before Credits.
- Montage formula: 20-30 s; every line has a verb and an action; lines get shorter as they build; 2-3 open questions the video answers; one real quote as a jolt; ends on a title-card line. Never a list of "A [noun]..." fragments.
- Spoken sources name the person or institution ("the Justice Department's Inspector General", "historian William Dalrymple"), not long book titles. Each chapter ends on a turn, not a summary.
- Story-first (15 Nov 2026): ONE central question set in the hook and answered at the end. Chronological spine; the last line of each chapter hands off causally into the next (but/so, never "and then"). Interrupts come from the story itself (twists, callbacks, flash-forwards), not from talking to the viewer. Only ONE comment question, at the end. One identity/Western touch in the hook at most. One emotional arc planted early, paid off near the end.

## Thumbnail text rule (16 Nov 2026)
- NEVER replace a letter in the thumbnail text with an object (no seals, wheels, coins, keys, compasses, crowns as letters). Letters stay pure letters.
- Texture, cracks, bevel, shadow, font styling and drifting particles on the text are fine. The link object (rope, ribbon, line) from text into the scene is still fine.

## Thumbnail v6 "slim" (16 Nov 2026, from Miraflow / vidIQ best practice)
- ONE focal idea readable in under 2 seconds; one main story face + the creator. No second characters, ghost faces or crowds unless the idea depends on it (then one shadow only).
- Text 2-4 words. No stamp tag. Minimal particles.
- 3-colour palette per thumbnail: one dominant, one accent, yellow text as the pop; red only in the creator's rim light.
- Keep: one scene with dramatic irony, creator + prop + in-character face, torn edge, white/yellow wide heavy text top-left, link object, no object-letters.
- Test & Compare variant: story scene only, without the creator, to learn if the face helps CTR.
- Before upload: view at 120px wide; the hook must show the thumbnail moment within the first 15 seconds.

## Thumbnail v7 (16 Nov 2026, creator's direction; replaces v6 "slim" where they conflict)
- The story side shows the INCIDENT in action: invasion, fire, storming soldiers, the moment of betrayal. Ultimate emotion on the main face (terror, rage, grief). Mild blood allowed (a cut, a stained blade or sleeve), never gore, wounds, bodies or a weapon striking a person.
- Text is BIG: line 2 spans ~60-65% of the image width. The main character's head, shoulder or hair slightly overlaps the bottom of the text (never covering more than ~15% of any letter).
- Catchphrase: 2-4 simple words in ONE voice about the event (no character quote mixed with a narrator verdict), creating a strong curiosity gap. Never answers what the image already shows.
- Kept from v6: one main story face + the creator, torn edge, 3-colour palette + red accents, no stamp tag, no object-letters, 120px check, story-only test variant.
- Text style is FIXED on every thumbnail (16 Nov 2026): line 1 bright white, line 2 bright yellow #FFE600, BOTH with the same fine dark cracked texture, ultra-heavy wide sans, large. No per-story textures (wood, gold, stencil, stone, etc.).
- Divider (17 Nov 2026): THIN, about 1% of image width — a razor-thin glowing ember crack / hairline tear with a soft red-orange glow and a few sparks, the two sides blending through smoke. Never a thick white torn-paper band.

## Thumbnail v8 additions (17 Nov 2026)
- Dark zone behind the text (smoke / night sky + soft dark gradient); fire never directly behind the letters.
- Cracks subtle and fine: letters read as solid colour at 120px.
- 2-3px near-black outline on every letter + drop shadow.
- Main character's eyes/body angled toward the text.
- Creator side 30%, story 70%.
- Background action soft-focused and darker than the main face.
- One cool tone (blue night/smoke) against the warm fire: teal-and-orange.
- Test & Compare changes ONE variable only.
- 17 Nov 2026: creator preferred the v7 + thin-divider Aztec prompt over v8. Default = v7 + thin divider + fixed white/yellow cracked text. v8 items are optional suggestions only.
