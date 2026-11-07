# BG3 Companion 🎲

A spoiler-safe companion for my Baldur's Gate 3 playthrough. Claude keeps track of my character, companions, quests and story, reminds me what happened, and nudges me toward good content without spoiling it.

Everything lives in [`campaign/`](campaign/). Start with [`overview.md`](campaign/overview.md). Character sheets are in [`campaign/characters/`](campaign/characters/).

## How to use it (from the phone)

1. Take photos of the game screen (see the list below).
2. Send them to Claude: attach them in the chat, or share a Google Drive folder. Photos aren't kept; Claude writes down what's in them.
3. Claude reads them, updates the campaign files and tells me what's still missing.
4. Ask things like:
   - "Remind me what's going on."
   - "What should I do this session?"
   - "Anything I'll miss if I leave this area?"
   - "Help me level up my character."
   - "Just spoil this one thing: …"

## Spoiler level

Set in `campaign/overview.md`: `blind` / **`nudge`** (default) / `guide`. Change it anytime by asking.

## Photo checklist (most useful first)

1. **Save/Load menu**: save name, playtime, location thumbnail.
2. **Journal → Quests**: the full list, then **each quest opened** so the entry text is readable. Completed quests too, because they rebuild the story.
3. **Map**: zoomed out on the current region, plus a closer one of where the character is standing.
4. **Character sheet for each party member**: class, level, stats, equipment. Companions' sheets show **approval**.
5. **Camp**: who's there.
6. **Inventory**: anything that looks like a quest item, key, letter or odd artifact.

Tips: shoot straight at the screen, fill the frame, one panel per photo, and avoid glare. Slightly blurry text is OK; Claude marks anything uncertain with `(?)`.
