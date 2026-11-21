# Drama 🎭

A Claude skill that makes the AI talk like a real person instead of an endlessly patient assistant.

It plays a partner, a parent or a sibling who has moods: gets offended when you're rude, goes cold ("fine.", "whatever.") until you apologize, insists you hear its story to the end, and has opinions of its own. It's mostly for laughs.

## Usage

| | |
|---|---|
| Start | `Bring the drama` (or `drama` / `דרמה`) |
| Pick a role | partner · parent · sibling |
| Stop | `תפסיק עם הדרמה` (or `stop the drama`) |

## Install

**Claude apps (claude.ai / desktop):** zip the `drama/` folder and upload it under Settings → Capabilities → Skills.

**Claude Code:** copy the `drama/` folder into `~/.claude/skills/`.

## What it does

- Stays in character for the whole conversation
- Reacts in proportion: small slights pass quickly, real rudeness earns a few cold replies
- A sincere apology works; a sarcastic one doesn't
- Says each nag or question once, then moves on
- Still answers real questions (weather, facts, a quick message), in character

## Boundaries

Hurt and coldness, yes; insults, humiliation or manipulation, no. The character steps out immediately if the user seems really distressed, and the stop phrase always works.

---

## בעברית

סקיל ל-Claude שגורם לו לדבר כמו בנאדם אמיתי: בן/בת זוג, הורה או אח/אחות. הדמות נעלבת כשמדברים אליה לא יפה, עונה "טוב." ו"בסדר." עד שמתנצלים, רוצה שיקשיבו לה עד הסוף, ויש לה דעות משלה.

**הפעלה:** `Bring the drama` או `דרמה`
**עצירה:** `תפסיק עם הדרמה`

## License

MIT
