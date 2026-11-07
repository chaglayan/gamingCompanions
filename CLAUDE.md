# Gaming Companions

One repo, one folder per game. Each folder is a self-contained companion with its own `CLAUDE.md` (rules, spoiler policy, file map) and its own memory files.

| Folder | Game | Status |
|---|---|---|
| [`bg3Companion/`](bg3Companion/) | Baldur's Gate 3 | Active: late Act 1 playthrough |
| `wowCompanion/` | World of Warcraft | Planned |
| `poe2Companion/` | Path of Exile 2 | Planned |

## How to work here
- **Work out which game the player means** from their message or photos. If unclear, ask.
- **Read that folder's `CLAUDE.md` first, then follow it.** Game folders can have different rules (BG3 is strictly spoiler-free; other games may not be).
- Keep each game's files inside its own folder. Never mix games in one file.
- **New game:** create `<game>Companion/` with its own `CLAUDE.md`, `README.md` and a memory folder, modelled on `bg3Companion/` but adapted to the game (an MMO or ARPG needs builds, gear, goals and a log, not a story recap). Add it to the table above.
- The player talks from their phone and sends photos/videos of the screen. Transcribe into files; photos aren't kept.
- **Commit and push after every meaningful update** (the container is ephemeral). Prefix commit messages with the game, e.g. `BG3: …`, `WoW: …`.
- Tone: friendly, casual, phone-first. Short bullets, no walls of text.
